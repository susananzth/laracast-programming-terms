---
layout: default
title: Latencia
---

> Volver al [inicio](./index.md)

## Latencia en Redes: Qué Es y Qué la Causa

### ¿Qué es la Latencia?

La **latencia de red** es el tiempo que tarda un dato en viajar desde su origen hasta su destino y regresar. Es un viaje de ida y vuelta, similar al tiempo que transcurre entre hacer una pregunta y recibir una respuesta.

Desde un punto de vista técnico, podemos medirla con el comando **ping**, que nos muestra el tiempo de respuesta de una conexión con cualquier servidor. Por ejemplo, una latencia promedio de 14 milisegundos hacia un servidor en Internet es un resultado razonablemente bueno. Sin embargo, ese mismo valor en una red local (LAN) sería inaceptablemente alto, ya que en una LAN la latencia debería ser de apenas 1 o 2 milisegundos.

La latencia afecta casi todo en una conexión: su estabilidad, su velocidad percibida y la experiencia general del usuario.

### ¿Qué Causa la Latencia?

**1. La Distancia**
Cuanto mayor es la distancia física entre el origen y el destino, mayor es la latencia. La conexión entre tu computadora y tu router es casi instantánea porque están físicamente cerca. En cambio, conectarte a un servidor ubicado a miles de kilómetros introduce un retraso inevitable, simplemente por el tiempo que tarda la señal en recorrer esa distancia.

**2. El Equipamiento de Red**
Cada dispositivo que se interpone entre el origen y el destino (switches, routers, firewalls) debe procesar el tráfico que pasa por él. Cuantos más dispositivos haya en la ruta, y cuanto más tráfico tengan que procesar, mayor será la latencia introducida en la conexión.

**3. La Carga del Servidor de Destino**
Este es probablemente el factor más determinante. Un servidor web no solo atiende tu solicitud: simultáneamente gestiona cientos de miles, o incluso millones, de peticiones de otros usuarios. Cuanto mayor sea su carga de trabajo, más lenta será su respuesta y, por lo tanto, mayor será la latencia experimentada.

### Conclusión

La latencia es ese pequeño (o no tan pequeño) retraso que hace que una conexión se sienta lenta, incluso cuando el ancho de banda es más que suficiente. Es un recordatorio de que la velocidad de una red no depende únicamente de cuántos datos pueden circular por ella, sino también de cuánto tiempo tardan en llegar.

> Contenido generado con Claude 4.6 Sonnet. Imágenes generadas con Gemini 3 Pro.