# API Inventario (mini)

- Endpoints simulados: GET /products, POST /products
- Objetivo: repo auditable (versiones + estados + trazabilidad)

## Cómo ejecutar (simulado)

- No se requiere despliegue real. Este repositorio se usa para GCS.

## Convención

- Commits: chore/docs/feat/fix + referencia ISSUE-xx
- Versiones: SemVer (vMAJOR.MINOR.PATCH)

## Trazabilidad

Los cambios del proyecto deben estar vinculados a Issues, commits y Pull Requests.

## Flujo de trazabilidad

Cada cambio debe seguir el flujo:

Issue → Branch → Commit → Pull Request → Review → Merge → Release

Los commits deben utilizar la convención definida en el repositorio y hacer referencia al Issue correspondiente.

## Auditoría de configuración

El repositorio mantiene sus elementos de configuración versionados y organizados en directorios definidos. Los cambios deben gestionarse mediante Issues, ramas, Pull Requests y commits trazables.

La línea base de entrega corresponde a la rama `main` y las versiones se gestionan mediante etiquetas SemVer.