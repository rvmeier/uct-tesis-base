## Formato para tesis o trabajo de título
#### Ingeniería Civil en Informática
#### Universidad Católica de Temuco.

Estos archivos sirven como base para escribir la tesis o trabajo de título de Ingeniería Civil en Informática.

> Basado en el trabajo original realizado por Cesar Fernández y las modificaciones introducidas por Daniel San Martin


 La estructura es la siguiente

  - apendices/
  - capitulos/
  - figuras/
  - extras/
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

### Créditos

- César Fernández
- Daniel San Martin

### To-dos

 - Escribir tesis

### License
 The MIT License (MIT)

Copyright (c) 2015

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
