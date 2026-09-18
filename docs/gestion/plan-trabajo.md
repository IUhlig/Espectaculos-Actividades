# Procedimiento de gestión de configuración

## 1. Objetivo

Definir el procedimiento utilizado por el equipo para gestionar los elementos de configuración del proyecto, controlar sus modificaciones y mantener la trazabilidad de los cambios.

## 2. Repositorio

El proyecto utiliza GitHub como repositorio de control de versiones.

La rama principal es `main`, que contiene los cambios integrados y validados.

## 3. Estrategia de ramas

Para desarrollar una actividad se creará una rama independiente a partir de `main`.

Convenciones:

- `feature/nombre`: desarrollo de una funcionalidad.
- `docs/nombre`: elaboración o modificación de documentación.
- `fix/nombre`: corrección de un defecto.

## 4. Procedimiento de cambios

1. Actualizar la rama local `main`.
2. Crear una rama para la actividad.
3. Realizar los cambios.
4. Crear commits.
5. Publicar la rama en GitHub.
6. Integrar los cambios a `main`.

## 5. Reglas de integración

- No realizar cambios directos en `main`.
- Revisar los cambios antes de integrarlos.
- Mantener la documentación actualizada.