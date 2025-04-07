# Modelo Regresión

Después de estar investigando, de muchos errores y ayuda de un amigo, pude terminar este trabajo en el cual he aprendido bastante, el uso de un modelo de Machine Learning, utilizando un dataset bajado de kaggle (una página de ayuda para obtener datasets).

## ¿Qué modelo utilice?

Random Forest Regression, es un algoritmo de aprendizaje automático que utiliza varios árboles de decisión para realizar predicciones. Es un método robusto para la clasificación y regresión

## ¿Por qué este modelo?

* Mejora la precisión y reduce la varianza en las predicciones.
* Controla el sobreajuste.
* No se ve afectado por variables correlacionadas.
* Es útil cuando el número de variables es mayor que el número de observaciones.
* Es útil para conjuntos de datos pequeños, donde cada registro puede ser valioso.


## 📊 Métricas del modelo

  Train MSE: 0.9935

  Test MSE: 1.1545

  Train R²: 0.7750

  Test R²: 0.7622
  

## ✅ ¿Qué significan?

El MSE (Error cuadrático medio) mide cuánto se alejan en promedio las predicciones del valor real. Cuanto más bajo, mejor.

El R² (Coeficiente de determinación) indica cuánta varianza del valor objetivo se explica por el modelo. Va de 0 a 1, donde 1 es ajuste perfecto.


📈 Evaluación general:

El modelo no está sobreajustado (train y test similares).

Con un R² > 0.75, estás explicando el ~76% de la variabilidad en los datos de test, lo cual es bastante bueno considerando que estás prediciendo una variable tan subjetiva como el nivel de ansiedad.

El MSE está en un rango razonable considerando que la escala es de 1 a 10.


## 📉 ¿Cómo interpretar y explicar la gráfica?
  
  La gráfica representa:

  Eje X: valores reales (niveles de ansiedad reales).

  Eje Y: predicciones del modelo.

  Línea negra discontinua: la línea de identidad (donde predicción = valor real). Idealmente, los puntos estarían alineados ahí si el modelo fuera perfecto.

  Puntos celestes: cada punto representa una predicción del modelo para un caso del set de test.














