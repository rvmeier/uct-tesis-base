## Formato para tesis o trabajo de título
#### Ingeniería Civil en Informática
#### Universidad Católica de Temuco.

Estos archivos sirven como base para escribir la tesis o trabajo de título de Ingeniería Civil en Informática.

> Basado en el trabajo original realizado por Cesar Fernández y las modificaciones introducidas por Daniel San Martin


 La estructura es la siguiente

  - apendices/
  - capitulos/
  - figuras/
  - tesis.tex
  - referencias.bib
  - Makefile

### Compilación

Para generar el pdf utilizando el Makefile tienes que escribir

```sh
$ make all TARGET=tesis
```

Para limpiar archivos auxiliares

```sh
$ make clean TARGET=tesis
```

En donde tesis es el nombre del archivo .tex original

### Contribuciones

En caso de modificar o agregar elementos útiles por favor enviar los cambios al repositorio.

### To-dos
 - Escribir tesis
