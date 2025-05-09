# Repositoria Remoto
## Conectar un repositorio local con un repositorio remoto
Para poder conectar nuestro local a un repositorio remoto debemos hacer uso del comando `git remote add` y escribir la dirección del repositorio que esta alojado en GitHub 
```bash
git remote add origin https://github.com/usuario/repo.git
```

## Subir cambios al repositorio
Para subir los cambios del repositorio local al remoto, se usa el comando `git push`
```bash
git push origin main
```

## Actualizar repositorio local
```bash
git pull origin <rama>
```

Este comando descarga la ultima actualización de la rama que el usuario quiera

<p>
    <img src="Images/gitpushpull.jpg" alt="gitpushpull" width="400"/>
</p>

### Consejo
+ Siempre se hace un `git pull` antes de realizar cualquier cambio

