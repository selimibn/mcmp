# Módulo III: Inferencia Bayesiana y Cuantificación de Incertidumbre

La física depende cada vez más de la inferencia estadística para
conectar los modelos con las observaciones. Este módulo introduce
enfoques bayesianos modernos para la estimación de parámetros y la
cuantificación de incertidumbre.

## Temas

### Fundamentos Bayesianos

* La probabilidad como inferencia
* Teorema de Bayes
* Distribuciones previas (priors) y verosimilitudes (likelihoods)
* Distribuciones posteriores

### Optimización Determinista

* Estimación de Máxima Verosimilitud (MLE)
* Búsqueda de la moda de la distribución posterior
* Optimizadores robustos (SciPy, iminuit)

### Diferenciación Automática

* Fundamentos de AD
* Aceleración de gradientes con JAX
* Aplicación a conceptos de Monte Carlo Hamiltoniano (HMC)

### Monte Carlo por Cadenas de Markov (MCMC)

* Metropolis-Hastings
* Muestreadores de conjunto (ensemble samplers)
* Métodos invariantes por afinidad
* Implementación práctica con emcee

### Diagnóstico de MCMC

* Periodo de calentamiento (burn-in)
* Autocorrelación
* Tamaño de muestra efectivo
* Diagnósticos de convergencia

### Programación Probabilística

* Introducción a PyMC
* Modelos jerárquicos
* Verificaciones predictivas posteriores

### Modelos Sustitutos de Procesos Gaussianos

* Métodos de kernel
* Regresión
* Emuladores para simulaciones costosas
* Aplicaciones en física

---


## Referencias

1. Andrew Gelman, John Carlin, Hal Stern, David Dunson, Aki Vehtari, Donald Rubin, *Bayesian Data Analysis*, 3ra Edición, ISBN-13: 978-1439840955.
2. Devinder Sivia & John Skilling, *Data Analysis: A Bayesian Tutorial*, 2da Edición, ISBN-13: 978-0198568322.
3. David J. C. MacKay, *Information Theory, Inference and Learning Algorithms*, ISBN-13: 978-0521642989.
4. Foreman-Mackey, Hogg, Lang & Goodman (2013), *emcee: The MCMC Hammer*, DOI: 10.1086/670067, arXiv: 1202.3665.
5. Osvaldo Martin, Ravin Kumar, Junpeng Lao, *Bayesian Modeling and Computation in Python* ISBN-13: 978-1032019772
6. Carl Edward Rasmussen & Christopher K. I. Williams, *Gaussian Processes for Machine Learning*, ISBN-13: 978-0262182539

