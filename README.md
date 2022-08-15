# Ciencia de datos - Competencia de Kaggle - Predicción de precios de casas

## Descripción de la competencia

Pregúntale a un comprador acerca de la casa de sus sueños y ellos probablemente no empezarán hablando acerca de la altura del techo del sótano o de la accesibilidad al transporte. No obstante, este conjunto de datos prueba que hay muchas más variables que afectan las negociaciones del precio que solamente el número de cuartos o si tiene una cerca blanca.

Con 79 variables explicatorias que describen (casi) cada aspecto de las casas resienciales en Ames, Iowa, el propósito de esta competencia es predecir el precio final de cada casa.

### Objetivo
Nuestro objetivo es predecir el precio de ventas de cada casa. Para cada Id en el conjunto de prueba, debemos predecir el valor de la variable `SalePrice`.

> A día de hoy, el puesto 1000 tiene una puntuación de 0.13028, así que nuestro objetivo será superarlo.

### Métrica
Las entregas serán evaluadas usando el RMSE (Root-Mean-Squared-Error) entre el logaritmo del valor predicho y el logaritmo de los precios de venta observados. (Tomar los logaritmos significa que los errores en predecir casas costosas y baratas afectará el resultado de manera equitativa.)

### Formato de entrega
Cada archivo debe contener una cabecera y debe tener el siguiente formato:

`
Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
etc.
`

## Solución
La solución se encuentra en este repositorio en formato csv. Se deja un notebook con la explicación detallada de lo que se hizo.
