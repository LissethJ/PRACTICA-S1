PRACTICA GIT - GITHUB 

lista de comandos 

* Para verificar si tienes instalado el Git
```bash
git --version
````
* Para limpiar la pantalla del terminal
```bash
clear
````
* Para configurar el git 
```bash
git config --global user.email "lisseth.delgadillo@gmail.com"
git config --global user.name "LissethD"
````
* Para ver los cambios en la configuracion 
```bash
-l
````
* Para entrar a la carpeta en la que se va a trabajar 
```bash
cd PRACTICA-S1
````
* Para ver los archivos que hay dentro de esa carpeta
```bash
ls
````
* Al crear un nuevo proyecto se realiza 
```bash
git init
````
* Para crear un directorio a otro desde la terminal 
```bash
mkdir carpeta2
````
* Para crear un archivo (file) dentro de una carpeta desde la terminal 
```bash
touch index.html
````
* Para ver los cambios realizados 
```bash
git status
````
* Para agregar un archivo al staging area
```bash
git add
````
* Para remover los archivos que habia agregado al staging area
```bash
git rm -r --cached
````
* Si queremos agregar los cambios inmediatamente anteriores 
```bash
git add .
````
*  Para agregar todos los cambios de una sola vez 
```bash
git add -A
````
* Para registrar el cambio que realizamos 
```bash
git commit -m "nombre del commit"
````
* Para ver los commits que hemos creado
```bash
git log
````
* Para ver el branch en el que me ubico 
```bash
git branch -r 
````
* Para ver todo el branch
```bash
git branch -a
````
* Para cambiar de branch master a main
```bash
git branch -M
```

