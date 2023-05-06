ABRIMOS LA TERMINAL DE WINDOWS
PARA IMPRIMIR LA UBICACION ACTUAL USAMOS: pwd
2  Para crear una carpeta llamada ejercicios en el escritorio:
  cd ~/Desktop
mkdir ejercicios
Para cambiar la ubicación a la nueva carpeta creada:
cd ~/Desktop/ejercicios
Para abrir la carpeta con VSCode:
code .
Para crear una carpeta llamada ejercicio1 dentro de la carpeta ejercicios:
mkdir ejercicio1

Para crear un archivo vacío llamado README.md dentro de la carpeta ejercicio1:
touch ejercicio1/README.md

Para configurar nombre e email globalmente en git:
git config --global user.name "Tu nombre"
git config --global user.email "tu_correo@ejemplo.com"

Para inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios:
cd ~/Desktop/ejercicios
git init

Para crear un primer commit con el mensaje “Versión Inicial”:
git add .
git commit -m "Versión Inicial"

Para agregar al README.md los comandos que ejecutaron en cada paso:
Editar el archivo README.md con un editor de texto y agregar los comandos que se utilizaron en cada paso.

Para crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”:

git add .
git commit -m "Agrega solución primer ejercicio"


Para publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1:
git remote add origin https://github.com/tu_usuario/aspirantes-mir-ejercicio-1.git
git branch -M main
git push -u origin main
