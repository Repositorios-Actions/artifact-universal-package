# Create universal artifact

Actions para crear un directorio donde alojar los archivos requeridos para la construcción de un artefacto.

## ¿Create universal artifact?

Este Actions facilita la construcción de un directorio que sirva como contenedor de los archivos requeridos para contruir un artefacto universal que puede ser subido a cualquier repositorio de artefactos.

## Prerrequisitos

Se debe indicar con la etiqueta 'with' algunos parametros.

1. Nombre del directorio principal (Repositorio).
2. Nombre del artefacto.

## Instrucciones

1. Copiar el llamado del action en el maketplace de GitHub. Recomendamos usar siempre la ultima versión.

Ejemplo:

<p align="center">
  <img width="671" height="61" alt="action" src="public/img/action.png">
</p>

2. Pega en tu workflow y añade la etiqueta with: añadiendo los parametros: "work_dir" y "artifact_name".

Ejemplo:

<p align="center">
  <img width="667" height="149" alt="action_with" src="public/img/action_with.png">
</p>

Se debe indicar el valores que corresponden. Nota: se puedes colocar los valores directos otra forma de trabajar es variabilizar los valores.

Ejemplo 2:

<p align="center">
  <img width="654" height="150" alt="action_with_variables" src="public/img/action_with_variables.png">
</p>

## Ejecución por consola

1- mkdir -p work_dir/artifact_name
2- cd work_dir && ls -l