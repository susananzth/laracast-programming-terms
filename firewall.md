---
layout: default
title: Switches, Routers, y Firewalls
---

> Volver al [inicio](./index.md)

## Dispositivos Clave en una Red

### El Switch de Red

Hemos hablado mucho sobre servidores y clientes, pero hay otros dispositivos igualmente indispensables sin los cuales una red simplemente no funciona. El primero es el **switch de red** (o simplemente *switch*).

Un switch es el dispositivo al que conectamos físicamente nuestras computadoras y demás equipos mediante cables de red. Es lo que permite que esos dispositivos formen parte de la red. En una red doméstica suele haber un solo switch, pero en entornos empresariales puede haber tantos como sean necesarios.

### Puntos de Acceso Inalámbrico

¿Y qué hay de los dispositivos inalámbricos? Para ellos existe el **punto de acceso inalámbrico** (*wireless access point*), que funciona esencialmente como un switch para dispositivos sin cable. En casi todos los casos, el punto de acceso está conectado físicamente a un switch, que es como obtiene acceso a la red.

### Cómo Dirigen el Tráfico los Switches

Los switches no envían datos a ciegas: utilizan **direcciones MAC** para dirigir la información al dispositivo correcto. Para ello, mantienen una tabla de referencia que asocia cada dirección IP con su correspondiente dirección MAC, lo que les permite enrutar los datos con precisión dentro de la red local (LAN).

### El Router

Cuando necesitamos comunicarnos con dispositivos en **otras redes**, entra en juego el **router**. Un router es un dispositivo inteligente que conecta al menos dos redes entre sí. En la mayoría de los casos domésticos y empresariales, se utiliza para conectar la red local (LAN) con Internet.

Si los switches gestionan el tráfico dentro de una red, los routers gestionan el tráfico *entre* redes. Cuando quieres acceder a un dispositivo en otra red, los datos deben pasar por tu router, y luego por varios routers intermedios, hasta llegar a su destino.

### El Firewall: La Muralla de la Red

Toda esa conectividad tiene un precio: la exposición a amenazas externas. Para protegerse, las redes utilizan un **firewall** (cortafuegos). Este dispositivo se sitúa típicamente entre el router y el primer switch de la red, actuando como un **perímetro de seguridad** que controla qué datos pueden entrar desde el exterior y, en algunos casos, qué datos pueden salir hacia Internet.

En la actualidad también existen los llamados **firewalls de próxima generación** (*next-generation firewalls*), que integran tanto las funciones tradicionales de un firewall como capacidades de enrutamiento en un único dispositivo.

### Resumen Visual

```
Internet ←→ Router ←→ Firewall ←→ Switch ←→ Dispositivos
                                      ↑
                               Punto de acceso
                               (dispositivos inalámbricos)
```

En el próximo episodio hablaremos sobre la **capacidad de datos** que puede circular por nuestras redes.

> Contenido generado con Claude 4.6 Sonnet. Imágenes generadas con Gemini 3 Pro.