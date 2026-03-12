# LAB2_OPTMZ

link: https://colab.research.google.com/drive/1LVw08MUcgsTxZeLlpjHmHcI_EMwaPl1_?usp=sharing
Coder@usuario-Saturno-Series:~$ mkdir ProyectoCoders
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ mkdir src
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd ProyectoCoders/src
bash: cd: ProyectoCoders/src: No existe el archivo o el directorio
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
src
Coder@usuario-Saturno-Series:~/ProyectoCoders$ mkdir assets
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
assets  src
Coder@usuario-Saturno-Series:~/ProyectoCoders$ mkdir docs
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
assets  docs  src
Coder@usuario-Saturno-Series:~/ProyectoCoders$ mkdir tests
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
assets  docs  src  tests
Coder@usuario-Saturno-Series:~/ProyectoCoders$ mkdir config
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
assets  config  docs  src  tests
Coder@usuario-Saturno-Series:~/ProyectoCoders$ mkdir backup
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
assets  backup  config  docs  src  tests
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd src
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ touch app.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
app.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ touch database.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
app.txt  database.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ touch functions.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
app.txt  database.txt  functions.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ cd 
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd docs
Coder@usuario-Saturno-Series:~/ProyectoCoders/docs$ touch README.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/docs$ ls
README.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/docs$ cd ProyectoCoders
bash: cd: ProyectoCoders: No existe el archivo o el directorio
Coder@usuario-Saturno-Series:~/ProyectoCoders/docs$ cd
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd config
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ touch settings.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ ls
settings.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cd
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd config
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ ls
settings.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cp settings.txt
cp: falta el operando archivo de destino después de 'settings.txt'
Pruebe 'cp --help' para más información.
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cd settings
bash: cd: settings: No existe el archivo o el directorio
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cd settings.txt
bash: cd: settings.txt: No es un directorio
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cp -r settings.txt ^C
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cp -r settings.txt /ProyectoCoders/backup
cp: no se puede crear el fichero regular '/ProyectoCoders/backup': No existe el archivo o el directorio
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cp settings.txt ../backup/
Coder@usuario-Saturno-Series:~/ProyectoCoders/config$ cd
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd backup
Coder@usuario-Saturno-Series:~/ProyectoCoders/backup$ ls
settings.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/backup$ cd 
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd src
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ mkdir database
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
app.txt  database  database.txt  functions.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ mv database.txt database/
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
app.txt  database  functions.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ cd database
Coder@usuario-Saturno-Series:~/ProyectoCoders/src/database$ ls
database.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src/database$ cd 
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd src
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ cp functions.txt ../backup/
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ cd 
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd backup
Coder@usuario-Saturno-Series:~/ProyectoCoders/backup$ ls
functions.txt  settings.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/backup$ cd 
Coder@usuario-Saturno-Series:~$ cd ProyectoCoders
Coder@usuario-Saturno-Series:~/ProyectoCoders$ ls
assets  backup  config  docs  src  tests
Coder@usuario-Saturno-Series:~/ProyectoCoders$ cd src
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
app.txt  database  functions.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ mv app.txt main.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
database  functions.txt  main.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ rm functions.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ ls
database  main.txt
Coder@usuario-Saturno-Series:~/ProyectoCoders/src$ 
