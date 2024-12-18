# **ANONYMOUS BANK" CALL CENTER**

 ##  `Tabla de Contenido`
1. [Información General](#Información-General)
2. [Tecnologías Utilizadas](#tecnologías-Utilizadas)
3. [EDA](#eda)
4. [Visualización](#visualización)
5. [Conclusiones](#conclusiones)

## `Informacion General`

 Un Call Center de un Banco: “Anonymous Bank” en Israel desea un analisis de datos de las llamadas. El dataset suministrado contiene las llamadas registradas durante 12 meses (desde el 01/01/99 hasta el 31/12/99).

Se solicita definir, construir y presentar un Dashboard que permita medir los niveles de calidad de servicio, eficiencia y productividad del Call Center. Para ello, se propone que definamos los KPIs adecuados para poder medir los objetivos propuestos, y definir nuevos niveles objetivos de manera de ofrecer esos niveles de SLA a terceras partes, o generar un nuevo servicio Premium para los clientes mas importantes del banco
 
## `Tecnologias Utilizadas`

- Se utilizó Python version 3.11 y varias librerias como: *Pandas, Matplotlib, Seaborn, Numpy*. Se utilizó el entornos en cuadernos de *'jupyter'* para codificar y editar. 
- Tambien se utilizó Power BI Desktop v.2.137 para construir un dasboard mostrando graficos y KPIs

## `EDA`

Se realizó un analisis exploratorio para comprender los datos, identificar y corregir valores atipicos e identificar outliers. Se usaron tecnicas estadisticas para identificar y graficar patrones que nos ayuden a tomar desiciones. Puede ser el EDA en siguiente link: [EDA.ipynb](EDA.ipynb)

## `Visualización`

Se realizó un Dashboard en Power BI mostrando los datos y los KPIs mediante graficos.

Los KPI son los siguientes:
- *Aumentar 5% las llamadas completadas segun el mes anterior.*

En el siguiente link se puede ver el Dashboard en Power BI: [Dashboard.pbix](Dashboard.pbix)

## `Conclusiones`

- Durante este año (1999) se realizaron un total de 444,448 llamadas. De las cuales el 79.46 % se completaron y el 20.54% no se completaron 
- Los meses de Agosto, Noviembre y Diciembre son los meses con mayor volumen de llamadas.
- El tiempo promedio de espera de las llamadas es de 59 segundos.
- El mayor trafico de llamadas ocurre durante las 9:15 am y 11:45 am.
- Los clientes regulares en promedio tienen menos tiempo de espera en comparacion con los clientes de alta prioridad. Esto es opuesto a lo que deberia pasar pues los clientes de alta prioridad deberian ser atendidos mas rapido.
- El 20.54 % de las llamadas no se completan ya sea por tiempo de espera o por caida de la llamada, este es un porcentaje muy alto.
- El dia con mayor volumen de llamadas es el domingo por lo tanto se deberian tener mas agentes ese dia. Los dias con menor volumen son viernes y sabado.
- Los meses con mayor trafico son agosto y diciembre.
- De los 6 VRU (unidad de respuesta de voz) instalados solo estan funcionando 2. Es necesario habilitar las VRU para aumentar la eficiencia en la atencion al cliente
