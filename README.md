# Modulo2_Analisis

Se eligió el modelo random forest de los previamente realizados y por medio de técnicas de ajuste de parámetros se obtuvieron los siguientes resultados:

# Clasificación 

Con el set de datos "car_data" con 1000 registros, y 3 variables de entrada:

## Comparación de modelos

### Precisión
Modelo Original:
Entrenamiento: 0.9975 Validación: 0.87

Modelo 1:
Entrenamiento: 0.94125 Validación: 0.91 Testeo: 0.93

Modelo 2:
Entrenamiento: 0.89375 Validación: 0.89 Testeo: 0.87

Modelo 3:
Entrenamiento: 0.9325 Validación: 0.91 Testeo: 0.89

### Roc-AUC

Modelo Original: 0.86969

Modelo 1: 0.9121

Modelo 2: 0.8909

Modelo 3: 0.9121
### Validación Cruzada

Modelo original: 0.90

Modelo 1: 0.91

# Regresión 

Con el set de datos "insurance" con 1338 registros, y 6 variables de entrada:

### Puntaje R2

Modelo Original
Entrenamiento 0.976406 Validacion 0.80727

Modelo Optimizado
Entrenamiento es 0.8863 Validacion es 0.8659 Testeo 0.911568
### Validación Cruzada
Modelo Original
0.83

Modelo Optimizado
0.85


El documento de Análisis y reporte se generó desde jupyter, pero no sale a menos que se descargue. Por lo tanto puse el generado desde colab como respaldo.


Link al colab:
https://colab.research.google.com/drive/1fhYSK03UQa5azmArl4HoJV3axuYyn_om?usp=sharing
