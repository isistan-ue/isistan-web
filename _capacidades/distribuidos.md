---
layout: single
title: Computación paralela, distribuida y móvil
author_profile: false
classes: wide
header:
  teaser: /assets/images/distribuidos.webp
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
sidebar:
  - title: 
    image: /assets/images/distribuidos.webp
---

A raíz del crecimiento y éxito de las infraestructuras computacionales distribuidas, sumado a las mayores capacidades de hardware de dispositivos móviles tales como smartphones y tablets, recientemente se comenzó a considerar la posibilidad de integrar como recursos de un sistema distribuido a tales dispositivos, dando origen a los Cloud móviles, Clústers ad-hoc de smartphones y más recientemente entornos Edge y Dew. La línea de investigación principal se enfoca en generar nuevos métodos y técnicas de desarrollo para este tipo de entornos donde se combinan distintos tipos de dispositivos computacionales con batería y fuentes de energía permanente, distintas posibilidades de conectividad o dedicación parcial/total al cómputo. 

El grupo logró avances significativos hacia aprovechar el poder de computo de dispositivos móviles actuales logrando un balance aceptable entre duración de batería/uso de recursos para tareas demandantes en uso de CPU. Además, se avanzó en una plataforma distribuida para construir algoritmos de recomendación sobre grafos, muy usados en sistemas de recomencación sociales. Finalmente, se realizaron contribuciones en computación orientada a servicios, específicamente en mejoras en calidad de descripciones de servicios que impactan en menores tiempos de desarrollo y mayor eficacia en la búsqueda e integración de servicios. Además, varios de los resultados se aplicaron a problemas de producción animal, en particular de ganado vacuno.

Algunos de los temas tratados recientemente son:
- Arquitecturas orientadas a servicios (SOA) y técnicas para el desarrollo, especificación, descubrimiento y composición de Servicios Web
- Plataformas y soporte para el desarrollo de software distribuido y Big Data para Clústers, Clouds y Grids
- Métodos de desarrollo, ejecución eficiente en energía y medición de consumo de aplicaciones móviles
- Aplicaciones y métodos computacionalmente intensivos para el soporte de decisiones en AgroTICs
- Planificación y asignación de recursos en sistemas distribuidos Edge y Dew.
- Modelamiento y simulación de dispositivos Android alimentados por batería para ejecución de software intensivo
- Aprovechamiento de entornos Dew para aplicaciones móviles e IoT.


Algunos proyectos de I+D relacionados con estas líneas:
- Incremento de la utilización de routers con ancho de banda ocioso. Desarrollo en [OpenWrt](https://openwrt.org/)
- Procesamiento de grandes grafos sobre redes sociales. Se probó con el grafo completo de Twitter al 2010. Se trabajó luego con algoritmos de recomendación (otras de las líneas de investigación). Se aplican técnicas de clustering y clasificación.
- Estimación de peso en vacas lecheras con cámaras 3D. Se trabaja con modelos de IA para la determinación del peso a partir de un conjunto de imágenes sobre el lomo de la vaca.
- Calificación automática por tipo de ganado vacuno lechero. La clasificación se basa en el uso de técnicas IA sobre imágenes. 
- Separación de residuos en origen. Se registra el residuo, se estima el peso y volumen a partir de la imagen. Planificación de recolección mediante técnicas meta-heurísticas, en conjunto con la Dirección de Medio Ambiente - Municipio de Tandil.
- Desarrollo de una plataforma Edge para aprovechar el poder ocioso de los móviles en situaciones de clusters oportunistas (ej. colas de espera, transporte público) para correr algoritmos de deep learning con tensorflow. El control/scheduling de los móviles está a cargo de single board computers como raspberry, gigabyte brix, etc. En colaboración con la [PUC de Chile](https://www.ing.uc.cl/).
