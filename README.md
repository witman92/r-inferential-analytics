# Inferencia estadística y modelos de regresión en R

Análisis inferencial sobre dos conjuntos de datos: una encuesta (400 observaciones, 18 variables) y mediciones biológicas de **pez espada del Pacífico Sur** (edad, longitud, peso y sexo).

## Qué incluye
- **Correlación múltiple** entre variables cuantitativas.
- **Diferencia de medias** del ingreso según estrato (95 % de confianza): ANOVA y comparaciones post-hoc de Tukey.
- **Test de proporciones** por tipo de establecimiento.
- **Regresión lineal múltiple** con selección hacia atrás por AIC (`stepAIC`) y **diagnóstico de residuos**: normalidad (Shapiro-Wilk), homocedasticidad (Breusch-Pagan), independencia (Durbin-Watson), outliers y puntos influyentes.
- **Modelos de crecimiento**: linealización de la función de **von Bertalanffy** (edad/longitud) y del modelo alométrico longitud/peso `w = a·x^b`, ajustados por sexo con diagnóstico de residuos.

## Estructura
```
inferential_regression_analysis.Rmd   # Análisis completo en R Markdown
Estudiantes.xlsx              # Encuesta
pez espada pasifico.xlsx      # Datos biológicos de pez espada
```

**Stack:** R · R Markdown · readxl · dplyr · tidyr · ggplot2 · corrplot · GGally · MASS · car · lmtest
