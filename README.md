# GitHub Actions Tutorial

Actividad: configuración de Integración Continua (CI) con GitHub Actions.

## Integrantes
- Integrante 1: COMPLETAR NOMBRE
- Integrante 2: COMPLETAR NOMBRE
- Integrante 3: COMPLETAR NOMBRE
- Integrante 4: COMPLETAR NOMBRE

## Qué se implementó
- Workflow `CI`.
- Ejecución automática con `push` a `main`.
- Ejecución con `pull_request` hacia `main`.
- Ejecución manual mediante `workflow_dispatch`.
- Job `build` sobre `ubuntu-latest`.
- Variables de entorno.
- Uso de GitHub Secrets (`USERNAME` y `PASSWORD`).
- Uso de una variable de repositorio (`PROJECT_VERSION`).
- Mensajes de prueba mediante `echo`.

## Configuración pendiente en GitHub
Antes de ejecutar el workflow, crear:
- Secret `USERNAME`
- Secret `PASSWORD`
- Variable `PROJECT_VERSION`

No colocar contraseñas reales dentro del código.
