# Datos al Ecosistema 2025 - Grupo 190

## Descripción de la solución

El producto desarrollado es una herramienta de análisis y visualización para la gestión de la seguridad vial, que combina de manera sistemática datos de siniestralidad, parque automotor y características de los actores viales para identificar tramos críticos, perfilar riesgos específicos y orientar acciones de intervención. Este producto está diseñado para facilitar la toma de decisiones basada en evidencia, apoyar la planificación sectorial y territorial, y servir como insumo operativo para estrategias del Plan Nacional de Seguridad Víal (PNSV) y acciones de cultura ciudadana, fiscalización y formación.

### Resultados Integrados del Análisis y Líneas de Acción

Los hallazgos obtenidos a partir del análisis de los datos suministrados por la Alcaldía de Calarcá, complementados con información proveniente de fuentes de datos abiertos, se presentan de manera detallada en el documento [docs/Resultados_Estrategicos_Accidentalidad_Calarca.pdf](https://github.com/Datos-al-Ecosistema-2025-Grupo-190/calarca-en-ruedas/blob/main/docs/Resultados_Estrategicos_Accidentalidad_Calarca.pdf).
Este archivo consolida los principales productos analíticos y orienta la toma de decisiones basada en evidencia para la gestión de la seguridad vial del municipio.

En particular, el documento desarrolla:

- Identificación del actor vial de mayor riesgo
- Ajuste de los Programas de Habilidades y Destrezas
- Propuesta de estandarización y mejoramiento de datos

### Tableros de control

>[!important]
>Los tableros de control se encuentran en la ruta [/dashboard](https://github.com/Datos-al-Ecosistema-2025-Grupo-190/calarca-en-ruedas/tree/main/dashboard) del repositorio. 

Este primer tablero presenta una visión de los siniestros viales ocurridos de 2021 a 2023, permitiendo analizar su comportamiento temporal, espacial y poblacional. Muestra el número de accidentes por mes, destacando picos de siniestralidad en ciertos periodos del año, e identifica las principales causas (con el choque como la más frecuente) junto con la distribución por género, donde predominan los hombres involucrados. También segmenta por rangos de edad, evidenciando mayor incidencia en personas entre 30 y 60 años, y compara la ocurrencia de accidentes entre zonas rurales y urbanas, con clara predominancia de eventos en áreas urbanas. Finalmente, el mapa de calor georreferenciado revela los puntos críticos de accidentalidad dentro del municipio, facilitando la identificación de sectores que requieren intervención prioritaria.

<img alt="image" src="https://github.com/user-attachments/assets/1d4f0469-d232-4acb-b790-7f5fcbf6b43e" />

*Imagen 1. Dashboard con el mapa de calor de los accidentes.*

---

El siguiente tablero profundiza en la relación entre los siniestros viales y los tipos de vehículo involucrados, permitiendo analizar patrones de riesgo más específicos. Se observa la distribución de accidentes por tipo de vehículo, destacando a las motocicletas y automóviles como los más involucrados, y se clasifica la gravedad de los hechos, donde predominan los casos con heridos y daños materiales por encima de los accidentes fatales. También se presenta la composición del parque vehicular registrado, mostrando la proporción de cada categoría y su posible correspondencia con los siniestros. Además, se identifica cuáles marcas presentan mayor participación en accidentes, resaltando a Chevrolet, Suzuki y Renault. Finalmente, el panel destaca las vías con mayor siniestralidad proporcionando información clave para focalizar intervenciones viales y estrategias de control vehicular.

<img alt="image" src="https://github.com/user-attachments/assets/feab42b0-4034-4a57-a9eb-1ddcec80c67d" />

*Imagen 2. Dashboard con el perfil de riesgo de los vehículos y las vías críticas.*

---

## Descripción del reto

El problema central en la gestión de la seguridad vial no es la falta de datos, sino la falta de articulación de los mismos para generar conocimiento territorial específico. Contamos con información crítica sobre SECTORES CRÍTICOS DE MORTALIDAD y el volumen de ACCIDENTES DE TRÁNSITO, pero esta data _se utiliza de forma aislada_. La clave para la prevención efectiva reside en responder preguntas básicas pero vitales: **¿Cuál es el tipo de vehículo más involucrado en los puntos críticos? ¿Cómo se correlaciona la antigüedad del PARQUE AUTOMOTOR MATRICULADO con la siniestralidad en esos mismos tramos?** Al no tener estas respuestas cruzadas, las entidades diseñan campañas y ejecutan operativos de control de vehículos sin un fundamento geográfico o temático preciso.

El Enfoque del Reto: Plataforma de Inteligencia de Riesgo Básico. El reto procura obtener una solución sencilla, pero potente, que articule al menos tres conjuntos de datos abiertos en una **única matriz de riesgo**. Esta solución debe permitir la visualización inmediata del Perfil de Riesgo asociado a cada punto crítico. Es decir, no solo señalar el lugar donde murió una persona, sino identificar de inmediato el tipo de vehículo, la hora y el factor concurrente más frecuente en ese punto específico, utilizando el cruce simple de las bases de datos. Esta plataforma debe ser un insumo directo para la planeación, evitando la necesidad de algoritmos predictivos complejos.

El Impacto y la Acción Inmediata. El resultado esperado es una herramienta de consulta ágil que permita a los tomadores de decisiones focalizar la acción pública de manera inmediata y estratégica. Esto impacta directamente en la mejora de los Componentes de Seguridad Vial al priorizar la señalización y mantenimiento en los puntos de mayor concurrencia de vehículos de riesgo. Además, facilita la Implementación de Estrategias de Comunicación y Mejoramiento de Habilidades al dirigir mensajes específicos (por ejemplo, a motociclistas en el kilómetro X a las 7 a.m.) y al fortalecer la Política Pública de Seguridad Vial (PNSV) con herramientas de articulación basadas en la evidencia más simple y contundente de los datos existentes. Dejemos de ser adivinos; seamos analistas de datos para salvar vidas. 

### Objetivo general

Articular y analizar de forma básica e inmediata los datos abiertos de siniestralidad (Accidentes y Puntos Críticos) y de registro vehicular (Parque Automotor) para generar perfiles de riesgo específicos que permitan la focalización territorial y temática de las estrategias de seguridad vial, garantizando el uso eficiente de los recursos y el cumplimiento de los ejes de acción del PNSV (Infraestructura, Vehículos y Cultura Ciudadana).

### Objetivos especificos

- **OE1.** Focalización de Infraestructura y Vehículos: Crear una matriz de cruce de datos (Mortalidad Crítica y Parque Automotor) que permita identificar y jerarquizar los tramos viales donde la combinación de alta siniestralidad con la tipología o antigüedad de los vehículos matriculados exige la intervención prioritaria de la infraestructura vial y el control técnico-mecánico.
- **OE2.** Diseño de Comunicación de Corresponsabilidad: Utilizar la correlación simple de los tres conjuntos de datos para perfilar al actor vial de mayor riesgo (ej. motociclista joven, peatón adulto mayor, etc.) en cada sector crítico, como insumo directo para el diseño de estrategias de comunicación hiper-focalizadas que promuevan la cultura ciudadana y la corresponsabilidad.
- **OE3.** Ajuste de Programas de Habilidades y Destrezas: Identificar las causas de accidentalidad más recurrentes en los sectores críticos y asociarlas al tipo de vehículo y actor vial para reformular y dirigir los programas de formación, mejora de habilidades y destrezas del sector transporte (público y privado) a las necesidades de prevención más urgentes.
- **OE4.** Generación de Herramientas de Articulación PNSV: Desarrollar una herramienta de visualización sencilla (dashboard o mapa interactivo) que integre los resultados del análisis (puntos de riesgo, perfiles de actor/vehículo) para servir como insumo de articulación, planificación, ejecución y seguimiento de las estrategias del Plan Nacional de Seguridad Vial (PNSV) a nivel sectorial y territorial.
- **OE5.** Estandarización y Calidad de Datos: Identificar las variables clave necesarias de los tres conjuntos de datos para el análisis de riesgo y proponer un esquema básico de estandarización, periodicidad de actualización y mejoramiento de la calidad de los datos abiertos, asegurando su sostenibilidad para la toma de decisiones continua.

## Conjuntos de datos Utilizados

| Conjunto de datos | Enlace |
| - | - |
| ACCIDENTES DE TRANSITO DESDE MARZO 2017 A DICIEMBRE DE 2022 | [https://www.datos.gov.co/Transporte/ACCIDENTES-DE-TRANSITO-DESDE-MARZO-2017-A-DICIEMBR/wacd-xkg8/about_data](https://www.datos.gov.co/Transporte/ACCIDENTES-DE-TRANSITO-DESDE-MARZO-2017-A-DICIEMBR/wacd-xkg8/about_data) |
| Sectores críticos mortalidad 2022 | [https://www.datos.gov.co/Transporte/Sectores-cr-ticos-mortalidad-2022/ybqk-8s42/about_data](https://www.datos.gov.co/Transporte/Sectores-cr-ticos-mortalidad-2022/ybqk-8s42/about_data) |
| Vehículos matriculados desde enero de 2020 hasta mayo del 2022 por clase, modelo y tipo de vehículo | [https://www.datos.gov.co/Transporte/Veh-culos-matriculados-desde-enero-de-2020-hasta-m/bj7e-xc9g/about_data](https://www.datos.gov.co/Transporte/Veh-culos-matriculados-desde-enero-de-2020-hasta-m/bj7e-xc9g/about_data) |
| Homicidios accidente de tránsito Policía Nacional | [https://www.datos.gov.co/Seguridad-y-Defensa/Homicidios-accidente-de-tr-nsito-Polic-a-Nacional/ha6j-pa2r/about_data](https://www.datos.gov.co/Seguridad-y-Defensa/Homicidios-accidente-de-tr-nsito-Polic-a-Nacional/ha6j-pa2r/about_data). |
| VEHICULOS INVOLUCRADOS EN UN ACCIDENTE DE TRANSITO LEY 2251-2022 | [https://www.datos.gov.co/Transporte/VEHICULOS-INVOLUCRADOS-EN-UN-ACCIDENTE-DE-TRANSITO/6jmc-vaxk/about_data](https://www.datos.gov.co/Transporte/VEHICULOS-INVOLUCRADOS-EN-UN-ACCIDENTE-DE-TRANSITO/6jmc-vaxk/about_data). |
| LESIONES ACCIDENTES DE TRÁNSITO | [https://www.datos.gov.co/Seguridad-y-Defensa/LESIONES-ACCIDENTES-DE-TR-NSITO/ntej-qq7v/about_data](https://www.datos.gov.co/Seguridad-y-Defensa/LESIONES-ACCIDENTES-DE-TR-NSITO/ntej-qq7v/about_data) |





