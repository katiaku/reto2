# Pasos pasa subir un proyecto a Git

### Entrar en el directorio del proyecto

### Inicializar git 
```
git init
```
### Crear nuevo repositorio en GitHub

### Añadir el HTTPS del nuevo repositorio como la direccion del origen 
```
git remote add origin https://github.com/...
```
### Cambiar el nombre de la rama principal a main
```
git branch -M main
```
### Pasar el proyecto al repositorio remoto
```
git add .
git commit -m "Mensaje"
git push -u origin main 
```

# .gitignore

Los ficheros/archivos incluidos en el fichero .gitignore 
se ignoran automaticamente al subir los cambios al repositorio 
remoto.

En nuestro caso ignoramos al archivo reto_2 entero y a todos los 
ficheros .png.
