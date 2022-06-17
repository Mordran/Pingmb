# Pingmb

## Metodología
Lo que se quiere obtener de este análisis es la latencia entre el servidor web y el servidor de datos para graficarlo y comparar los resultados con otros para ver si es que hay diferencia.

## Requerimientos
- Intercambio de llaves entre el servidor web y el servidor de datos 
- Calcular la latencia entre el servidor de datos y el servidor web 
- Usar scp para copiar los archivos de un servidor a otro 
- Graficar la latencia 

## Resultados
- 1 MBs => 0.00 s
- 11 MBs => 0.00 s
- 21 MBs => 0.01 s
- 31 MBs => 0.01 s
- 41 MBs => 0.01 s
- 51 MBs => 0.02 s
- 61 MBs => 0.02 s
- 71 MBs => 0.03 s
- 81 MBs => 0.03 s
- 91 MBs => 0.04 s


![](Resultados.jpeg)


## Gráfica
La gráfica de la latencia esta representada de la siguiente forma; eje vertical es el tiempo en segundos y el eje horizontal es el tamaño de los archivos en megas 

![](latency.png)
