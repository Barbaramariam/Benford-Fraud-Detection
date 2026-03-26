# Benford-Fraud-Detection
Detección de fraude financiero mediante la Ley de Benford y algoritmos de Machine Learning (KNN y Random Forest).
# Deteccion de Fraude Financiero mediante la Ley de Benford

Este proyecto aplica tecnicas de aprendizaje automatico para identificar posibles fraudes en transacciones financieras, analizando como se distribuyen los primeros digitos de los montos segun la Ley de Benford.

## Descripcion
El objetivo principal es distinguir entre transacciones naturales y fraudulentas. Para ello, se estudio la frecuencia con la que aparecen los digitos del 1 al 9 y se utilizaron esas frecuencias para entrenar modelos de clasificacion.

## Metodologia
- **Analisis Exploratorio:** Visualizacion y comparacion de la distribucion de los primeros digitos en datos reales vs. datos sospechosos.
- **Modelado:** Entrenamiento y comparacion de dos algoritmos de Machine Learning:
  - K-Nearest Neighbors (KNN)
  - Random Forest
- **Evaluacion:** Uso de matrices de confusion para medir que tan bien el modelo identifica el fraude y cuantos errores comete.

## Conclusiones del Proyecto
Tras las pruebas realizadas, se determino que el modelo **KNN** es el mas adecuado para este sistema. Su principal ventaja es la precision para identificar patrones de fraude, manteniendo un control eficiente sobre las falsas alarmas, lo que minimiza el riesgo financiero.

## Tecnologias Utilizadas
- Python
- Scikit-learn (Machine Learning)
- Pandas y NumPy (Gestion de datos)
- Matplotlib y Seaborn (Graficos)

## Contenido del Repositorio
- `Fernandez Barbara Parcial.ipynb`: Codigo fuente y reporte de resultados.
- `benford_training_data.csv`: Datos utilizados para el entrenamiento.
- `benford_test_data.csv`: Datos de prueba para validar el modelo.
