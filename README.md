# HyperYI
# **HYPER-YI**
## Que encontraras en este post
Es una documento html y CSS creado apartir del curso de Git y Githab en platzi

De parte de Git: Comandos aprendidos:
Git init//Para crear una rama master y poder utilizar los comandos de git
mkdir//Crear una Carpeta
touch//Crear un archivo, puede ser un texto plano .txt
git cat//Para ver dentro de los archivos de texto plano
git status// Ver la rama en la que estamos y ver si hay cambios en los documentos 
git log// Ver la lista de todos los commits y la persona que los ha hecho
git add .//Agregar todos los datos modificados a staging
git commit -m "msg"//Pasarlo a un repositorio local
git commit -am "msg"//Guardarlo y pasarlo al repositorio local
git config --list// Vemos la lista de comandos
git config --list --show-origin//Configuraciones de usuario
git config --global user.name "nombre"//ponerse un nombre de usuario en git
git config --global user.email "gmail"//Poner un gmail al usuario git
history // Vemos los ultimos comandos que hemos hecho
git checkout 1j312h3123b123 blogpost.html // me deja ver el commit que guarde ahi
git checkout master // regreso al head y al ultimo commit guardado

*Ramas*
git branch// Vemos las ramas creadas
git branch header // Creamos la rama header para trabajar la parte de arriba
git  branch -d (Nombre)// Borramos una rama
git branch -D (N de la rama)// Forzamos la eliminacion de la rama
git checkout header// Voy a la rama header
gitk // vemos un software en el cual nos muestra las ramas y los merge creados
git log --all --graph --decorate --oneline// Vemos la historia de las ramas 

*Merge*
Esto unicamente se hacer cuando las ramas que vamos a fucionar ya fueron revisadas y sabes que estan listas para hacerles merge.
Vas a la rama principal del proyecto y traes la rama que quieres fusionar
git merge header// debo estar en master y eso hace que se me una la rama header con la master

*Repositorio Remoto*
git remote -v// vemos los repositorios que tenemos
got remote set-url origin (link github) //Cambiamos la url del repositorio remoto
git pull origin(repositorio remoto) master(rep local)// traemos los cambios del repositorio remoto al local
git push orgin master // Llevamos los cambios que tenemos en local al repositorio que tenemos en githab (el origin)


*BORRAR ARCHIVOS*
rm // con rm nombre.termianl 
rm --help// ver las distintas opciones que hay con rm
git reset --hard // Borra TODO
git reset --soft // Borra el historial y los registros

**Nota: Aun faltan muchos comandos, pronto los agregare **
Mi perfil en [Twitter](https://twitter.com/david_19y)
