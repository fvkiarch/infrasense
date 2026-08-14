# Informe de Avance 13: Agosto 2026

## 13/8/2026

En el marco de la implementación de mejoras de automatización e infraestructura, se finalizó la fase de diseño y planificación técnica para el sistema de monitoreo ambiental y de acceso físico. Se determinó que la arquitectura más robusta consiste en utilizar un ESP32 configurado con IP estática que actúe como un micro-servidor web, permitiendo que el servidor de Nagios realice consultas activas (polling) para conocer el estado de la puerta y la temperatura en tiempo real. 

- **Tareas completadas:**
  - Definición de la arquitectura de red y flujo de comunicación (Monitoreo Activo vía HTTP).
  - Creación del listado final de componentes necesarios para el ensamblaje físico.

- **Problemas encontrados y soluciones/alternativas propuestas:**
  - *Problema:* El sensor de láminas (reed switch) original de cápsula de vidrio posee terminales muy finos, lo que provocaría falsos contactos o falsas alertas en Nagios si se conectan jumpers directamente debido a las vibraciones de la puerta.
  - *Solución:* Se descartó la soldadura directa. Como alternativa, se propuso el uso de pequeñas borneras/clemas para asegurar los cables de forma mecánica, o bien la adquisición del sensor ya integrado en módulo (KY-021 o MC-38) que cuenta con pines robustos aptos para conexiones con jumpers a presión.

- **Próximos pasos:**
  - Cotizar y adquirir los componentes listados en la casa de electrónica (ESP32, módulo DHT22, cables jumper, borneras/módulos de conexión).

- **Imágenes o videos ilustrativos del avance:**
  - No aplica

## [x]/8/202x
- [Realizar una descripción de los avances en el proyecto en la fecha en uno o dos párrafos]
- [Incluir:]
  - [Tareas completadas]
  - [Problemas encontrados y soluciones/alternativas propuestas]
  - [Próximos pasos]
  - [Imágenes o videos ilustrativos del avance]

## [x]/8/202x
- [Realizar una descripción de los avances en el proyecto en la fecha en uno o dos párrafos]
- [Incluir:]
  - [Tareas completadas]
  - [Problemas encontrados y soluciones/alternativas propuestas]
  - [Próximos pasos]
  - [Imágenes o videos ilustrativos del avance]

## [x]/8/202x
- [Realizar una descripción de los avances en el proyecto en la fecha en uno o dos párrafos]
- [Incluir:]
  - [Tareas completadas]
  - [Problemas encontrados y soluciones/alternativas propuestas]
  - [Próximos pasos]
  - [Imágenes o videos ilustrativos del avance]

## Nota
En este enlace encontrarás un [ejemplo como debe completarse el informe de avance](avance_ejemplo.md).
