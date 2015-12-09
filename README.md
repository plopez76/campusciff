EJERCICIOS GIT.

2.0 cd Ejercicios_Git # Me situo en la carpeta que quiero que sea mi Repositorio local
    git init # Lo inicializo
2.1 Crear Repositorio remoto en GitHub 
2.2 git	clone git@github.com:plopez76/campusciff.git # Clonar Repositorio en local
2.3 cd campusciff # Me situo dentro de campusciff
    touch README.md # Creo el archivo README.md
    notepad README.md #Cambié por defecto el editor de texto a notepad porque me resulta mas amigable; el comando que                        utilicé fue: git config --global core.editor notepad.
    git add . #añado README.md a Staging area
2.4 git commit -m'commit inicial' subo README.md a mi repositorio local
2.5 git push -u origin master #Subo README.md a mi repositorio remoto
2.6 mkdir privada # Creo el directorio privada
    touch privado.txt # Creo el archivo privado.txt
2.7 touch .gitignore # Creo el archivo .gitignore
    echo privado.txt > .gitignore # Añado privado.txt a la lista de excepciones
    echo privada/ >> .gitignore # Añado privada a la lista de excepciones