# perfil-github

Repo **público** `pbeyflo/pbeyflo`: GitHub muestra su `README.md` en la portada
del perfil. Todo lo que se escriba aquí es visible para cualquiera.

- Al añadir un proyecto nuevo, añadirlo a la tabla de Juegos o Herramientas.
- Los demás repos son privados: no enlazarlos (darían 404 a los visitantes).
- Nombre, bio y ubicación del perfil se cambian con
  `gh api -X PATCH user -f name=… -f bio=… -f location=…`, que pide el scope
  `user` (`gh auth refresh -h github.com -s user`, interactivo: lo corre el usuario).
- Datos públicos autorizados por el usuario (2026-10-20): nombre completo, UPV/ETSInf,
  València. Nada más personal.
