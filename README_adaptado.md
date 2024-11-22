
# Trabajo de Aplicación No. 3 - Programación 2024-2

Este repositorio contiene la solución al Trabajo de Aplicación No. 3, en el cual se desarrollaron dos modelos de aprendizaje supervisado usando la base de datos "Air Quality UCI". El proyecto incluye la implementación, evaluación y comparación de dos modelos con el objetivo de analizar su desempeño en un problema de predicción.

## Objetivos
1. Implementar dos modelos de aprendizaje supervisado:
   - **Regresión Lasso**: Modelo lineal con regularización L1, adecuado para conjuntos de datos con muchas características irrelevantes.
   - **Random Forest**: Modelo no lineal basado en múltiples árboles de decisión, ideal para capturar relaciones complejas.
2. Optimizar los hiperparámetros de los modelos utilizando **GridSearchCV**.
3. Evaluar los modelos mediante curvas de aprendizaje y métricas de error.
4. Comparar los modelos y justificar la selección del mejor en función del problema.

## Contenido del repositorio
```
├── README.md                  # Descripción del proyecto
├── regresion 1 proy.ipynb     # Implementación y evaluación de Regresión Lasso
├── regresion 2 proy.ipynb     # Implementación y evaluación de Random Forest
├── comparación.ipynb          # Comparación de los dos modelos
├── AirQualityUCI.csv          # Base de datos utilizada
└── informe.pdf                # Resumen detallado del análisis y conclusiones
```

## Resultados principales
- **Regresión Lasso**:
  - MAE: _[Valor calculado]_
  - RMSE: _[Valor calculado]_
  - R²: _[Valor calculado]_
  - Observación: Modelo balanceado, útil para identificar las características más relevantes.

- **Random Forest**:
  - MAE: _[Valor calculado]_
  - RMSE: _[Valor calculado]_
  - R²: _[Valor calculado]_
  - Observación: Modelo flexible, captura relaciones no lineales, pero podría requerir más recursos computacionales.

## Recomendación
Basándonos en las métricas y análisis, recomendamos el modelo con mejor desempeño para este conjunto de datos. Más detalles están disponibles en el archivo `informe.pdf`.

## Tecnologías utilizadas
- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## Autores
- **[Tu nombre]**