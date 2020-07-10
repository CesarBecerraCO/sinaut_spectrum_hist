# Consultas a históricos desde Python

## Dependencias

```
1. Anaconda Python

Desde Anaconda Prompt:
> conda install jupyter
> jupyter notebook

2. Servicio PHP corriendo (myserver) ** solo usuarios en dicha red **
```

## Descripción
Consulta de medidas promedio 15min a la BD histórica del sistema SCADA SINAUT SPECTRUM.
Las consultas se realizan por señal, para un día o para un mes específico, ejemplo: [2020, 6, 24] ó [2020, 6, 0], respectivamente.

## Implementación
Se utiliza PHP para procesar la petición desde Python (pandas, requests, json)
En la asignación a la variable url, reemplazar 'myserver' por el nombre/ip correspondiente, ejemplo: 'http://10.1.2.23'
