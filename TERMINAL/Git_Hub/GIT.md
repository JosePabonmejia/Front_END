//First for proyect
$ git show : muestra los cambios que tuvo el repositorio 
$ git diff idcommit idcimmit2 : git diff b6028b8526a162415e56ed16a48115ce08dced15 41c51e25d05baa2e3018f81688a749532ab1d7ce
$ git log : para ver todos los commits
$ git log --graph : Para ver commits con ramas y todo 
$ git branch o git-branch --all :Muestra todas las ramas existentes
$ git branch -nombre de la rama-: Con este comando se genera una nueva rama.
$ git checkout -nombre de la rama-: Con este comando puedes saltar de una rama a otra.
$ git reset id-commit: Nos lleva a cualquier commit no importa la rama, ya que identificamos el id del tag., eliminando el historial de los commit posteriores al tag seleccionado.





//Normales
cd .. : ir a carpeta anterior 
cat archivo.txt: mostrar rapidamente el contenido de un archivo 
ATAJO apretar TAB luego de colocar las siglas de cualquier archivo
history : saber todos los comandos realizados 
si queremos regresar algun comando colocamos signo de admiracion y luego el numero de comando que quiero !40
$ rm: Borrar archivos vacio.txt 
$ mv :Renombrar archivos 
$ pwd: saber donde estamos 
$ ls : listado 
$ ls -al : listado especifico que muestra hasta documentos ocultos  
$ mkdir:Crea una carpeta
$ touch :Crea un archivo

//Mas usados

$ git status : Estatus del proyecto 

$ git config --global user.email "ejemplo@gmail.com"

$ git init : Crea un repositorio 

$ git add ejemplo.txt o tambien git add . : Agrega el archivo seleccionado 

$ git commit -m "version 1" : Hacer un commit 

$ git remote add origin @url Quick Setup

$ git push : para subir datos a la nube

$ git fetch : trae actualizaciones del proytecto, del servidor remoto 

$ git merge : combina los ultimos cambios del servidor remoto 

$ git pull origin main: hace fetch y merge al mismo tiempo
 
$ git branch : crea una rama 

$ git show : muestra datos importantes del estado del repositorio

$ git checkout "rama": entramos en la rama   

$ touch vacio.txt : crear un archivo vacio 

$ git rm --cached texto.txt : elimina pero sigue en la memoria RAM

$ git config --list : configuracion para git hub 

$ git show ejemplo.txt 

$ git log : para ver todos los commits

$ git log --graph : Para ver commits con ramas y todo 

$ git diff :luego utilizar el comando log se extrae un codigo de commit para hacer la comparacion

$ git reset 57b95a590dc4c5f90e42fd6fd6c664668bc461c9 --soft y hard nos regresa al estado anterior o futuro del commit 


//Con proyectos muy grandes 

$ git log --oneline:Te muestra el id commit y el título del commit.

$ git log --decorate: Te muestra donde se encuentra el head point en el log.

$ git log --stat: Explica el número de líneas que se cambiaron brevemente.

$ git log -p: Explica el número de líneas que se cambiaron y te muestra que se cambió en el contenido.

$ git shortlog: Indica que commits ha realizado un usuario, mostrando el usuario y el título de sus commits.

$ git log --graph --oneline --decorate y

$ git log --pretty=format:"%cn hizo un commit %h el dia %cd": Muestra mensajes personalizados de los commits.

$ git log -3: Limitamos el número de commits.

$ git log --after=“2018-1-2”

$ git log --after=“today” y

$ git log --after=“2018-1-2” --before=“today”: Commits para localizar por fechas.

$ git log --author=“Name Author”: Commits hechos por autor que cumplan exactamente con el nombre.

$ git log --grep=“INVIE”: Busca los commits que cumplan tal cual está escrito entre las comillas.

$ git log --grep=“INVIE” –i: Busca los commits que cumplan sin importar mayúsculas o minúsculas.

$ git log – index.html: Busca los commits en un archivo en específico.

$ git log -S “Por contenido”: Buscar los commits con el contenido dentro del archivo.

$ git log > log.txt: guardar los logs en un archivo txt

//Ramas

$ git branch o git-branch --all :Muestra todas las ramas existentes

$ gitk : Muestra las ramas de manera visual habre una herramienta

$ git branch -nombre de la rama-: Con este comando se genera una nueva rama.

$ git checkout -nombre de la rama-: Con este comando puedes saltar de una rama a otra.

$ git checkout -b rama: Genera una rama y nos mueve a ella automáticamente, Es decir, es la combinación de git branch y git checkout al mismo tiempo.

$ git reset id-commit: Nos lleva a cualquier commit no importa la rama, ya que identificamos el id del tag., eliminando el historial de los commit posteriores al tag seleccionado.

$ git checkout rama-o-id-commit: Nos lleva a cualquier commit sin borrar los commit posteriores al tag seleccionado.

$ git show branch: Nos muestra las ramas creadas 

$ git 

$ git log --all --graph --decorate --oneline  

🚩//Cuando queremos anclar un proyecto local a un repositorio en la web

$ git remote add origin  https://github.com/JosePabonmejia/HTML-CSS_Bravo.git : Jalamos el repositorio
$ git remote -v : Nos muestra fetch y push
$ git push origin master : llevar datos al repo
Si da errror usar por el historial de commits de git :
$ git pull origin master --allow-unrelated-histories : Fuciona los historiales de commits
para finalizar $ git pull origin master


🚩//Como cambiar de rama 
$ git branch -m main 
$ git push origin main 

//Configurar múltiples colaboradores en un repositorio de GitHub pasos

$ git clone htttp.etc : Para clona lo que exista en el repo.
$ vim historia.txt : Muestra el archivo historia en el cmd
$ git status : Estado del repo 
$ git commit -am "Primer cimmit desde el contrato": No se coloca ad por que solo fue un cambio pequeño 
$ git pull origin main : Traemos lo que hay en internet 
$ git log : para ver los commits 
$ git log --graph : Para ver commits con ramas y todo 
$ git push origin master : para mandar los datos al repo 
luego comocamos nuestros datos como correo y contraseña 
pero primero debemos estar agregados en el repo como colaboradores

//Flujo de trabajo profesional: Haciendo merge de ramas de desarrollo a master
Por lo general la empresa te manda una rama para que puedas trabahar 

$ git pull origin "rama nombre": Para traer todo lo que hay an la rama 
$ git checkout "rama" : Para entrar en la rama 
se hecen los cambios y hacemos un git commit am

