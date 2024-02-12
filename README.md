# PASOS PARA TRABAJAR CON GITHUB

### Si es la primera vez que subiremos un cambio, debemos seguir el siguiente flujo:

1. Crear repositorio público, por ejemplo con nombre "ejemplo"
2. Ir a mi proyecto, abrir una terminal y ejecutar los siguientes comandos
```
   git init
```
(Solo se ejecuta una vez en la historia del proyecto): Este comando incializa el repositorio  a nivel local
```
   git add .
```
Este comando agrega todos los archivos que guardaremos en el repositorio
```
   git commit -m "first commit"
```
Este comando le dará un título a la versión del proyecto que estamos guardando en el repositorio
```
   git remote add origin https://github.com/<tu_usuario_github>/ejemplo.git
```
Este comando conecta el repositorio local con el repositorio remoto creado en el paso 1.
```
   git push -u origin master
```
Este comando empujará los cambios locales al repositorio remoto de github

### Si NO es la primera vez que subiremos un cambio, debemos seguir el siguiente flujo:
```
   git add .
```
Este comando agrega todos los archivos que guardaremos en el repositorio
```
   git commit -m "first commit"
```
Este comando le dará un título a la versión del proyecto que estamos guardando en el repositorio
```
   git push -u origin master
```
Este comando empujará los cambios locales al repositorio remoto de github
