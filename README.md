# PASOS PARA TRABAJAR CON GITHUB

### Si es la primera vez que subiremos un cambio, debemos seguir el siguiente flujo:

1. Crear repositorio público, por ejemplo con nombre "ejemplo"
2. Ir a mi proyecto, abrir una terminal en Visual Studio Code y ejecutar los siguientes comandos:

Solo se ejecuta una vez en la historia del proyecto, este comando incializa el repositorio  a nivel local:
```
   git init
```

Este comando agrega todos los archivos que guardaremos en el repositorio:
```
   git add .
```

Este comando le dará un título a la versión del proyecto que estamos guardando en el repositorio:
```
   git commit -m "first commit"
```

Este comando conecta el repositorio local con el repositorio remoto creado en el paso 1:
```
   git remote add origin https://github.com/<tu_usuario_github>/ejemplo.git
```

Este comando empujará los cambios locales al repositorio remoto de github:
```
   git push -u origin master
```

---

### Si NO es la primera vez que subiremos un cambio, debemos seguir el siguiente flujo:

Este comando agrega todos los archivos que guardaremos en el repositorio:
```
   git add .
```

Este comando le dará un título a la versión del proyecto que estamos guardando en el repositorio:
```
   git commit -m "first commit"
```

Este comando empujará los cambios locales al repositorio remoto de github:
```
   git push -u origin master
```

