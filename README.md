# Quinto Proyecto del Predictive Analytics for Business Nanodegree Program de Udacity

# A/B Test a New Menu Launch
 Descripción del proyecto
Usted es analista de negocios de Round Roasters, un restaurante de café en los Estados Unidos de América. El equipo ejecutivo realizó una prueba de mercado con un nuevo menú y necesita determinar si el nuevo menú puede generar suficientes ventas para compensar el costo de marketing del nuevo menú. Su trabajo es analizar la prueba A / B y redactar una recomendación sobre si la cadena Round Roasters debería lanzar este nuevo menú.

# ¿Cómo completo este proyecto?
Este proyecto utiliza las habilidades aprendidas a lo largo del curso "Pruebas A / B". Para completar este proyecto:

# Pasar por el curso
Aplicar las habilidades aprendidas en el curso para resolver el problema empresarial indicado en la sección de detalles del proyecto.
Utilice nuestras pautas y rúbrica para ayudar a construir su proyecto.
Cuando esté listo, envíenoslo para que lo revisemos utilizando la plantilla de envío que se encuentra en la sección de materiales de apoyo.
Habilidades requeridas
Para completar este proyecto, debe poder:

Limpiar, formatear y combinar una amplia gama de fuentes de datos
Planificar y analizar pruebas A / B


# Detalles Generales 

El problema empresarial
Round Roasters es una cadena de café de lujo con ubicaciones en el oeste de los Estados Unidos de América. Los últimos años han provocado un estancamiento en el crecimiento de la cadena de café y se creó un nuevo equipo de gestión para reactivar el crecimiento en sus tiendas.

La primera gran iniciativa de crecimiento es introducir sándwiches gourmet en el menú, junto con una oferta limitada de vinos. El nuevo equipo de administración cree que una campaña publicitaria en televisión es crucial para atraer a la gente a las tiendas con estas nuevas ofertas.

Sin embargo, la campaña televisiva requerirá un impulso significativo en el presupuesto de marketing de la empresa, con un retorno de la inversión ( ROI ) desconocido . Además, existe la preocupación de que los clientes actuales no compren las nuevas ofertas del menú.

Para minimizar el riesgo, el equipo directivo decide probar los cambios en dos ciudades con nueva publicidad televisiva. Las ciudades de Denver y Chicago fueron elegidas para participar en esta prueba porque las tiendas en estas dos ciudades (o mercados) funcionan de manera similar a todas las tiendas en toda la cadena de tiendas; el rendimiento en estos dos mercados sería un buen indicador para predecir qué tan bien funciona el menú actualizado.

La prueba se llevó a cabo durante un período de 12 semanas (del 29 de abril de 2016 al 21 de julio de 2016) donde cinco tiendas en cada uno de los mercados de prueba ofrecieron el menú actualizado junto con publicidad televisiva.

El período comparativo es el período de prueba, pero para el año pasado (2015-abril-29 al 2015-julio-21).

Se le ha pedido que analice los resultados del experimento para determinar si los cambios del menú deben aplicarse a todas las tiendas. El impacto previsto en la rentabilidad debería ser suficiente para justificar el aumento del presupuesto de marketing: aumento de al menos un 18% en el crecimiento de las ganancias en comparación con el período comparativo en comparación con las tiendas de control; también conocido como elevación incremental . En los datos, la ganancia se representa en la variable Gross_margin .

Ha podido recopilar tres archivos de datos para usar en su análisis:

Datos de transacciones para todas las tiendas desde el 21 de enero de 2015 hasta el 18 de agosto de 2016
Una lista de todas las tiendas de Round Roasters
Una lista de las 10 tiendas (5 en cada mercado) que se utilizaron como mercados de prueba.
Pasos para el éxito
Paso 1: planifique su análisis
Para realizar el análisis correcto, deberá preparar un conjunto de datos. Antes de arremangarse y preparar los datos, es una buena idea tener un plan de lo que debe hacer para preparar el conjunto de datos correcto. Un buen plan te ayudará con tu análisis. Aquí hay algunas preguntas para comenzar:

¿Cuál es la métrica de rendimiento que utilizará para evaluar los resultados de su prueba?
¿Cuál es el período de prueba?
¿A qué nivel (día, semana, mes, etc.) se deben agregar los datos?
Paso 2: limpia tus datos
En este paso, debe preparar los datos para los pasos 3 y 4. Debe agregar los datos de la transacción al nivel apropiado y filtrar por los rangos de datos apropiados. Puede asumir que no hay datos faltantes, incompletos, duplicados o sucios. Está listo para pasar al siguiente paso cuando tenga datos de transacciones semanales para todas las tiendas.

Paso 3: Emparejar las unidades de tratamiento y control
En este paso, debe crear las variables de tendencia y estacionalidad, y utilizarlas junto con otras variables de control para hacer coincidir dos unidades de control con cada unidad de tratamiento. Los almacenes de tratamiento deben coincidir con los almacenes de control de la misma región. Nota: Calcule la cantidad de transacciones por tienda por semana y use 12 períodos para calcular la tendencia y la estacionalidad.

Aparte de tendencia y estacionalidad ...

¿Qué variables de control deben considerarse? Nota: Considere únicamente las variables del archivo RoundRoastersStore.
¿Cuál es la correlación entre cada variable de control potencial y su métrica de desempeño? (Ejemplo de matriz de correlación a continuación)
¿Qué variables de control utilizará para hacer coincidir las reservas de tratamiento y control?
Paso 4: análisis y redacción
Realice su análisis A / B y cree un informe breve que describa sus resultados y recomendaciones.


En un análisis AB, usamos la matriz de correlación para encontrar la variable más correlacionada con la métrica de rendimiento para incluirla en la herramienta de controles AB para ayudar a encontrar las mejores coincidencias.
