# Análisis de Red de Conflictos - Proyecto de Vida Artificial

[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/Zers04/Network-Analysis-of-Internal-Conflicts/blob/main/README.md)
[![es](https://img.shields.io/badge/lang-es-blue.svg)](https://github.com/Zers04/Network-Analysis-of-Internal-Conflicts/blob/main/README-es.md)

![Gephi](https://img.shields.io/badge/Gephi-0.10%2B-green)

Análisis de una red compleja de conflictos armados internos utilizando el software Gephi para la visualización y cálculo de métricas.

## 📋 Descripción del Proyecto

Este proyecto analiza una red de conflictos con **1078 nodos** y **898 aristas**, implementado como parte del curso de Vida Artificial de la Universidad del Valle. El análisis se centra en conflictos internos, definidos como situaciones de violencia prolongada entre fuerzas gubernamentales y grupos armados dentro de un Estado.

**Integrantes:**
- Valentina Londoño Dueñas (202160173)
- Juan David Cataño Castillo (202160227)

**Fecha de Presentación:** Abril de 2024

## 🎯 Objetivos

- Recolectar información de fuentes confiables sobre conflictos armados.
- Construir y modelar una red compleja que represente estas relaciones de conflicto.
- Utilizar Gephi para visualizar la red y identificar patrones, nodos críticos y propiedades estructurales.
- Analizar métricas de la red para extraer información relevante sobre la dinámica de los conflictos.

## 🛠️ Metodología y Herramientas

El proyecto se realizó siguiendo estos pasos:

1.  **Recolección:** Búsqueda y filtrado de información en motores de búsqueda (Google, Google Scholar) y bases de datos confiables.
2.  **Modelado:** Construcción de la red donde los nodos representan entidades (países, grupos armados, gobiernos) y las aristas representan relaciones de conflicto entre ellas.
3.  **Análisis:** Uso del software **Gephi** para:
    - Visualizar la estructura general de la red y sus componentes.
    - Calcular métricas topológicas (diámetro, radio, coeficiente de clustering, etc.).
    - Identificar comunidades y nodos clave mediante algoritmos de layout y filtros.
4.  **Interpretación:** Análisis de los resultados para generar conclusiones sobre los conflictos.

**Herramienta Principal:** [Gephi - The Open Graph Viz Platform](https://gephi.org/)

## 📊 Resultados y Métricas Principales

El análisis en Gephi reveló las siguientes características de la red:

| Métrica | Valor |
| :--- | :--- |
| Nodos | 1078 |
| Aristas | 898 |
| Diámetro | 13 |
| Radio | 1 |
| Longitud promedio del camino más corto | 5.52 |
| Coeficiente de Clustering promedio | 0.139 |
| Número de Componentes Débilmente Conectados | 254 |
| Triángulos totales | 47 |

## 📈 Visualizaciones y Hallazgos

El análisis permitió generar visualizaciones que muestran:
- La **estructura general** de la red de conflictos.
- La distribución de **nodos altamente conectados** (hubs).
- La **distribución de grados** y el **grado por peso de las aristas**.
- La **intermediación** entre nodos.
- La distribución de la **Centralidad de Cercanía**.
- El **coeficiente de clustering** de los nodos.

## 🎥 Demo y Video de la Red

Se creó una visualización dinámica de la red que muestra su estructura y conexiones. Puede verse en el siguiente enlace:
[**Ver demostración en YouTube**](https://youtu.be/vnTD_hIhufo?si=7mALQF5dfQBRnCVz)

## 📚 Conclusión y Perspectivas Futuras

El análisis de red permitió verificar el tipo de estructura compleja que presentan los conflictos globales, destacando casos puntuales que ofrecen un contexto histórico interesante. Como trabajo futuro, se propone:
- Ampliar las fuentes de recolección para representar más conflictos y obtener una red más completa.
- Actualizar la información para incluir desarrollos recientes.
- Explorar la integración de otros atributos a los nodos y aristas (intensidad del conflicto, duración, etc.).

## 📖 Bibliografía

1.  Iheanacho, E. N. (2019). THE MENACE OF FULANI HERDSMEN IN NIGERIA: A THREAT TO NATIONAL SECURITY...
2.  Benjaminsen, T. A., & Ba, B. (2021). Fulani-dogon killings in mali: Farmer-herder conflicts as insurgency and counterinsurgency...
3.  Njoku, T. C. M. (1995). Cristianos y Musulmanes en Nigeria...
4.  Méndez, M. N. R. (2005). Construcción y deconstrucción nacional en Medio Oriente: el caso de Irak...
5.  Osorno, D. E. (2011). El cártel de Sinaloa: Una historia del uso político del narco...
6.  Bastian, M., Heymann, S., & Jacomy, M. (2009). Gephi: an open source software for exploring and manipulating networks...

---

*Proyecto desarrollado para el curso de Vida Artificial - Universidad del Valle - 2024*
