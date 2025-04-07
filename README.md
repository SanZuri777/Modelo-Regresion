# Modelo Regresión
  Este trabajo es una regresión lineal en la cual hice un modelo de machine learning para predecir el nivel de ansiedad de las personas (basándome en un dataset), donde pude aprender diferentes temas.
  Un modelo de regresión es una técnica de análisis de datos que predice el valor de datos desconocidos mediante el uso de otro valor de datos relacionado y conocido

## ¿Qué modelo utilice?

  Random Forest Regression, es un algoritmo de aprendizaje automático que utiliza varios árboles de decisión para realizar predicciones. Es un método robusto para la clasificación y regresión

## ¿Por qué este modelo?

* Mejora la precisión y reduce la varianza en las predicciones.
* Controla el sobreajuste.
* No se ve afectado por variables correlacionadas.
* Es útil cuando el número de variables es mayor que el número de observaciones.
* Es útil para conjuntos de datos pequeños, donde cada registro puede ser valioso.

## Gráfica
  Para comprender mejor todo el modelo, te presento la gráfica, y te explicaré cada punto.
  ![image](https://github.com/user-attachments/assets/6c654795-2fbe-45cb-826c-057c16886ff1)


## 📉 La gráfica representa:

  Eje X: valores reales (niveles de ansiedad reales).

  Eje Y: predicciones del modelo.

  Línea negra discontinua: la línea de identidad (donde predicción = valor real). Idealmente, los puntos estarían alineados ahí si el modelo fuera perfecto.

  Puntos azules: cada punto representa una predicción del modelo para un caso del set de test.


## ¿Por qué los puntos estan acomodados de esa manera?
  Tal vez al pensar en una regresión lineal piensas en puntos dispersos desde el punto más bajo al más alto y no separados de la misma manera en la que yo los represento en mi gráfico, pero tiene una razón.
  Al tener valores cerrados, nivel de ansiedad del 1 al 10 (trabajados así por el dataset), es por eso por lo que los puntos se ven así, pero si analizamos detenidamente podemos ver que los puntos a pesar de estar un poco separado entre sí mismos, se centran y están       cerca de la línea de referencia.
  Si el modelo fuera perfecto, todos los puntos estarían centrados en la línea de referencia.


## 📊 Métricas del modelo

  Train MSE: 0.9935

  Test MSE: 1.1545

  Train R²: 0.7750

  Test R²: 0.7622
  

## ✅ ¿Qué significan?

  El MSE (Error cuadrático medio) mide cuánto se alejan en promedio las predicciones del valor real. Cuanto más bajo, mejor.

  El R² (Coeficiente de determinación) indica cuánta varianza del valor objetivo se explica por el modelo. Va de 0 a 1, donde 1 es ajuste perfecto.


## 📈 Evaluación general:

  El modelo muestra un rendimiento sólido, con un R² de 0.76 en el conjunto de prueba, lo que indica una buena capacidad para capturar la variabilidad en los niveles de ansiedad. Además, la diferencia entre el error en entrenamiento y prueba es mínima, lo que sugiere     que no hay sobreajuste.


## 🧠 Conclusión

  El modelo logró predecir de forma bastante precisa los niveles de ansiedad, con un buen desempeño general y sin señales de sobreajuste. Aunque tiende a suavizar los valores más extremos, sigue bien la tendencia de los datos. Este ejercicio demuestra cómo el Machine     Learning puede ser una herramienta útil para explorar variables psicológicas complejas a partir de datos cotidianos.













