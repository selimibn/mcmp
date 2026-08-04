

# Métodos Computacionales Modernos para la Física

## Descripción del Curso

Este curso introduce técnicas computacionales modernas utilizadas en
la investigación contemporánea de la física. Partiendo de la
experiencia previa en métodos numéricos y modelado computacional, los
estudiantes aprenderán los principios de la ingeniería de software
para la investigación, optimización de desempeño, inferencia
bayesiana, modelado estadístico y aprendizaje automático aplicado a la
ciencia. Se enfatiza la reproducibilidad, el mantenimiento y los
flujos de trabajo computacionales que son transferibles entre
distintas subáreas de la física. El curso culmina con un proyecto de
investigación abierto donde los estudiantes aplicarán estas
herramientas a un sistema físico de su elección.

---

## Objetivos de Aprendizaje

Al finalizar el curso, los estudiantes serán capaces de:

1. Desarrollar software científico reproducible y fácil de mantener.
2. Aplicar técnicas de perfilado (profiling) y optimización a
   problemas de física computacional.
3. Implementar algoritmos paralelos en arquitecturas multinúcleo.
4. Realizar estimación de parámetros bayesianos y cuantificación de incertidumbre.
5. Construir y diagnosticar simulaciones de Monte Carlo por Cadenas de Markov (MCMC).
6. Construir modelos sustitutos (surrogates) para simulaciones computacionalmente costosas.
7. Aplicar métodos de aprendizaje automático a conjuntos de datos científicos.
8. Diseñar y ejecutar un proyecto de investigación computacional utilizando prácticas modernas de software.

---

## Módulo I: Ingeniería de Software para la Investigación

Este módulo introduce la mentalidad y las herramientas necesarias para construir software científico robusto.

### Temas

1. Diseño de Software Científico
2. Control de Versiones con Git
3. Pruebas de Software Científico
4. Empaquetado y Entornos

---

## Módulo II: Fundamentos de Alto Desempeño

Los cálculos de física moderna suelen pasar la mayor parte de su tiempo de ejecución dentro de un pequeño número de núcleos (kernels) críticos para el desempeño. Este módulo se centra en extraer el máximo desempeño de las CPUs antes de considerar hardware especializado.

### Temas

1. Perfilado y Análisis de Desempeño
2.  Cómputo Vectorizado
3. Compilación Justo a Tiempo (JIT)
4. Paralelismo de Memoria Compartida
5. Fundamentos de Cómputo Distribuido
6. Datos Escalables y E/S
7. GPUs

---

## Módulo III: Inferencia Bayesiana y Cuantificación de Incertidumbre

La física depende cada vez más de la inferencia estadística para
conectar los modelos con las observaciones. Este módulo introduce
enfoques bayesianos modernos para la estimación de parámetros y la
cuantificación de incertidumbre.

### Temas

1. Fundamentos Bayesianos
2. Optimización Determinista
3. Diferenciación Automática
4. Monte Carlo por Cadenas de Markov (MCMC)
5. Diagnóstico de MCMC
6.  Programación Probabilística
7. Modelos Sustitutos de Procesos Gaussianos


---

## Módulo IV: Aprendizaje Automático para el Modelado Científico

El aprendizaje automático (machine learning) se ha convertido en una herramienta importante para acelerar simulaciones, identificar patrones en grandes conjuntos de datos y construir modelos sustitutos. El énfasis aquí es la utilidad científica en lugar de los sistemas de IA a gran escala.

### Temas

1. Aprendizaje Supervisado
2. Clasificación en Física
3. Reducción de Dimensionalidad
4. Modelos Sustitutos de Redes Neuronales
5. Aprendizaje Activo y Optimización
6. Aprendizaje Automático Científico (SciML)

---

## Módulo V: Proyecto Final
	
Los estudiantes desarrollan un proyecto computacional original aplicando las técnicas aprendidas durante el semestre.

Los proyectos pueden incluir:

* Estimación de parámetros bayesianos en física de partículas
* Inferencia estadística para modelos cosmológicos
* Modelos sustitutos para simulaciones costosas
* Sistemas dinámicos y cuantificación de incertidumbre
* Problemas de clasificación en física experimental
* Métodos computacionales en materia condensada, óptica, física de plasmas o biofísica

---

# Propuesta de Evaluación

| Componente                                    | Peso   |
| --------------------------------------------- | -----: |
| Tareas de Ingeniería de Software              |    20% |
| Tareas de Cómputo de Alto Desempeño (HPC)     |    20% |
| Proyecto de Inferencia Bayesiana              |    20% |
| Mini-proyecto de Aprendizaje Automático       |    10% |
| Proyecto Final de Investigación               |    30% |

---


## Referencias Generales

1. Wilson et al., *Best Practices for Scientific Computing*
2. Gorelick & Ozsvald, *High Performance Python*
3. Sivia & Skilling, *Data Analysis: A Bayesian Tutorial*
4. Foreman-Mackey et al., *emcee: The MCMC Hammer*
5. Acquaviva, Machine *Learning for Physics and Astronomy*
