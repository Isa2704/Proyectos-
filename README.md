# Proyectos
## 1. Análisis de Series Temporales: Pernoctaciones en España (1999-2020)
Archivo: ANALISIS DE UNA SERIE TEMPORAL MARÍA ISABEL SERRANO DELGADO.pdf

Estudio exhaustivo de la evolución del sector turístico en España basado en datos oficiales del INE. El objetivo principal fue desarrollar un modelo predictivo robusto capaz de capturar la tendencia y estacionalidad del sector.

Metodología: Se analizó una serie mensual de 253 observaciones, aplicando transformaciones logarítmicas para corregir la heterocedasticidad y diferenciaciones para alcanzar la estacionariedad.

Modelización: Tras un proceso de identificación mediante FAC y FACP, se seleccionó y validó un modelo SARIMA (1,0,1)(2,1,0) sin constante.

Resultados: El modelo superó con éxito las fases de validación (test de Ljung-Box, normalidad de residuos y sobreajuste), permitiendo realizar una predicción fiable a 5 años vista.

## 2. Proyectos de Etología y Bioestadística con R
### A. Asociación de Orientación y Estímulos Químicos (ProyectoEtologia2.docx)
Objetivo: Evaluar si existe una asociación entre el lugar de establecimiento de la araña (Puerta/Ventana) y el tipo de estímulo químico recibido (Olor de hormiga vs. Permetrina).

Técnicas: Uso de tablas de contingencia y el Test de Chi-cuadrado de independencia para variables cualitativas.

Conclusión: El análisis determinó que no existen evidencias estadísticas suficientes para confirmar una asociación preferencial basada exclusivamente en el estímulo olfativo (p−valor>0.05).

### B. Análisis Comparativo de Tiempos de Permanencia (ProyectoEtologia1.docx)
Objetivo: Determinar si la proporción de tiempo que la araña pasa en la zona experimental varía significativamente entre el tratamiento con feromonas (hormiga) y el insecticida (permetrina).

Técnicas: Tras verificar la no normalidad de los datos mediante el test de Shapiro-Wilk, se optó por un enfoque no paramétrico utilizando el Test de Mann-Whitney (Wilcoxon).

Conclusión: No se hallaron diferencias significativas en el tiempo de permanencia, sugiriendo que ambos estímulos generan una respuesta conductual similar en la especie.

### C. Patrones de Primer Movimiento y Orientación (ProyectoEtologia.docx)
Objetivo: Estudiar la dirección del primer movimiento de los ejemplares para identificar comportamientos de atracción o evitación ante el rastro de hormiga.

Técnicas: Aplicación de pruebas de asociación para datos apareados y análisis de frecuencias.

Conclusión: Los resultados estadísticos indicaron que el primer movimiento no está condicionado de forma determinante por el estímulo en las condiciones dadas (p−valor=0.3938).

Habilidades técnicas aplicadas: 
  Lenguajes: R (readxl, stats, graphics).
  Estadística: Modelos SARIMA, Tests de Normalidad, Pruebas no paramétricas, Chi-cuadrado.
  Herramientas: SPSS (visualización), RStudio, Excel.

## 3. Análisis y Reglas de Asociación de Accidentes de Tráfico en Chicago
Descripción: Proyecto de minería de datos aplicado a un dataset real de siniestralidad vial en Chicago. El trabajo abarca desde la limpieza de valores nulos y Análisis Exploratorio de Datos (EDA) hasta la aplicación de modelos de aprendizaje no supervisado. Se utiliza el algoritmo Apriori para descubrir reglas de asociación que expliquen bajo qué circunstancias específicas se agrava la siniestralidad.

Herramientas: Python (Pandas, Matplotlib, Seaborn) y Machine Learning (mlxtend para Algoritmo Apriori).

Resultados clave: Identificación de patrones espaciotemporales (horas y días de mayor riesgo) y extracción de insights sobre cómo interactúan variables como las condiciones climáticas, la iluminación y los defectos de la vía en la gravedad de los accidentes.

## 4. Predicción de Victorias en CS:GO mediante Machine Learning
Descripción: Desarrollo de un proyecto predictivo de clasificación supervisada basado en métricas de partidas del videojuego CS:GO. El objetivo es predecir qué bando (Terrorista o Antiterrorista) ganará la ronda en función de variables como el valor del equipamiento, salud y blindaje. Se evalúan y comparan múltiples algoritmos para encontrar el mejor ajuste.

Herramientas: R, R Markdown y librerías predictivas (caret, randomForest, e1071, class).

Resultados clave: Entrenamiento y comparativa exhaustiva de diversos modelos (Regresión Logística, LDA, QDA, Naive Bayes, KNN, Árboles de Decisión y Random Forest), analizando matrices de confusión y precisión predictiva para determinar el algoritmo óptimo en entornos de eSports.

## 5. Predicción de Riesgo de Ictus Clínico (Modelos LDA y QDA)
Descripción: Aplicación estadística multivariante orientada al sector salud (Healthcare Data). El proyecto consiste en predecir la probabilidad de que un paciente sufra un accidente cerebrovascular (ictus) basándose en factores de riesgo biométricos e historiales clínicos (edad, hipertensión, niveles de glucosa, IMC y tabaquismo).

Herramientas: R, R Markdown y modelado estadístico avanzado (paquete MASS).

Resultados clave: Implementación, entrenamiento y validación de modelos de Análisis Discriminante Lineal (LDA) y Análisis Discriminante Cuadrático (QDA). Se evalúa el rendimiento clasificatorio de ambos modelos para identificar correctamente a los pacientes de riesgo frente a los sanos, trabajando con asimetrías en los datos.

