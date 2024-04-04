# Regresión Lineal
Es un método utilizado para modelar la relación entre una o más variables independientes (predictoras) y una variable dependiente (respuesta) continua. La relación entre las variables se modela como una función lineal.

# Regresión Lineal Simple
<p align="center">
<img src="Images/regresionlienalsimple.png"  height=500>
</p>




# Regresión Lineal Múltiple

<p align="center">
<img src="Images/regresionlienalmultiple.png"  height=80>
</p>

Existen más tipos de regresiones lienales, como la ponderada, ridge, lasso, mínimos cuadrados parciales, elasticnet y la logística
<br>

<h2> Es importante tener en cuenta que para hacer regresión de manera rigurosa hay que hacer una validación de los datos <h2>

# Validacion de los Datos

Limpieza de datos: Elimina los valores atípicos, los datos faltantes y las observaciones duplicadas. La presencia de datos erróneos puede afectar negativamente la calidad del modelo.

Normalidad: Verifica la distribución de las variables para asegurarte de que se ajusten a una distribución normal. La regresión lineal múltiple asume que las variables independientes y dependiente siguen una distribución normal.

Linealidad: Asegúrate de que exista una relación lineal entre las variables independientes y la variable dependiente. Puedes usar gráficos de dispersión para visualizar esta relación.

Multicolinealidad: Comprueba si existe multicolinealidad entre las variables independientes. La multicolinealidad puede afectar la precisión de los coeficientes de regresión. Puedes utilizar técnicas como el factor de inflación de la varianza (VIF) para identificar la multicolinealidad.

Homocedasticidad: Verifica si la varianza de los residuos es constante en todos los niveles de las variables independientes. Los gráficos de residuos pueden ayudarte a identificar la homocedasticidad.

Independencia de los residuos: Asegúrate de que los residuos de la regresión no muestren patrones sistemáticos, como autocorrelación. Los gráficos de autocorrelación de residuos pueden ser útiles para detectar este problema.

Validación cruzada: Divide tus datos en conjuntos de entrenamiento y prueba para evaluar el rendimiento del modelo en datos no vistos. La validación cruzada ayuda a evitar el sobreajuste y proporciona una estimación más realista del rendimiento del modelo.
