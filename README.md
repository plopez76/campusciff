# EJERCICIOS GIT.

**2.00** cd Ejercicios_Git # Me situo en la carpeta que quiero que sea mi Repositorio local  
         git init # Lo inicializo  
**2.01** Crear Repositorio remoto en GitHub   
**2.02** git	clone git@github.com:plopez76/campusciff.git # Clonar Repositorio en local  
**2.03** cd campusciff # Me situo dentro de campusciff
         touch README.md # Creo el archivo README.md  
         notepad README.md #Cambié por defecto el editor de texto a notepad porque me resulta mas amigable; el comando que                             utilicé fue: git config --global core.editor notepad.  
         git add . #añado README.md a Staging area  
**2.04** git commit -m'commit inicial' subo README.md a mi repositorio local  
**2.05** git push -u origin master #Subo README.md a mi repositorio remoto  
**2.06** mkdir privada # Creo el directorio privada  
         touch privado.txt # Creo el archivo privado.txt  
**2.07** touch .gitignore # Creo el archivo .gitignore  
         echo privado.txt > .gitignore # Añado privado.txt a la lista de excepciones  
         echo privada/ >> .gitignore # Añado privada a la lista de excepciones  
**2.08** touch 1.txt # Añado 1.txt  
**2.09** git tag # Creo el tag v0.1  
**2.10** git push --tags # Subo el tag a mi repo remoto  
**2.11** git checkout -b v0.2 # Creo la rama v0.2 y me posiciono en ella  
**2.12** touch 2.txt   
**2.13** git add .  
         git commit -m'archivo 1.txt creado en v0.2'   
**2.14** git checkout master # Posicionarme en la rama master  
         git merge v0.2 #Hacer un merge en la rama master  
**2.15** echo Hola > 1.txt  
         git add .  
         git commit -m'commit Hola 1.txt' # Escribir Hola en 1.txt en rama master  
**2.16** git checkout v.02  
         echo Adios > 1.txt  
         git add .  
         git commit -m'Provocando conflicto' # # Escribir Adios en 1.txt en rama v0.2 
**2.17** git checkout master # Posicionarme en la rama master  
         git merge v0.2 #Hacer un merge en la rama master  
**2.18** git branch # Listar las ramas  
**2.19** Entro en 1.txt y borro todo menos HolaAdios  
         git add .  
         git status # Para comprobar que todo está listo para comiterar  
         git commit -m'Merge solucionado'  
**2.20** git tag v0.2 # Creo tag v0.2  
         git branch -d v0.2 # Borro la rama v0.2  
**2.21** git log  


