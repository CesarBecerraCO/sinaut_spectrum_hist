# Consultas a históricos desde Python

## Dependencias

```
Anaconda Python
> conda install jupyter

Servicio PHP corriendo (myserver) *** solo usuarios en dicha red ***
```

## Descripción
Consulta de medidas promedio 15min a la BD histórica del sistema SCADA SINAUT SPECTRUM.
Las consultas son se realizan por señal, para 1 día o para un mes específico.

## Implementación
Se utiliza PHP para procesar la petición desde Python (pandas, requests, json)
En la asignación a la variable url, reemplazar 'myserver' por el nombre/ip correspondiente, ejemplo: 'http://10.1.2.23'
