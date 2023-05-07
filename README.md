# Create universal artifact

Actions para crear un directorio donde alojar los archivos requeridos para la construcción de un artefacto.

## ¿Create universal artifact?

Este Actions facilita la construcción de un directorio que sirva como contenedor de los archivos requeridos para contruir un artefacto universal que puede ser subido a cualquier repositorio de artefactos.

## Prerrequisitos

Se debe indicar con la etiqueta 'with' algunos parametros.

1. Nombre del directorio principal (Repositorio).
2. Nombre del artefacto.
3. Concatenar variable de entorno "github.run_numbe", ejemplo: "proyect15" por defecto está "false", indicar "true" para habilitar.

## Instrucciones

1. Copiar el llamado del action en el maketplace de GitHub. Recomendamos usar siempre la ultima versión.

Ejemplo:

<p align="center">
  <img width="671" height="61" alt="action" src="public/img/action.PNG">
</p>

2. Pega en tu workflow y añade la etiqueta with: añadiendo los parametros: user_repo:, pass_repo: y  url_repo:.

Ejemplo:

<p align="center">
  <img width="667" height="149" alt="action_with" src="public/img/action_with.PNG">
</p>

Se debe indicar el valores que corresponden. Nota: se puedes colocar los valores directos otra forma de trabajar es variabilizar los valores.

Ejemplo 2:

<p align="center">
  <img width="654" height="150" alt="action_with_variables" src="public/img/action_with_variables.PNG">
</p>

## Limitaciones

De momento solo se realizaron pruebas con repositorios GitLab. No se descarta su compatibiliad con otras compañias.