## Istanbul Retail – Business Intelligence Analysis
### Descripción del proyecto

Este proyecto explora un dataset de transacciones de compras realizadas en distintos centros comerciales de Estambul entre 2021 y 2023.

El objetivo es aplicar conceptos de Business Intelligence (BI) y análisis de datos para identificar patrones de consumo, comportamiento de clientes y tendencias de ventas que puedan aportar valor para la toma de decisiones de negocio.

Este análisis fue desarrollado como parte de mi proceso de aprendizaje dentro de la certificación IBM Business Intelligence Analyst.

### Objetivos del análisis

A través del análisis exploratorio de datos se buscaron responder preguntas de negocio como:

  - ¿Qué categorías de productos generan más ingresos?

  - ¿Cuál es el perfil de los compradores según género y edad?

  - ¿Existen diferencias en el comportamiento de compra entre centros comerciales?

  - ¿Qué métodos de pago son los más utilizados?

  - ¿Existen patrones o tendencias temporales en las ventas?

### Dataset

El dataset contiene información de transacciones realizadas en 10 centros comerciales de Estambul.

#### Variables principales

  - invoice_no → identificador de transacción

  - customer_id → identificador de cliente

  - gender → género del cliente

  - age → edad del cliente

  - category → categoría del producto

  - quantity → cantidad de productos comprados

  - price → valor total de la transacción

  - payment_method → método de pago

  - invoice_date → fecha de la compra

  - shopping_mall → centro comercial donde se realizó la compra

### Proceso de análisis

El análisis se desarrolló siguiendo un flujo típico de análisis de datos:

#### Comprensión de los datos

  - Exploración inicial del dataset

  - Identificación de tipos de datos

  - Revisión de estructura y variables

#### Limpieza de datos

  - Conversión del campo invoice_date a formato fecha

  - Verificación de valores nulos

  - Validación de registros duplicados

#### Análisis exploratorio de datos (EDA)

  - Se analizaron distintas dimensiones del negocio:

  - Ventas por categoría de producto

  - Ventas por género

  - Ventas por rango de edad

  - Métodos de pago más utilizados

  - Ventas por periodo de tiempo

  - Ventas por centro comercial

### Principales insights

Algunos hallazgos relevantes del análisis:

  - Clothing es la categoría con mayor volumen de ventas, representando cerca del 45% del total.

  - Los clientes femeninos generan aproximadamente 60% de las ventas.

  - El grupo de edad con mayor participación en compras es 35-44 años, aunque el consumo está relativamente distribuido entre 25-54 años.

  - El efectivo es el método de pago más utilizado, seguido por tarjeta de crédito.

  - Los centros comerciales Mall of Istanbul y Kanyon concentran cerca del 40% de las ventas totales.

  - El comportamiento de compra por categoría es similar entre los distintos centros comerciales.

### Herramientas utilizadas

  - Python

  - Pandas

  - Matplotlib

  - Jupyter Notebook
