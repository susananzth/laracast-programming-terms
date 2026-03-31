---
layout: default
title: Redes
---

> Volver al [inicio](./index.md)

## ¿Qué es una Red?

Las redes son fundamentales para la informática moderna, ya que sin ellas los dispositivos no podrían comunicarse entre sí. Una red conecta múltiples dispositivos para que puedan intercambiar información. Pensemos en el teléfono y la computadora como ejemplos: cualquier dispositivo con capacidad de conexión (computadoras, tabletas, teléfonos, impresoras, incluso bombillas inteligentes) puede formar parte de una red.

Una buena analogía: si los dispositivos fueran edificios aislados, la red serían las carreteras que los conectan, y los datos que viajan entre ellos serían los vehículos que circulan por esas carreteras.

![Red](img/network-01.png)

### LAN vs WAN

Existen dos tipos principales de redes:

- **LAN (Red de Área Local):** Es una red localizada, generalmente contenida dentro de un solo edificio. Tu hogar tiene una LAN, tu oficina también.
- **WAN (Red de Área Amplia):** Conecta múltiples LANs entre sí. La WAN más grande que existe es **Internet**.

![lan-vs-wan](img/network-02.png)

### Los Cortafuegos Protegen las LANs

Tu LAN doméstica está conectada a Internet y, por lo tanto, al resto de redes del mundo. Sin embargo, esto no significa que cualquier persona pueda acceder a tus dispositivos. Para eso existen los **cortafuegos (firewalls)**, cuya función principal es proteger una LAN de intrusiones externas provenientes de la WAN.

### Protocolos de Red

Para que los dispositivos puedan comunicarse, no basta con estar conectados: también deben *entenderse*. De la misma manera que los humanos usamos idiomas para comunicarnos, los dispositivos usan **protocolos**. El más utilizado es el protocolo **TCP/IP**.

![Protocolos](img/network-03.png)

### Enrutamiento de Paquetes con TCP/IP

El funcionamiento de TCP/IP es muy ingenioso. Cuando escribes una dirección web como *susananzth.com* en tu teléfono, tu dispositivo no envía la solicitud como un bloque único. En su lugar, **divide los datos en paquetes individuales** que pueden viajar por rutas distintas hasta llegar a su destino, donde son reensamblados y procesados. Lo mismo ocurre con la respuesta del servidor hacia tu dispositivo.

En esencia, las redes son las autopistas del mundo digital, las que permiten que todo funcione de manera fluida y continua.
![Paquetes](img/network-04.png)

### ¿Por Qué Son Importantes las Direcciones?

Para que un dispositivo pueda enviar datos a otro, necesita saber *dónde* se encuentra ese dispositivo, es decir, necesita conocer su **dirección**. Esto será el tema del próximo episodio.
![Direcciones](img/network-05.png)

> Contenido generado con Claude 4.6 Sonnet. Imágenes generadas con Gemini 3 Pro.