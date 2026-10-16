# Simulación del Álbum del Mundial - Problema del Coleccionista 

Proyecto realizado para la materia Estadística y Probabilidad (Comisión A). 

El trabajo consistió en simular mediante el método de Monte Carlo la cantidad de paquetes necesarios para completar el álbum del Mundial de fútbol (860 figuritas en paquetes de 5 unidades, sin repetidas adentro del paquete), contrastando los resultados empíricos con la resolución teórica basada en la suma armónica.

> **Nota sobre la autoría:** Este repositorio contiene la entrega grupal de la materia (junto a Camila Delgado, Juan Figueroa, Mariana La Rosa Saubidet y Viviana Reverberi), donde me encargué del desarrollo del código en Python, el diseño de la simulación de Monte Carlo y el análisis comparativo de estrategias.

### ¿Qué incluye el notebook?
- **Simulación base:** Modelo de apertura de paquetes hasta completar el álbum ($N = 500$ repeticiones) y cálculo del promedio estimado vs. valor teórico esperado (~1261 paquetes).
- **Visualización:** Histograma de frecuencias y distribución de la cantidad de paquetes con Seaborn.
- **Comparativa de estrategias:** Basándome en el análisis de Federico Holik, agregué una comparación entre:
  1. Completar el álbum de forma individual.
  2. Estrategia colaborativa (llenado en simultáneo entre 8 amigos compartiendo repetidas).
  3. Estrategia de compra inicial fija (200 paquetes) + canje 1 a 1 de duplicadas.
- **Métricas:** Tabla resumen en Pandas con porcentaje de figuritas repetidas, costos estimados y ahorro económico por persona.

### Tecnologías
- Python 3
- NumPy, SciPy (stats)
- Pandas
- Matplotlib, Seaborn

El notebook se puede abrir y ejecutar directamente desde Google Colab con el botón de arriba.
