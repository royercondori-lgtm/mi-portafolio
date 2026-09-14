# Guía del Proyecto: Trabajo Colaborativo en Git

Documentación detallada sobre el flujo de trabajo en Git y GitHub desarrollado durante el Laboratorio 03.

## Descripción del Proyecto

Este proyecto documenta las mejores prácticas para trabajar en equipo utilizando ramas, fusiones y resolución de conflictos en Git. Para verificar el estado de los archivos se recomienda usar el comando `git status` de forma frecuente.

### Pasos de Instalación y Uso

1. Clonar el repositorio remoto en tu máquina local.
2. Crear una nueva rama para tus cambios con `git checkout -b mi-rama`.
3. Realizar los cambios necesarios en el proyecto.
4. Confirmar y subir los cambios a la plataforma.

## Componentes y Requisitos

### Herramientas Requeridas

- Control de versiones con Git
- Repositorio alojado en GitHub
- Editor de código Visual Studio Code

### Checklist de Cumplimiento

- [x] Configuración inicial de usuario en Git
- [x] Creación y fusión de ramas locales
- [ ] Configuración de despliegue automático

## Resumen de Comandos Principales

| Comando      | Descripción                            | Ejemplo de Uso        |
| ------------ | -------------------------------------- | --------------------- |
| `git branch` | Lista o crea ramas en el repositorio   | `git branch Feature1` |
| `git merge`  | Integra los cambios de una rama a otra | `git merge Feature1`  |
| `git log`    | Muestra el historial de commits        | `git log --oneline`   |

## Ejemplo de Código

A continuación se presenta un script de automatización en Bash para actualizar la rama principal:

```bash
#!/bin/bash
echo "Actualizando repositorio..."
git checkout main
git pull origin main
echo "¡Repositorio actualizado con éxito!"
```
