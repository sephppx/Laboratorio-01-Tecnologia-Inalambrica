# Laboratorio 01 - Tecnología Inalámbrica

**Felipe Bustos López Y Francisco Polanco Alfaro**

## Descripción

Este repositorio contiene los archivos correspondientes al Laboratorio 01 de la asignatura Tecnología Inalámbrica.

La experiencia tuvo como objetivo analizar el comportamiento de una red inalámbrica dentro de una vivienda, realizando mediciones de potencia recibida en diferentes ubicaciones y observando las variaciones de la señal en función de la distancia y de los obstáculos presentes durante la propagación.

## Objetivo

Analizar la potencia recibida de una red WiFi en diferentes puntos de una vivienda, identificando las variaciones de señal y los posibles fenómenos asociados a su propagación.

## Herramientas utilizadas

- Aircrack-ng
- Airodump-ng
- Tarjeta inalámbrica compatible con modo monitor
- Archivos de captura generados durante la experiencia

## Metodología

Las mediciones fueron realizadas en cuatro ubicaciones diferentes dentro de la vivienda:

- Living
- Cocina
- Comedor
- Patio

En cada ubicación se realizaron capturas de tráfico inalámbrico durante aproximadamente dos minutos.

Posteriormente, los datos obtenidos fueron utilizados para analizar la potencia recibida desde el Access Point y comparar las variaciones observadas entre los distintos puntos de medición.

## Resultados

Los niveles de potencia recibida registrados fueron los siguientes:

| Ubicación | Potencia recibida |
|---|---:|
| Living | -29 dBm |
| Cocina | -46 dBm |
| Comedor | -53 dBm |
| Patio | -61 dBm |

El Living presentó el mayor nivel de potencia recibida, mientras que el Patio presentó el menor nivel.

La disminución de potencia observada se relaciona principalmente con el aumento de la distancia respecto al Access Point y con la presencia de obstáculos físicos que producen atenuación de la señal durante su propagación.

## Mapa de potencia

El archivo `PlanoPDF.pdf` contiene el plano utilizado para representar las ubicaciones de las mediciones y los niveles de potencia obtenidos en cada punto.

## Archivos de captura

Los archivos ubicados en la carpeta `Capturas/` corresponden a los archivos originales generados durante la experiencia.

Se mantienen en su formato `.bak` original para conservar la evidencia de las mediciones realizadas. Estos archivos contienen los datos de captura utilizados posteriormente para el procesamiento y análisis de los resultados.

| Archivo | Ubicación |
|---|---|
| `Living.bak` | Living |
| `Cocina.bak` | Cocina |
| `comedor.bak` | Comedor |
| `Patio.bak` | Patio |

## Análisis

Una mayor potencia recibida representa mejores condiciones para la comunicación inalámbrica. En cambio, una menor potencia puede generar una mayor vulnerabilidad frente a pérdidas de paquetes, disminución de velocidad y posibles interrupciones de la conexión.

En las mediciones realizadas, el Patio presentó el nivel más bajo de potencia, con -61 dBm, por lo que corresponde a la zona más vulnerable de la vivienda.

Como posibles alternativas de mejora se considera la instalación de un segundo punto de acceso o repetidor inalámbrico cercano al Patio. También se puede considerar la reubicación del Access Point hacia una posición más central para reducir la distancia promedio hacia los distintos sectores de la vivienda.

Durante las capturas también se observó una variación del canal mostrado por Airodump-ng. Esta variación corresponde al proceso de escaneo de canales de la herramienta y no implica que el Access Point haya cambiado realmente de canal, ya que el Access Point utilizado durante la experiencia permaneció configurado en el canal 161.

## Conclusión

La experiencia permitió analizar experimentalmente el comportamiento de una red inalámbrica dentro de una vivienda mediante mediciones de potencia recibida en distintos puntos. Los resultados mostraron una disminución de la potencia a medida que aumentaba la distancia respecto al Access Point y debido a la presencia de obstáculos físicos. La diferencia entre los valores obtenidos permitió identificar las zonas con mejor y peor cobertura, destacando la importancia de una adecuada ubicación del Access Point para obtener una distribución más uniforme de la señal inalámbrica.

## Informe

El informe completo del laboratorio se encuentra disponible en:

`LAB01_ Teconologia_Inalambrica.pdf`

## Referencias

[1] S. G. Glisic, *Advanced Wireless Networks: 4G Technologies*. Chichester, England: John Wiley & Sons, 2006.

[2] T. S. Rappaport, *Wireless Communications*, 2nd ed. Philadelphia, PA: Prentice Hall, 2001.# Laboratorio-01-Tecnologia-Inalambrica
# Laboratorio-01-Tecnologia-Inalambrica
# Laboratorio-01-Tecnologia-Inalambrica
