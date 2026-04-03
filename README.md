# DataMiningIA_-Julian-Alvarez-
DataMiningIA_[Julian Alvarez]
1. Objetivo y Pregunta Central
Pregunta de investigación: ¿En qué medida las horas de estudio semanales y el entorno socioeducativo (apoyo en el hogar y asistencia) predicen la calificación final de un estudiante?
Objetivo: Identificar los patrones clave que permiten predecir el éxito académico y proporcionar recomendaciones basadas en datos.
2. Fuente de los Datos y Proceso de Limpieza
El dataset consiste en 500 registros generados sintéticamente para simular el comportamiento académico de un grupo de estudiantes universitarios.
Proceso de Limpieza (Asistido por IA):
Normalización: Se estandarizaron las categorías de "Nivel Educativo de los Padres" a una escala numérica (1-3).
Tratamiento de nulos: Se verificó la ausencia de valores faltantes en las columnas críticas.
Validación de rangos: Se aseguraron límites lógicos (Horas de estudio entre 0-50 y Notas entre 0-100).
3. Técnicas de Minería de Datos Aplicadas
Se utilizó la técnica de Regresión Lineal Múltiple mediante el complemento "Análisis de Datos" de Excel.
Variable Dependiente (Y): Nota Final.
Variables Independientes (X): Horas de Estudio, Nivel Educativo Padres, Inasistencias y Acceso a Internet.
4. Resultados Obtenidos e Insights
Correlación Positiva: Las horas de estudio son el predictor más fuerte; cada hora adicional de estudio incrementa la nota en aproximadamente 1.2 puntos.
Impacto Negativo: Las inasistencias tienen un peso negativo crítico; superar las 10 faltas reduce la probabilidad de aprobación en un 40%.
R-Cuadrado: El modelo explica el 72% de la variabilidad de las notas finales, lo que indica una alta confiabilidad.
5. Limitaciones y Recomendaciones
Limitaciones: El dataset no incluye factores emocionales o de salud mental que podrían influir en el rendimiento.
Recomendaciones: Implementar programas de alerta temprana para estudiantes que superen las 5 inasistencias y fomentar grupos de estudio dirigidos para optimizar las horas de trabajo autónomo.
