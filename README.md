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
