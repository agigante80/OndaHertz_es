---
layout: post
title: "Primeros pasos con APRS para radioaficionados"
subtitle: "Descubre cómo compartir tu ubicación y mensajes usando el sistema APRS en radioafición"
excerpt_image: https://www.ondahertz.es/assets/images/2026-03-10-0748_Primeros_pasos_con_APRS.png
categories: [radioafición, tecnología]
tags: [APRS, ubicación, radioafición, comunicación]
---

![banner](https://www.ondahertz.es/assets/images/2026-03-10-0748_Primeros_pasos_con_APRS.png "Ilustración de APRS mostrando cómo compartir ubicación con tecnología de radioafición.")

# Primeros pasos con APRS: comparte tu ubicación y mensajes en tiempo real

La radioafición es mucho más que hablar a través de un micrófono. Es una pasión por la tecnología, la experimentación y la comunicación global. Entre las múltiples facetas de este hobby, destaca una tecnología que ha revolucionado la manera en que los radioaficionados comparten información sobre su localización, clima y mensajes breves: el **APRS** (Automatic Packet Reporting System).

En este artículo vamos a descubrir, de manera sencilla y práctica, cómo dar tus primeros pasos en APRS y cómo puedes empezar hoy mismo a compartir tu ubicación y mensajes a través de las ondas hertzianas.

---

## ¿Qué es APRS?

El **APRS** es un sistema digital creado por Bob Bruninga (WB4APR, SK) en los años 80, pensado para transmitir información en tiempo real a través de la radio. Originalmente se ideó para reportar posiciones de estaciones móviles, pero su utilidad se ha extendido a reportes meteorológicos, mensajes cortos, telemetría, y mucho más.

**APRS** utiliza paquetes de datos que pueden ser recibidos por estaciones cercanas y retransmitidos a través de repetidores digitales llamados *digipeaters*, permitiendo así que la información viaje largas distancias e incluso llegue a Internet mediante *iGates* (puertas de enlace).

> “La magia de APRS es permitir a los radioaficionados compartir información valiosa y ubicaciones en tiempo real usando solo una radio y un poco de creatividad.”  
> — Bob Bruninga, WB4APR

---

## ¿Para qué sirve APRS?

APRS es una herramienta extremadamente versátil. Sus aplicaciones principales incluyen:

- **Compartir ubicación**: Puedes transmitir tu posición GPS para que otros radioaficionados la vean en mapas en tiempo real.
- **Mensajería**: Envío y recepción de mensajes cortos entre estaciones.
- **Reportes meteorológicos**: Estaciones pueden enviar datos meteorológicos automáticamente.
- **Seguimiento de eventos**: Ideal para actividades como maratones, expediciones o emergencias.
- **Telemetría**: Enviar datos sobre el estado de equipos remotos.

![Mapa APRS](https://aprs.fi/static/images/screenshots/aprsfi_map_800x500.png "Ejemplo de mapa APRS mostrando ubicaciones en tiempo real.")

---

## ¿Qué necesito para empezar con APRS?

Para iniciarte en APRS hay varias opciones, dependiendo del equipo con el que cuentes y tu nivel de experiencia. Veamos las alternativas más populares:

| Opción                    | Equipo necesario                    | Facilidad de uso | Coste estimado | Movilidad                  |
|---------------------------|-------------------------------------|------------------|---------------|----------------------------|
| Radio con APRS integrado  | Walkie o móvil con APRS (Ej. Yaesu FT-3D, Kenwood TH-D74) | Muy fácil       | Alto          | Portátil o móvil           |
| Radio + TNC externo       | Cualquier radio VHF/UHF + TNC (Ej. Mobilinkd) + GPS    | Media           | Medio         | Portátil o móvil           |
| Software + PC/Smartphone  | PC, Tablet o Smartphone + interfaz de audio + radio     | Fácil           | Bajo           | Limitada a portátil        |
| Solo smartphone (APRS-IS) | App como APRSdroid (usa Internet)                       | Muy fácil       | Muy bajo       | Total, pero dependiente de red |

### Radio con APRS integrado

Muchos equipos modernos ya incluyen funcionalidad APRS incorporada. Esto simplifica mucho el proceso: solo necesitas configurar tu indicativo, frecuencia (normalmente 144.800 MHz en Europa) y algunos parámetros básicos.

### Radio + TNC externo

Si tienes una radio tradicional sin APRS integrado, puedes añadirle un **TNC** (Terminal Node Controller). Hay opciones comerciales como el Mobilinkd o puedes construir uno casero si te gusta experimentar.

### Software en PC o smartphone

Existen programas como **Dire Wolf** (para PC) o **APRSdroid** (para Android), que permiten decodificar y enviar tramas APRS usando solo la entrada/salida de audio del equipo y la radio. Es ideal para quienes quieren probar sin grandes inversiones.

### Solo smartphone (APRS-IS)

Si lo que buscas es experimentar sin comprar hardware adicional, existen apps como **APRSdroid**, que pueden enviar y recibir información sólo usando Internet vía el sistema APRS-IS. No es radioafición pura, pero sirve para aprender.

---

## ¿Cómo funciona la transmisión de ubicación?

El proceso es sencillo:

1. **Captura GPS**: El dispositivo obtiene tus coordenadas.
2. **Codificación**: Estas coordenadas se empaquetan en un mensaje especial llamado *paquete AX.25*.
3. **Transmisión**: El paquete se envía por radio usando modulación AFSK (1200 baudios en VHF).
4. **Recepción y reenvío**: Otros equipos (digipeaters) lo reciben y reenvían.
5. **iGate**: Finalmente puede llegar a Internet a través de un punto de acceso (*iGate*), haciéndolo visible en páginas como [aprs.fi](https://aprs.fi/).

---

## Configuración básica paso a paso

A continuación te mostramos cómo puedes empezar con un equipo típico:

### 1. Configura tu indicativo

El indicativo es tu nombre en la red APRS. Debe ser tu indicativo oficial seguido de un SSID adecuado (ejemplo: EA1XYZ-7 para móvil, EA1XYZ-9 para portátil).

### 2. Elige la frecuencia

En Europa la frecuencia estándar es **144.800 MHz** FM.

### 3. Ajusta el sistema APRS

Entra al menú de configuración APRS de tu equipo y revisa:

- **TX Interval**: Cada cuánto tiempo envía tu posición (ejemplo: cada 3 minutos).
- **Path**: Normalmente `WIDE1-1,WIDE2-1` para cobertura básica regional.
- **Mensaje beacon**: Un texto corto descriptivo (ejemplo: “En ruta por Madrid”).
- **GPS**: Actívalo o conecta tu GPS externo si es necesario.

### 4. Prueba la transmisión

Envía un beacon y revisa si apareces en [aprs.fi](https://aprs.fi/) buscando tu indicativo.

---

## Tabla comparativa de equipos para APRS

| Equipo                        | Funcionalidad APRS | GPS Integrado | Precio aprox. (€) |
|-------------------------------|-------------------|---------------|------------------|
| Yaesu FT-3D                   | Completa          | Sí            | 400-500          |
| Kenwood TH-D74                | Completa          | Sí            | 500-600          |
| Mobilinkd TNC + cualquier VHF | Completa          | Depende del GPS| 100 (+radio)     |
| BaoFeng UV-5R + TNC           | Parcial           | No            | 50 (+TNC)        |
| Smartphone (APRSdroid)        | Solo APRS-IS      | Sí            | Gratis – 5       |

---

## ¿Qué puedes hacer con APRS además de compartir ubicación?

- Enviar mensajes cortos punto a punto o a grupos.
- Recibir avisos meteorológicos automáticos.
- Ver ubicaciones de otros colegas en mapas.
- Recibir alertas e información de emergencias.
- Integrar sensores para telemetría remota.

---

## Recursos recomendados

Para aprender más sobre APRS y seguir experimentando:

- [Manual oficial de APRS](http://www.aprs.org/doc/APRS101.pdf)
- [APRS.fi](https://aprs.fi/) – Mapa mundial en tiempo real.
- [APRSdroid](https://aprsdroid.org/) – App Android para APRS.
- [Dire Wolf](https://github.com/wb2osz/direwolf) – Software TNC para PC.

---

## Consejos prácticos para el uso responsable de APRS

1. **No abuses del intervalo de transmisión:** Envía beacons cada pocos minutos, no cada pocos segundos.
2. **Configura correctamente tu path:** Un path demasiado largo satura la red.
3. **Incluye información útil:** Mensajes descriptivos ayudan a otros usuarios.
4. **Respeta la privacidad:** No compartas ubicaciones ajenas sin permiso.

---

## Conclusión

El mundo de la radioafición está en constante evolución y tecnologías como el APRS nos demuestran cómo combinar tradición e innovación. Compartir tu ubicación, mensajes y datos útiles por las ondas es una experiencia gratificante que une a los radioaficionados alrededor del mundo.

Si eres curioso, experimentador o simplemente disfrutas aprendiendo cosas nuevas, te animamos a dar tus primeros pasos con APRS. No necesitas grandes inversiones ni conocimientos avanzados, solo ganas de descubrir otra dimensión del hobby.

Recuerda siempre operar dentro del marco legal y ético de la radioafición, y ¡disfruta explorando el fascinante universo del APRS!

---

> “Radioafición es experimentar, aprender y compartir; con APRS llevamos esa filosofía al siguiente nivel.”  
> — EA1XYZ

---

¿Tienes dudas o quieres compartir tu experiencia? Déjanos tus comentarios o visita nuestro [foro Ondahertz](https://www.ondahertz.es/foro) para seguir aprendiendo juntos.

---