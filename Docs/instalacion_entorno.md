[Volver](../README.md)

## Instalación de entorno
Vamos a utilizar __VSCode__ como herramienta de desarrollo y __Git__ para el control de versionado de nuestro código y __Github__ para almacenar dicho código en la nube. Existen otros como Bitbucket, Gitlab, Azure Devops. Todos ellos utilizan Git como base para realizar todas las operaciones.
Cada vez que avancen en las etapas, tendrán que descargar una nueva base de código. 

1. Instalar [Git](https://git-scm.com/downloads). Puedes leer una pequeña [introducción a Git](./index_git.md).
1. Instalar [Visual Studio Code](https://code.visualstudio.com/).
1. Crear la carpeta __HxLabs__.
1. Ir al [proyecto github](https://github.com/chbohm/HexactaLabs-NetCore_React-Initial) y crear un "fork" desde el botón
![forks](./images/forks_example.png)
1. Copiar al portapapeles la url del fork.
1. Clonar el proyecto forkeado de GitHub.
	1. __Desde linea de comandos:__ Correr este comando situados en __HxLabs__:  *git clone "url"*.
	1. __Desde visual code:__ abrir Visual Studio Code en la carpeta __HxLabs__.
		1. CTRL + SHIFT + P y escribir "git clone".
		1. Agregar la URL del proyecto y seleccionar una carpeta.
1. Estos pasos pueden usarse para cualquier proyecto que debamos clonar.
1. Luego, cuando comience la *etapa X* ir a la carpeta correspondiente y abrir una nueva instancia de VSCode, o directamente desde Code, *File/Open Folder*.

Debería quedar algo semejante a esto: 

![folders](./images/folders_git.png)

## Frontend

1. [Prerequisitos](./prerequisitos.md)
1. [Estructura de Carpetas](./estructura-carpetas.md)

## Backend
1. [Prerequisitos](./prerequisitosnetcore.md)
1. [Estructura de Carpetas](./estructura-carpetas-netcore.md)
1. [Troubleshooting](./troubleshooting.md)

