
## Título: Multithreading en Linux con OpenMP: Prácticas de Programación para Procesadores Multinúcleo

Este repositorio contiene los programas desarrollados para la práctica de la asignatura Arquitectura de Sistemas y Software de Base de 4º de Ingeniería de la Salud, ejecutados en un entorno Linux. El proyecto aborda la programación de procesadores multinúcleo utilizando OpenMP en un entorno Linux, explorando técnicas de paralelización, sincronización de hilos, y optimización del rendimiento en cálculos complejos como la estimación del valor de Pi.

## 1. Contenidos del Repositorio 
El repositorio está organizado en varias carpetas principales: /data, /src, /docs, y un archivo adicional. Cada uno de estos elementos contiene componentes relevantes para el proyecto
### 1.1. Código fuente (src)
La carpeta /src contiene los scripts y programas desarrollados durante la práctica:
- **Programas en C:**
  [hello.c](src/hello.c): Programa básico "Hello World" en C. 
  [hello_par.c](src/hello_par.c): Versión paralela del programa "Hello World" usando OpenMP.
  [pi_serie.c](src/pi_serie.c): Estimación secuencial del valor de Pi.
  [pi_par1.c](src/pi_par1.c): Primera versión paralela para estimar el valor de Pi.
  [pi_par2.c](src/pi_par2.c): Optimización usando private.
  [pi_par3.c](src/pi_par3.c): Implementación con región crítica (critical).
  [pi_par4.c](src/pi_par4.c): Versión optimizada utilizando atomic.
  [pi_par5.c](src/pi_par5.c): Versión final con reducción paralela para mejor rendimiento
  
### 1.2. Documentos (docs)
La carpeta /docs incluye el documento:
[Procesadores-multinucleo-openmp-PPC.pdf](docs/Procesadores-multinucleo-openmp-PPC.pdf): PDF del trabajo.
  
## 2. Características Principales
-**Lenguaje utilizado:** C con OpenMP
-**Entorno:** Sistema operativo: Linux
-**Temas abordados:**
  - Creación y gestión de hilos.
  - Sincronización de hilos con critical y atomic.
  - Optimización de rendimiento en cálculos paralelos.
-**Programas desarrollados:**
  - Ejecución y análisis de un programa simple "Hello World" en paralelo.
  - Estimación del valor de Pi mediante series matemáticas en versiones tanto secuenciales como paralelas.
