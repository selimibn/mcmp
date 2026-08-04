# Estudio de Caso: Dark Matter Freeze-Out

Para proporcionar una narrativa cohesiva, las tareas del semestre se estructuran en torno a un único proyecto creciente: la construcción de una herramienta de simulación e inferencia de Materia Oscura.

### Módulo I: La Librería Boltzmann
**Objetivo:** Construir un paquete modular de Python que resuelva la ecuación de Lee-Weinberg para una WIMP (Partícula Masiva de Interacción Débil).
*   **Enfoque:** Interfaces limpias para EDO (ecuaciones diferenciales ordinarias), pruebas unitarias para la densidad de equilibrio y documentación utilizando la mentalidad de un Ingeniero de Software para la Investigación.

### Módulo II: El Escáner de Parámetros
**Objetivo:** Extraer el máximo desempeño para permitir escaneos a gran escala.
*   **Enfoque:** Usar **Numba** para acelerar las integrales de la sección eficaz promediada térmicamente. Implementar **MPI** y **HDF5** para escanear un espacio de parámetros 5D (masa, acoplamientos) en un clúster y almacenar los resultados de manera eficiente.

### Módulo III: La Restricción de Planck
**Objetivo:** Conectar el modelo con la realidad utilizando datos cosmológicos.
*   **Enfoque:** Construir una función de Verosimilitud (Likelihood) comparando la salida del solucionador con la $\Omega h^2$ de Planck. Usar **emcee** para encontrar las regiones permitidas del espacio de parámetros WIMP. Realizar una optimización por **MLE** como punto de partida.

### Módulo IV: El Dark Emulator
**Objetivo:** Superar el cuello de botella computacional de los solucionadores de EDO.
*   **Enfoque:** Entrenar una **Red Neuronal** o un modelo sustituto de **Procesos Gaussianos** para predecir la densidad reliquia instantáneamente a partir de las entradas del modelo. Usar **Aprendizaje Activo** para muestrear inteligentemente el espacio de parámetros donde el solucionador es más necesario.

## Referencias

1. Lee & Weinberg (1977), *Cosmological Lower Bound on Heavy-Neutrino Masses* , DOI: 10.1103/PhysRevLett.39.165
2. Kolb & Turner, *The Early Universe*, ISBN-13: 978-0201626742.
3. Bertone (Editor), *Particle Dark Matter*, ISBN-13: 978-0521763684.
4. Belanger et al., *micrOMEGAs*, DOI: 10.1016/j.cpc.2018.01.024.
