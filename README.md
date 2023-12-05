## **Introduccion** 

Proyecto realizado para responder y dar posibles soluciones de siniestros viales para El `Observatorio de Movilidad y Seguridad Vial` (OMSV), centro de estudios que se encuentra bajo la órbita de la ***Secretaría de Transporte*** del Gobierno de la Ciudad Autónoma de Buenos Aires, nos solicito la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales.


### **El Rol a representar es el de un Data Science**

El analista deberá trabajar con los datos proporcionados por [Datos oficiales](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)
Realizará el correspondiente ETL con su respectivo EDA para, 
Utilizar alguna herramienta visual donde se generara un dashboard que presente las graficas del análisis. Esto facilitará llevar a cabo la presentación y conclusión del trabajo, e incluir las posibles soluciones para disminuir los siniestros viales en las comunas de la Ciudad Autónoma de Buenos Aires.

**Notebooks donde se realizaron las tareas de limpieza extraccion y carga de los datos**

Notebooks[EDA.ipynb]

Notebooks[ETL.ipynb]

**Con la herramienta grafica Power BI se genera un** [Dashboard]PI_02_Siniestros_Viales_CABA

Donde se realizan las metricas e items propuestos con sus respectivas graficas para la presentacion en un panel interactivo.
El dasbhoard incluye **filtros**, permitiendo explorar detalladamente los datos con la selección de cada uno de ellos, facilitando la interpretación de la información y su análisis. 

**Los `KPIs` solicitados y realizados son los siguientes**

Grafica y medicion de los 2 KPIs propuestos:
- *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*.
  
  Definimos a la **tasa de homicidios en siniestros viales** como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico.
  Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

**"Tomando los datos del censo de CABA del año 2022 de https://www.argentina.gob.ar/caba."**

- "De los 6 años para los cuales se disponen de datos, se puede observar que solo en 2 años y medio se alcanzó el KPI, siendo el año 2020 el de mayor reducción de siniestros. No obstante, se puede atribuir esta disminución más a la pandemia por COVID que a mejoras en las condiciones viales."
  
- *Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*.
  
  Definimos a la **cantidad de accidentes mortales de motociclistas en siniestros viales** como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal.
  Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

- "Desde que se tienen mediciones 2016-2019 el valor no ha variado mucho, el porque no se ve tanta variación en 2019 puede deberse a que aunque la pandemia por COVID restringió la circulación no fue tan remarcada en las motocicletas ya que son medios de transporte mas versátiles para desplazarse y pueden evadir con mayor facilidad los controles."

**Tercer KPI en base a los 2 primeros reducir un 15% la cantidad de siniestros viales en la Comuna N°1, de CABA, respecto al año anterior.**

Se define la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área durante un período de tiempo específico. La fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000


 - Tomando los datos de las comunas de: https://www.estadisticaciudad.gob.ar/eyc/?p=1601, que indica cantidad de habitantes en la comuna n°1 es de 205886 personas se define el tercer KPI.



 - Se define la tasa de siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área durante un período de tiempo específico. La fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000



 - En los años 2019 y 2020 se alcanzo una cifra menor, un 40% en la reducción de la tasa de homicidios en los siniestros viales.




## Fuente de datos:
- [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales): dataset principal `Homicidios`
- [Notas para el uso del dataset de homicidios de siniestros viales de la CABA](https://cdn.buenosaires.gob.ar/datosabiertos/datasets/transporte-y-obras-publicas/victimas-siniestros-viales/NOTAS_HOMICIDIOS_SINIESTRO_VIAL.pdf)

**Complementarios:**
- [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales): datos complementarios `Lesiones`
- Se hizo uso de WebScrapping para obtener informacion adicional para complementar el analisis:
- [superficie_Comunas]https://es.wikipedia.org/wiki/Comunas_de_la_ciudad_de_Buenos_Aires


![Static Badge](https://img.shields.io/badge/Visual_Studio_Code-gray?style=flat&logo=visual%20studio%20code&logoColor=white)
![Static Badge](https://img.shields.io/badge/PowerBI-gray?style=flat&logo=powerbi)
![Static Badge](https://img.shields.io/badge/Python-gray?style=flat&logo=python)
![Static Badge](https://img.shields.io/badge/-Pandas-gray?style=flat&logo=pandas)
![Static Badge](https://img.shields.io/badge/-Matplotlib-gray?style=flat&logo=matplotlib)
![Static Badge](https://img.shields.io/badge/-Seaborn-gray?style=flat&logo=seaborn)






  

