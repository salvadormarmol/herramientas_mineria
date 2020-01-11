# R

- Es un entorno y lenguaje de programación con enfoque estadístico
- Se trata de uno de los lenguajes más utilizados en investigación por la comunidad estadística 
- Es muy popular en 
	- minería de datos 
	- la investigación biomédica
	- la bioinformática 
	- matemáticas financieras. 
- Cuenta con gran cantidad de bibliotecas o paquetes con funcionalidades de cálculo o visualización.
- R es gratuito y se distribuye bajo la licencia GNU GPL. 
- Está disponible para los sistemas operativos Windows, Macintosh, Unix y GNU/Linux.

## Historia

- Desarrollado en 1993 por Ross Ihaka y Robert Gentleman en la Universidad de Auckland
- Fue creado utilizando un interprete tipo Scheme (1975) y la sintaxis del lenguaje estadístico S (1976)
	- Da como resultado un lenguaje en apariencia muy similar a S, pero el uso de fondo y la semántica es derivado de Scheme

## Descargar tutoriales

[Básico](Intro_to_R.zip)
[Avanzado](Advanced_R.zip)

### Instrucciones para su ejecución

Una vez descargados y desempaquetados las carpetas comprimidas ejecutar las siguientes instrucciones

```R
rm(list=ls())
install.packages("swirl")
library("swirl")
setwd(<sustituye esto por la trayectoria donde se encuentra el directorio del tutorial>)
install_course_directory("Intro_to_R")
install_course_directory("Advanced_R")
swirl()
```

Da tu nombre, selecciona el tutorial que deseas y sigue las instrucciones
