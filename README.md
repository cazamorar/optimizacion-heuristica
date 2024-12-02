# Optimización Numérica y Combinatoria con Visualizaciones

Este repositorio contiene la implementación de un proyecto relacionado con la optimización numérica y combinatoria, acompañados de visualizaciones dinámicas para comprender los resultados. Los proyectos se desarrollaron en Python, utilizando librerías populares de ciencia de datos y visualización.

## Deepnote:
https://deepnote.com/app/alejandra-uribe-sierra-6d3e/Optimizacion-Heuristica-b83586ac-f181-4e61-8d03-82103ac52780?utm_source=app-settings&utm_medium=product-shared-content&utm_campaign=data-app&utm_content=b83586ac-f181-4e61-8d03-82103ac52780

## Contenido del Repositorio

- **`Generación de animaciones.ipynb`:** Código para la generación de visualizaciones dinámicas (GIFs) que representan los procesos de optimización y recorrido en un mapa.
- **`Optimización Heurística.ipynb`:** Implementación de los métodos de optimización numérica y combinatoria, incluyendo algoritmos evolutivos y metaheurísticos como las colonias de hormigas y algoritmos genéticos.
- **`mx.json`:** Archivo GeoJSON con los datos geográficos de México para la representación de rutas en mapas.

---

## Descripción de los Proyectos

### Parte 1: Optimización Numérica

1. **Funciones de prueba seleccionadas:**
   - Función de Rosenbrock
   - Función de Rastrigin
2. **Métodos de optimización aplicados:**
   - **Descenso por Gradiente:** Se implementó un algoritmo con condiciones iniciales aleatorias.
   - **Métodos Heurísticos:** Algoritmos evolutivos, optimización por enjambre de partículas y evolución diferencial.
3. **Visualizaciones:**  
   Se generaron animaciones en 2D y 3D para representar el proceso de optimización, comparando las trayectorias del descenso por gradiente y los métodos heurísticos.
4. **Discusión:**  
   Los resultados se analizan en términos de:
   - Valor final de la función objetivo.
   - Número de evaluaciones de la función objetivo.
   - Comparativa entre métodos deterministas y heurísticos.

### Parte 2: Optimización Combinatoria

1. **Problema planteado:**  
   Un vendedor debe recorrer las capitales de los 32 estados de México, minimizando el costo total de desplazamiento, que incluye:
   - **Valor de la hora del vendedor.**
   - **Costos de peajes.**
   - **Consumo de combustible del vehículo seleccionado.**

2. **Métodos aplicados:**
   - **Colonias de Hormigas:** Simula el comportamiento de colonias reales para encontrar rutas óptimas.
   - **Algoritmos Genéticos:** Emplea mecanismos de selección, cruce y mutación para optimizar el recorrido.
3. **Visualización dinámica:**  
   Se genera un GIF que muestra la evolución de la mejor ruta sobre un mapa de México, destacando las capitales visitadas y las conexiones entre ellas.

---

## Dependencias

Para ejecutar los notebooks, asegúrate de tener instaladas las siguientes bibliotecas de Python:

- `numpy`
- `matplotlib`
- `geopandas`
- `shapely`
- `Pillow`
- `scipy`

Instalación sugerida:
```bash
pip install numpy matplotlib geopandas shapely Pillow scipy
