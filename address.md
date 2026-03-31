---
layout: default
title: Direcciones
---

> Volver al [inicio](./index.md)

## What is Addressing?

### Direcciones MAC e IP

Cuando añades un dispositivo a una red, no sabe automáticamente cómo comunicarse con los demás. El problema no es de idioma ni de protocolo, sino de **direcciones**: para que dos dispositivos se comuniquen, deben conocerse mutuamente. Y todo dispositivo tiene, al menos, dos tipos de dirección.

#### La Dirección MAC

La primera es la **dirección MAC** (*Media Access Control*). Es un identificador único asignado al componente de red dentro del dispositivo, algo así como una **huella digital**: irrepetible y permanente.

#### La Dirección IP

La segunda, y más utilizada en la práctica, es la **dirección IP**. Esta funciona más como una dirección postal: es la que permite enviar datos a otro dispositivo, ya sea dentro de la misma red o en una red completamente diferente. Las direcciones IP son las que hacen posible **enrutar la información** a través de las carreteras y autopistas que conforman nuestra red e Internet.

![Direcciones](img/address-01.png)

### El Sistema DNS: El Directorio de Internet

Claro que nadie quiere memorizar una dirección IP para visitar *Google.com*. Para eso existe el **DNS** (*Domain Name System* o Sistema de Nombres de Dominio), que actúa como una **guía telefónica digital**: traduce nombres legibles para humanos en direcciones IP legibles para las máquinas.

Cuando escribes *Google.com* en tu navegador, tu computadora hace una consulta a un **servidor DNS**, que devuelve la dirección IP correspondiente. Todo esto ocurre en fracciones de segundo, de forma transparente para el usuario.

![DNS](img/address-02.png)

### Nombres de Dispositivos en una LAN

Este sistema no se limita a los sitios web. En una red local (LAN), casi todos los dispositivos tienen un nombre asignado, ya sea por el fabricante o por el usuario. En Windows, por ejemplo, el nombre predeterminado de una computadora suele comenzar con *desktop-*. Al hacer ping a ese nombre, el sistema lo traduce automáticamente a su dirección IP, de la misma manera que lo haría con un sitio web.

![Nombres de Dispositivos](img/address-03.png)

### Resumen

Todo dispositivo en una red necesita dos direcciones:

- **Dirección MAC:** identifica de forma única al componente de red del dispositivo. Es obligatoria para pertenecer a una red.
- **Dirección IP:** permite la comunicación entre dispositivos, tanto dentro de la misma red como hacia otras redes externas.

Y para simplificar todo este sistema de direcciones, existe el **DNS**, que nos permite usar nombres en lugar de números. Muchas veces, los dispositivos con los que más interactuamos a través de la red son los **servidores**.

> Contenido generado con Claude 4.6 Sonnet. Imágenes generadas con Gemini 3 Pro.