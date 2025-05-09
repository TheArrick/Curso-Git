# Repositoria Remoto
## Conectar un repositorio local con uno remoto
Luego de hacer `git init` sobre un directorio. Para poder conectarlo a un repositorio remoto debemos hacer uso del comando `git remote add` y escribir la dirección del repositorio que esta alojado en GitHub 
```bash
git remote add origin https://github.com/usuario/repo.git
```
+ `origin` es un nombre estandar que representa el origen del repositorio remoto
+ Solo se requiere hacer este paso una vez.
  
## Subir cambios al repositorio
Luego de hacer commits en el local podemos subirlos los cambios al remoto, se usa el comando `git push`
```bash
git push origin main
```
+ `main` es la rama a la que apuntamos los cambios. Puede cambiarse a cualquier rama que el usuario vea convenientee

## Actualizar repositorio local
Para poder traer la ultima actualización del repositorio remoto y fusionarlo con la rama actual. 
```bash
git pull origin <rama>
```

Este comando descarga la ultima actualización de la rama que el usuario quiera

<p align="center">
    <img src="Images/gitpuhspull.jpg" alt="gitpushpull" width="400"/>
</p>

### Consejo
+ Siempre se hace un `git pull` antes de comenzar a trabajar para evitar problemas.

