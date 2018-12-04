# practica0-
## Comandos basicos

Configurar Nombre que salen en los commits
	git config --global user.name "dasdo"
  niciamos GIT en la carpeta donde esta el proyecto

	git init
Clonamos el repositorio de github o bitbucket

	git clone <url>
Añadimos todos los archivos para el commit

	git add .
Hacemos el primer commit

	git commit -m "Texto que identifique por que se hizo el commit"
  subimos al repositorio
	git push origin master
  GIT LOG
Muestra los logs de los commits

	git log
Muestras los cambios en los commits

	git log --oneline --stat
