Análisis de Rendimiento de Tiendas — Alura Store

Este proyecto surge a partir de un reto propuesto por Alura Latam, enfocado en la obtención de información estratégica para clientes a partir de datos de sus tiendas. He sido contratado para realizar un análisis detallado de las tiendas de Alura Store, con el objetivo de identificar cuál de ellas presenta el menor desempeño y podría ser vendida para invertir en un nuevo negocio.

El jefe del proyecto solicitó evaluar los siguientes aspectos clave:

Facturación total de cada tienda: Determinar cuál tienda genera más ingresos.

Categorías más populares: Identificar las categorías con mayor demanda en cada tienda.

Productos más vendidos: Analizar los productos más populares por tienda.

Promedio de evaluación de clientes: Calcular la satisfacción promedio.

Productos más y menos vendidos: Identificar extremos de rotación.

Costo promedio de envío: Evaluar el gasto logístico por tienda.

Análisis de resultados: Interpretar los hallazgos y emitir conclusiones.

Para llevar a cabo este análisis, se utilizó el entorno de desarrollo Google Colab, empleando el lenguaje de programación Python (versión 3.11.13). Las principales librerías utilizadas fueron:

pandas: Para la manipulación y análisis de datos.

matplotlib: Para la visualización de resultados.

Para instalar las dependencias necesarias, se puede ejecutar el siguiente comando en el entorno:

bash
pip install pandas matplotlib
El cliente, el Sr. Juan, posee cuatro tiendas y desea vender una para reinvertir en un nuevo negocio. Para tomar esta decisión, se realizó un análisis exhaustivo de ventas, rendimiento y comportamiento del cliente.

Los datos fueron extraídos desde archivos CSV alojados en el siguiente repositorio de GitHub: https://github.com/alura-es-cursos/challenge1-data-science-latam

El análisis se centró en las siguientes métricas clave para cada tienda:

Total de ingresos

Principales ventas por categoría

Calificación promedio de satisfacción del cliente

Productos más y menos vendidos

Costo promedio de envío

El análisis completo y la conclusión se encuentran documentados en el archivo principal del proyecto: AluraStoreLatam.ipynb.

Conclusión del análisis: Tras el análisis de los datos, se determina que la Tienda 1 es la más sólida y rentable, destacando por sus altos ingresos y desempeño general. Por otro lado, la Tienda 4 presenta el menor nivel de ingresos y el menor promedio de envío. Aunque este último dato podría deberse a distancias cortas de entrega, también refleja una baja actividad comercial.

Por lo tanto, se recomienda mantener la Tienda 1 como activo principal y vender la Tienda 4 para liberar recursos e invertir en nuevas oportunidades de negocio con mayor potencial de crecimiento.

Este proyecto tiene como objetivo extraer información valiosa que permita tomar decisiones estratégicas basadas en datos reales y confiables.
