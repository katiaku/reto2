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
