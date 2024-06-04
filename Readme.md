
por ahora podemos decir que primero tenemos que realizar el EDA para poder saber como nos vinieron los datos y saber que datos podemos procesar y que sabemos sobre ellos,


posteriormente vamos a crear un dashboard , donde debe ser funcional,con storytelling y contener filtros de datos. se debe tener en cuenta muy bien la eleccion de graficos a utilizar ya que es importante la interpretacion de los datos. tambien se debe tomar en cuenta el analisis que se puede sacar de ese grafico en el cual muestra los datos.

se debe mostrar 2 KPI establecidos y proponer,medir y graficar un KPI adicional que consideres relevante para la temática. Los dos KPIs propuestos son:

## Primer KPI
* Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

## Segundo KPI
*Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

## Tercer KPI Propuesto: se busca una reducción del 10% en la cantidad de accidentes ocurridos durante las mañanas, específicamente en el horario de 5 a 9 am del último año, dividiendo los resultados por trimestres para identificar tendencias y áreas de mejora en la seguridad vial durante estas horas críticas del día.

## README
en el readme vamos a tener que desarrollar un glosario o division de puntos que vamos a tener que mostrar como por ejemplo la explicacion del EDA,ETL y DASHBOARD, debe contener tambien el analisis que pudimos sacar de cada uno y tambien de los KPI, tambien el funcionamiento de estos. tambien sumarle el uso de la API. para finalizar podemos añadirle conclusiones con una analisis de toda la informacion que pudimos sacar resumidamente

# como adicional estan:

* Crear una base de datos en un motor SQL, ingestar el dataset procesado y utilizarla como fuente de datos de su dashboard en Power BI (o la herramienta de visualización que utilice).
* Ejecutar scripts de Python en la herramienta de visualización de datos escogida.
* Cruce de datos con datasets complementarios, ya sea para obtener información nueva o poder comparar la información disponible para todas las plataformas.


el analisis hasta el momento, es que los hechos que tiene no todos tienen registrado los 2 participantes,sino que es la victima o acusado, pero eso nos puede dar una probabilidad de cual vehiculo es el que mas siniestros registra.