# Datos al Ecosistema 2025 - Grupo 190

## Descripción de la solución

El producto desarrollado es una herramienta de análisis y visualización para la gestión de la seguridad vial, que combina de manera sistemática datos de siniestralidad, parque automotor y características de los actores viales para identificar tramos críticos, perfilar riesgos específicos y orientar acciones de intervención. Este producto está diseñado para facilitar la toma de decisiones basada en evidencia, apoyar la planificación sectorial y territorial, y servir como insumo operativo para estrategias del Plan Nacional de Seguridad Víal (PNSV) y acciones de cultura ciudadana, fiscalización y formación.

### Tableros de control

<img alt="image" src="https://github.com/user-attachments/assets/bd5aad03-de35-4de2-b7b7-2ed51709358b" />

*Imagen 1. Dashboard con el mapa de calor de los accidentes.*

<img alt="image" src="https://github.com/user-attachments/assets/314d1faf-b5ab-4e2f-b41b-d02f18513fd5" />

*Imagen 2. Dashboard con el perfil de riesgo de los vehículos y las vías críticas.*

## Descripción del reto

El problema central en la gestión de la seguridad vial no es la falta de datos, sino la falta de articulación de los mismos para generar conocimiento territorial específico. Contamos con información crítica sobre SECTORES CRÍTICOS DE MORTALIDAD y el volumen de ACCIDENTES DE TRÁNSITO, pero esta data _se utiliza de forma aislada_. La clave para la prevención efectiva reside en responder preguntas básicas pero vitales: **¿Cuál es el tipo de vehículo más involucrado en los puntos críticos? ¿Cómo se correlaciona la antigüedad del PARQUE AUTOMOTOR MATRICULADO con la siniestralidad en esos mismos tramos?** Al no tener estas respuestas cruzadas, las entidades diseñan campañas y ejecutan operativos de control de vehículos sin un fundamento geográfico o temático preciso.

El Enfoque del Reto: Plataforma de Inteligencia de Riesgo Básico. El reto procura obtener una solución sencilla, pero potente, que articule al menos tres conjuntos de datos abiertos en una **única matriz de riesgo**. Esta solución debe permitir la visualización inmediata del Perfil de Riesgo asociado a cada punto crítico. Es decir, no solo señalar el lugar donde murió una persona, sino identificar de inmediato el tipo de vehículo, la hora y el factor concurrente más frecuente en ese punto específico, utilizando el cruce simple de las bases de datos. Esta plataforma debe ser un insumo directo para la planeación, evitando la necesidad de algoritmos predictivos complejos.

El Impacto y la Acción Inmediata. El resultado esperado es una herramienta de consulta ágil que permita a los tomadores de decisiones focalizar la acción pública de manera inmediata y estratégica. Esto impacta directamente en la mejora de los Componentes de Seguridad Vial al priorizar la señalización y mantenimiento en los puntos de mayor concurrencia de vehículos de riesgo. Además, facilita la Implementación de Estrategias de Comunicación y Mejoramiento de Habilidades al dirigir mensajes específicos (por ejemplo, a motociclistas en el kilómetro X a las 7 a.m.) y al fortalecer la Política Pública de Seguridad Vial (PNSV) con herramientas de articulación basadas en la evidencia más simple y contundente de los datos existentes. Dejemos de ser adivinos; seamos analistas de datos para salvar vidas. 

## Objetivo general

Articular y analizar de forma básica e inmediata los datos abiertos de siniestralidad (Accidentes y Puntos Críticos) y de registro vehicular (Parque Automotor) para generar perfiles de riesgo específicos que permitan la focalización territorial y temática de las estrategias de seguridad vial, garantizando el uso eficiente de los recursos y el cumplimiento de los ejes de acción del PNSV (Infraestructura, Vehículos y Cultura Ciudadana).

## Objetivos especificos

- **OE1.** Focalización de Infraestructura y Vehículos: Crear una matriz de cruce de datos (Mortalidad Crítica y Parque Automotor) que permita identificar y jerarquizar los tramos viales donde la combinación de alta siniestralidad con la tipología o antigüedad de los vehículos matriculados exige la intervención prioritaria de la infraestructura vial y el control técnico-mecánico.
- **OE2.** Diseño de Comunicación de Corresponsabilidad: Utilizar la correlación simple de los tres conjuntos de datos para perfilar al actor vial de mayor riesgo (ej. motociclista joven, peatón adulto mayor, etc.) en cada sector crítico, como insumo directo para el diseño de estrategias de comunicación hiper-focalizadas que promuevan la cultura ciudadana y la corresponsabilidad.
- **OE3.** Ajuste de Programas de Habilidades y Destrezas: Identificar las causas de accidentalidad más recurrentes en los sectores críticos y asociarlas al tipo de vehículo y actor vial para reformular y dirigir los programas de formación, mejora de habilidades y destrezas del sector transporte (público y privado) a las necesidades de prevención más urgentes.
- **OE4.** Generación de Herramientas de Articulación PNSV: Desarrollar una herramienta de visualización sencilla (dashboard o mapa interactivo) que integre los resultados del análisis (puntos de riesgo, perfiles de actor/vehículo) para servir como insumo de articulación, planificación, ejecución y seguimiento de las estrategias del Plan Nacional de Seguridad Vial (PNSV) a nivel sectorial y territorial.
- **OE5.** Estandarización y Calidad de Datos: Identificar las variables clave necesarias de los tres conjuntos de datos para el análisis de riesgo y proponer un esquema básico de estandarización, periodicidad de actualización y mejoramiento de la calidad de los datos abiertos, asegurando su sostenibilidad para la toma de decisiones continua.

## Conjuntos de datos 

| Conjunto de datos | Enlace |
| - | - |
| ACCIDENTES DE TRANSITO DESDE MARZO 2017 A DICIEMBRE DE 2022 | [https://www.datos.gov.co/Transporte/ACCIDENTES-DE-TRANSITO-DESDE-MARZO-2017-A-DICIEMBR/wacd-xkg8/about_data](https://www.datos.gov.co/Transporte/ACCIDENTES-DE-TRANSITO-DESDE-MARZO-2017-A-DICIEMBR/wacd-xkg8/about_data) |
| Sectores críticos mortalidad 2022 | [https://www.datos.gov.co/Transporte/Sectores-cr-ticos-mortalidad-2022/ybqk-8s42/about_data](https://www.datos.gov.co/Transporte/Sectores-cr-ticos-mortalidad-2022/ybqk-8s42/about_data) |
| Vehículos matriculados desde enero de 2020 hasta mayo del 2022 por clase, modelo y tipo de vehículo | [https://www.datos.gov.co/Transporte/Veh-culos-matriculados-desde-enero-de-2020-hasta-m/bj7e-xc9g/about_data](https://www.datos.gov.co/Transporte/Veh-culos-matriculados-desde-enero-de-2020-hasta-m/bj7e-xc9g/about_data) |

