# Cyberpunk2030

Proyecto de Unity para trabajar en equipo.

## Abrir el proyecto

1. Instala **Unity Hub** y **Unity 6000.4.12f1**.
2. Clona este repositorio con GitHub Desktop o Git.
3. En Unity Hub, selecciona **Add / Añadir proyecto desde disco** y elige la carpeta del repositorio.
4. Abre el proyecto y espera a que Unity importe los recursos y descargue los paquetes.

## Trabajar en equipo

- Crea una rama para cada tarea y abre un pull request para revisar los cambios antes de integrarlos en `main`.
- Descarga los cambios del equipo antes de empezar a trabajar.
- Incluye siempre los archivos `.meta` junto con sus recursos. Mueve o renombra los recursos desde Unity para conservar sus referencias.
- Coordina los cambios en escenas y prefabs para evitar que dos personas editen el mismo archivo a la vez.
- Guarda las escenas y recursos antes de crear un commit.

Se comparten `Assets`, `Packages` y `ProjectSettings`. Unity regenera las carpetas temporales y de caché, que están excluidas del repositorio.

El propietario puede invitar al equipo desde **Settings → Collaborators** en GitHub.
