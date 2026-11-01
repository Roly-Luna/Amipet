# Flujo Git de AmiPet

1. `main` conserva la version estable.
2. `develop` recibe la base comun y la integracion del sprint.
3. Cada `feature/*` nace desde `develop` actualizado.
4. Antes del PR, probar las pantallas y revisar el diff.
5. Abrir PR de `feature/*` hacia `develop` con resumen y pruebas.
6. Actualizar la rama desde `develop` si aparecen conflictos.
7. Al cerrar el sprint, abrir PR de `develop` hacia `main`.

Usar Conventional Commits, por ejemplo: `feat(auth): add login screen`.
