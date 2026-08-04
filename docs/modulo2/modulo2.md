# Módulo II: Fundamentos de Alto Desempeño

Los cálculos de física moderna suelen pasar la mayor parte de su tiempo de ejecución dentro de un pequeño número de núcleos (kernels) críticos para el desempeño. Este módulo se centra en extraer el máximo desempeño de las CPUs antes de considerar hardware especializado.

## Temas

### Perfilado y Análisis de Desempeño

* Complejidad computacional
* Herramientas de perfilado (profiling)
* Identificación de cuellos de botella
* Limitaciones de memoria frente a CPU

### Cómputo Vectorizado

* Aspectos internos de NumPy
* Difusión (broadcasting)
* Diseño de memoria (layout)
* Operaciones eficientes con arreglos

### Compilación Justo a Tiempo (JIT)

* Numba
* Especialización de tipos
* Aceleración de bucles
* Núcleos (kernels) numéricos

### Paralelismo de Memoria Compartida

* Multiprocesamiento
* Grupos de procesos (process pools)
* Escaneos de parámetros en paralelo
* Cargas de trabajo "vergonzosamente" paralelas

### Fundamentos de Cómputo Distribuido

* Conceptos de MPI
* Paso de mensajes
* Descomposición de dominios
* Introducción a mpi4py

### Datos Escalables y E/S

* E/S de alto desempeño con HDF5 (h5py)
* Persistencia y serialización de datos
* Puntos de control (checkpointing) en simulaciones de larga duración

### GPUs

* Cómputo en GPU con CuPy/JAX 

---

## Referencias Recomendadas
1. Micha Gorelick & Ian Ozsvald, *High Performance Python*, 2da Edición, ISBN-13: 978-1492055020.
2. Michael T. Heath, *Scientific Computing*, ISBN-13: 978-1611975574.
3. Marc Snir et al., *MPI: The Complete Reference*, ISBN-13: 978-0262692151
4. [Documentación de NumPy](https://numpy.org/doc/?utm_source=chatgpt.com)
5. [Documentación de Numba](https://numba.readthedocs.io?utm_source=chatgpt.com)
6. [Documentación de mpi4py](https://mpi4py.readthedocs.io?utm_source=chatgpt.com)
7. [Documentación de h5py](https://docs.h5py.org?utm_source=chatgpt.com)
