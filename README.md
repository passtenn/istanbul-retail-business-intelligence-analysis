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

### Dashboard interactivo desarrollado en Tableau para analizar patrones de consumo y ventas.

<div class='tableauPlaceholder' id='viz1773812657986' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DashboarddeanlisisdeventasretailEstambul&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DashboarddeanlisisdeventasretailEstambul&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DashboarddeanlisisdeventasretailEstambul&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='es-ES' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1773812657986');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1877px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
