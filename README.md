# Fundamentos Git 
Para empezar, podemos ya sea crear un repositorio desde cero o clonar uno ya existenten.
## Iniciar un repositorio
+ En un directorio del sistema se escribe el comando `git init` t
+ Se genera automaticamente el directorio oculto `.git`

## Clonar
+ Con el comando `git clone <URL>` 

## Añadir archivos Staged
```bash
git add archivo.extension
```
O en caso de querer añadir todo los cambios del directorio actual

```bash
git add .
```
## Hacer un commit
+ Un commit es un guardado del estado de los archivos. 
```bash
git commit -m "Mensaje"
```
+ El mensaje debe ser claro y resumir cual es la nueva funcionalidad o el cambio realizado.

## Realizar buen mensaje en el commit
+ Mensaje empieza con un verbo en infinitivo
+ Maximo 50 caracteres 
+ Evitar mensajes genericos
## Heurística 
+ feat: Nueva característica
+ fix:  Bug arreglado
+ perf: Mejora de rendimiento
+ build: Cambios en el despliegue 
+ docs: Cambios en la documentación
+ refactor: Refactorización de codigo
+ style: Cambios de formato
+ test: Test



