# Ramas
Las ramas permiten desarrollar nuevas funcionalidades o ideas de forma aislada, sin afectar el código principal. Esto hace que el trabajo colaborativo y el control de versiones sean más ordenados y seguros.
Por defecto, Git crea una rama principal llamada main o master.
A continuación se hara un listado de los comandos más utiles en cuanto a ramas
## Crear una nueva rama
```bash
git branch <nombre-rama>
```
## Moverse entre ramas
```bash
git switch <nombre-rama>
```

## Mostrar todas las ramas
```bash
git branch
```
## Borrar ramas
```bash
git switch -d <nombre-rama>
```

## Merge entre ramas
+ Este comando permite combinar los cambios entre una rama y la main
```branch
git branch -d <nombre-rama>
```

## Buenas Practicas
+ Nombra tus ramas de forma clara
+ Trabaja en ramas separadas por funcionalidad.
+ Haz merge solo cuando todo funcione correctamente.
+ Elimina ramas que ya no uses para mantener limpio tu repositorio.




