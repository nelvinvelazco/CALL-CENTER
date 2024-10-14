# "ANONYMOUS BANK" CALL CENTER

## INTRODUCCION
Se hará un analisis de los datos con la finalidad de medir los niveles de calidad de servicio, eficiencia y productividad del Call Center. Se analizaran si se estan cumpliendo los SLA para garantizar la satifaccion de cliente

## DESCRIPCION DE LOS DATOS
Los datos que se analizazan estan en un archivo "Call_Center_1999_DataSet.csv" el cual tiene columnas y 444.448 filas donde se detalla el registro de las llamadas durante 12 meses (desde el 01/01/99 hasta el 31/12/99). Lo campos de este DataSet son:

- vru.line: Linea de VRU que atendio la llamada
- call_id: Codigo identificador de llamada
- customer_id: Codigo identificador del Cliente
- priority: Prioridad del Cliente
- type: Tipo de Servicio
- date: Fecha de la llamada
- vru_entry: Hora en que la llamada entra al Call Center
- vru_exit: Hora de Salida de la llamada del vru
- vru_time: Tiempo en Segundos de la llamada en VRU
- q_start: Hora en que la llamada entra en la cola de espera
- q_exit: Hora en que la llamada sale de la cola para ser atendida por un agente
- q_time: Tiempo en Segundos de la llamada en cola
- outcome: Dice si fue atendido o no por un agente o si se cortó
- ser_start: Hora en que la llamada comenzo a ser atendida por un agente
- ser_exit: Hora en que la llamada culmina
- ser_time: Tiempo en Segundos de atencion de la llamada por el Agente
- server: Nombre de Usuraio del agente que atendio la llamada
- startdate: No definido
