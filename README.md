# Fundamentos Git 
Para empezar, podemos ya sea crear un repositorio desde cero o clonar uno ya existenten.
## Iniciar un repositorio
+ En un directorio del sistema se escribe el comando
```bash
git init
```
Este comando inicializa un repositorio vacío en el directorio actual. Automáticamente se crea un directorio oculto llamado .git que contiene toda la configuración y el historial del repositorio.


## Clonar
Para poder hacer uso de un repositorio ya existente alojado en GitHub, necesitamos su URL
```bash
git clone <url-repositorio>
```
Esto descargá todos los archivos que este contenga.

## Añadir archivos Staged
+ Staged es una zona intermedia entre los archivos modificados y los commit
+ Permite tener un control sobre los cambios antes de confirmarlos
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
## Estado actual del repositorio
Para ver el estado del repositorio.
```bash
git status
```


## Realizar buen mensaje en el commit
+ Mensaje empieza con un verbo en infinitivo
+ Maximo 50 caracteres 
+ Evitar mensajes genericos
## Heurística 
| Tipo       | Descripción                                             |
| ---------- | ------------------------------------------------------- |
| `feat`     | Nueva funcionalidad                                     |
| `fix`      | Corrección de errores                                   |
| `docs`     | Cambios en la documentación                             |
| `style`    | Cambios de formato                                      |
| `refactor` | Refactorización de código                               |
| `perf`     | Mejoras de rendimiento                                  |
| `test`     | Añadir o modificar pruebas                              |
| `build`    | Cambios en la configuración de build o despliegue       |







