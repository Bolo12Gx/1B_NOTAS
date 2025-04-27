Clase 21-04-2025
    Shortcuts
    ctrl+shift+p ----------> Command Palette
    ctrl+d ----------------> Multiselect Cursor (De a una palabra a la vez)
    ctrl+F2 ---------------> Multiselect Cursor (Todos a la vez)
    ctrl+K+C---------------> Agregar Comment Code Block y para eliminar ctrl+K+U
        <!-- Hola como estas -->
    ctrl+P ----------------> Quick Open
    ctr+B -----------------> Toggle sidebar
    ctrl+space ------------> Autocomplete
    ctrl+shift+alt --------> Cortado matricial 
Clase  22-04-2025
    Workspace or Workdirectory (ws/wd), ubicado en la raiz del dico ----> c/workspace
    <!-- LINUX COMMAND --> en la terminal
    ls ----> lista de archivos
    ls -a ---->lista de archivos ocultos
    pwd ----> posicion de directorio de trabajo (ws)
    mkdir ---> create new directory
    cp ----> copy files or directories
    kill -----> terminate process by sending a signal
    rm -----> remove files or directories 
    <!-- GIT -->
    Para cada PC se utiliza el "git global config
    Para cada nuevo proyecto
        1. Git -int renombrar
        git branch main
        git checkout main
        git status 
        git add para hacer tracking a un archivo o "git add ." hacer tracking a todos
        git commit -m"name" guardar el avance
        VINCULADO A LA NUBE
        git pull ------> Bajar el codigo de la nube
        git push ------> Subir el codigo
            Ejemplo
            git pull >> compiler >> (verificar si hay error) >> git push
Clase 23-04-2025
    Comandos git
        git clone "URL" -------> se coloca la URL donde se encuentra el proyecto en el git
        git log -----> Lista de commit (saves)
            git log --decorate --online
        git checkout -----> Ubicacion del archivo
        git reset ------> Regresa todos los archivos al antiguo commit, una vez regresado al commit anterior, se borran los commits guardados despues del commit regresado(quiere decir:  si estoy en el commit 5 y quiero regresar al commit 3, el commit 4 se borrara)
        git tag ------> Debido a la creacion de muchos commit a lo largo del proyecto, este comando ayuda a poner una "etiqueta" para identificarlos con mayor rapidez.
            