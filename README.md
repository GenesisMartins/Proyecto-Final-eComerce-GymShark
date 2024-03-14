# Proyecto-Final-eComerce-GymShark

### Descripción:
El proyecto consiste en realizar un análisis exhaustivo de datos sobre la marca Gymshark, una reconocida empresa de ropa deportiva. 
Gymshark es una marca de ropa deportiva fundada en 2012 en el Reino Unido por Ben Francis y un grupo de amigos en su casa de Birmingham. Lo que comenzó como una pequeña empresa de impresión de camisetas se ha convertido en una marca global líder en el mercado de la moda deportiva, conocida por su enfoque en la comunidad fitness y su uso eficaz de las redes sociales para el marketing, por lo cual me ha parecido una idea estupenda el analizar como en tan poco tiempo han logrado posicionarse de tal manera.

- Paso #1: WebScraping de https://eu.gymshark.com/  
- Paso #2: - Utilizando datos FAKE creados con la libreria de Pandas FAKER para obtener un reporte de ventas los ultimos tres años.
         - Crar un listado FAKE de clientes
El objetivo es obtener insights valiosos que puedan utilizarse para mejorar la estrategia de negocio, comprender el comportamiento del cliente y optimizar las operaciones.
- Paso #3: EDA
- Paso #4: RFM (técnica utilizada para evaluar el valor de los clientes).
- Paso #5: Testeo de hipotesis.
- Paso #6: Presentación BI.

### Objetivos:

Analizar las tendencias de ventas a lo largo del tiempo para identificar patrones estacionales y oportunidades de crecimiento.
Segmentar a los clientes según su frecuencia de compra, valor de compra y ubicación geográfica para personalizar las estrategias de marketing y retención.
Evaluar la rentabilidad de los productos y categorías para optimizar el inventario y maximizar los márgenes de beneficio.

### Herramientas Utilizadas:

- Python con pandas para el procesamiento y análisis inicial de los datos.
- Faker : Libreria Faker
- fecha y hora : (Biblioteca estándar de Python)
- selenio : Instalar conpip install selenium
- BeautifulSoup: Libreria bs
- Power BI para la visualización de datos y creación de paneles interactivos.

### Configuración:

#### Requisitos previos:

- Python 3.x instalado
- git instalado
- PowerBi

### Limitaciones:
El proyecto se vio limitado no solo por las limitaciones de tiempo del proyecto, completado en un breve período de una semana y media como parte del bootcamp de análisis de datos de IronHack, sino también por ciertas limitaciones dentro de los modelos:

##### - El no contar con un inventario real:  

Me ha traido contratiempos al momento de diseñar los reportes de ventas, en un principio la falta de datos, la linealidad de cantidades, la lentitud de la libreria para generar un inventario similar al real, al momento de graficar resultados seguía notanto errores en fechas, inventario, precios, dias y total de ventas, por lo cual he ido ajustando en multiples oportunidades, hasta decidir bajar de 8.500.000 de registros a menos de 500K, era la unica forma de tener los datos de una forma mas rapida y efectiva.

### Entregables:

- Cuadernos de JN paso a paso ETL-EDA-Testeo Hipotesis.
- Paneles interactivos de Power BI que presenten de manera clara y concisa los insights obtenidos.

### Trabajo futuro:

Para Abordar las limitaciones y mejorar los entregables de Gymshark se plantea: 

- Mejorar las descripciones de columnas que involucran los inventarios a lo largo del tiempo, de esta forma ofrecer de una forma mas realista oportunidades en la toma de decisiones estratégicas basadas en datos.
- GymShark llecva 5 años en el mercado, por lo cual estaría bien evaluarlo desde sus inicios y en base a ello hacer una proyección para proximos años a diferentes niveles.
- Incluir un estudio de Analisis de Sentimiento el redes sociales, GymShark se ha caraterizado por hacerse top a nivel global a traves del uso de éstas, por lo cual estaría bien el analizar estos datos y mejorar su eficiencia en la estrategia de marketing para el fortalecimiento de la relación con los clientes a través de estrategias más personalizadas y orientadas de forma agrupada.

  
### Expresiones de gratitud

Este proyecto reconoce por sus contribuciones:

Estracción de información:
- GymShark: https://eu.gymshark.com/

Herramientas de diseño de Dashboard: 
- @PowerBiDesign Youtube
  



