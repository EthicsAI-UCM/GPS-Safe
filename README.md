# GPS SAFE

<code> GIDIA - Ética de Datos e Inteligencia Artificial </code>

>  "La ética no consiste en frenar el progreso, sino en dirigirlo."
>
>   — Kant (interpretación)


## Model Card y Anexos
Para entender completamente el contexto, el desarrollo, y la documentación técnica de este proyecto, consulte los siguientes recursos:


| Documento | Título del Anexo | Descripción | Enlace |
| :--- | :--- | :--- | :--- |
| **📄 Model Card** | Model Card | Documento principal que ayuda a entender de forma general como funciona el modelo | [Ir a la Model Card](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/Model%20Card.pdf) |
| **📚 Anexo 1** | Casos de uso previstos y no previstos | Define el propósito principal, los perfiles de usuario, y las restricciones formales. | [Ir al Anexo 1](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%201%20Casos%20de%20uso%20previstos%20y%20no%20previstos.pdf) |
| **📚 Anexo 2** | Datos y Entrenamiento del sistema | Detalla las fuentes de datos, criterios de calidad e impacto ambiental del entrenamiento. | [Ir al Anexo 2](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%202%20Datos%20y%20Entrenamiento%20del%20sistema.pdf) |
| **📚 Anexo 3** | Evaluación y métricas | Explica los ejes de evaluación, métricas técnicas y los umbrales críticos de despliegue (precisión >95%, FN <1%). | [Ir al Anexo 3](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%203%20Evaluaci%C3%B3n%20y%20m%C3%A9tricas.pdf) |
| **📚 Anexo 4** | Privacidad y protección de datos | Detalla el cumplimiento del RGPD, el manejo de datos sensibles y las medidas de encriptación y anonimización. | [Ir al Anexo 4](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%204%20Privacidad%20y%20protecci%C3%B3n%20de%20datos.pdf) |
| **📚 Anexo 5** | Propiedad intelectual y modelo de apertura | Define el régimen de licencias y el modelo de negocio. | [Ir al Anexo 5](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%205%20Propiedad%20intelectual%20y%20modelo%20de%20apertura.pdf) |
| **📚 Anexo 6** | Marco de Riesgos, Límites Operacionales y Gobernanza | Describe los riesgos críticos, las Líneas Rojas éticas y el poder de veto del Comité Ético. | [Ir al Anexo 6](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%206%20Marco%20de%20Riesgos%2C%20L%C3%ADmites%20Operacionales%20y%20Gobernanza.pdf) |
| **📚 Anexo 7** | Usuarios, sesgos y colectivos afectados | Detalla la degradación de rendimiento en colectivos y los compromisos de diseño para la equidad. | [Ir al Anexo 7](https://github.com/EthicsAI-UCM/GPS-Safe/blob/main/ANEXO%207%20Usuarios%2C%20sesgos%20y%20colectivos%20afectados.pdf) |


## 1. Descripción del proyecto

GPS Safe es una aplicación de navegación inteligente que te ayuda a llegar a casa de la forma más rápida y segura. Utiliza inteligencia artificial (IA) para analizar datos en tiempo real —como reportes de incidentes, tráfico, iluminación o comportamiento del usuario— y predecir el nivel de riesgo de cada ruta. De este modo, la app no solo optimiza el trayecto por tiempo, sino también por seguridad, ofreciendo rutas personalizadas y alertas preventivas. 

> Su objetivo es convertir la movilidad urbana en una experiencia más confiable, responsable y conectada con las necesidades reales de las personas.



## 2. Control de versiones

Cada una de las versiones del proyecto aquí recogidas se ha desarrollado durante un Sprint distinto, cada Sprint con una duración de dos semanas. Para más detalle sobre estos Sprints (las fechas; la planificación, la revisión y la retrospectiva; el product backlog con las tareas etiquetadas por tamaño, peso y persona/s asignada/s), ver la [Wiki](https://github.com/EthicsAI-UCM/GPS-Safe/wiki) del proyecto. Estas versiones son acumulativas e iterativas: cada nueva versión amplía o refina las funcionalidades de la anterior, manteniendo su base y mejorando progresivamente el sistema.

```📑 Especificacion_v0.pdf```

En esta versión cero, se tratan aspectos superficiales como quiénes son los integrantes del grupo, cuál es el proyecto a abordar (nombre, definición, ámbito, uso de IA, actores, innovación, riesgos, etc.) y cómo va a estar organizado (formas de comunicación, superación de debilidades personales, team building, etc.).

```📑 Especificacion_v1.pdf```

En esta primera versión, se profundiza en aquellos temas que causaron interés o controversia en el debate de la versión anterior, como la privacidad, evaluación de riesgos, usos indebidos... Se incluyen dos anexos en los que se desarrollan a conciencia estos puntos. En esencia, se detallan ciertos aspectos del proyecto para reforzar su funcionamiento, seguridad y ética. 

```📑 Especificacion_v2.pdf```

En esta segunda versión, se vuelven a tratar los temas que causaron mayor interés o controversia en el debate de la versión anterior. Además, se introducen el análisis de riesgos y límites del proyecto, así como una definición de la propiedad intelectual del mismo. Ambos temas se han tratado con mayor profundidad y están plasmados en los dos anexos adjuntos a la memoria principal. En esencia, se sigue aumentando el tamaño del proyecto con nuevas especificaciones, esta vez, para consolidarlo técnicamente.

```📑 Especificacion_v3.pdf```

*En progreso...*


## 3. Prototipo conceptual 

Para transformar la idea de GPS-Safe en algo visible y comprensible, desarrollamos un primer prototipo conceptual. Este *mock-up* muestra la estructura básica de la aplicación y una interfaz inicial, lo que nos permite validar el concepto, recoger comentarios y orientar los siguientes pasos del desarrollo.

**Visualización previa de la app** *(Diseño inicial y flujo principal)* [Ver prototipo en Canva](https://www.canva.com/design/DAG2FMkn63Q/IrMF0guvsO35Kviok0BNKw/view?utm_content=DAG2FMkn63Q&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=he84d66c04d)

### Explicabilidad por capas  

Además, para garantizar transparencia y confianza, incorporamos un sistema de explicabilidad en varios niveles, adaptado a las necesidades de cada tipo de usuario. Esta estructura permite entender cómo decide la IA y facilita un uso responsable.

- **A nivel de usuario** *(Explicaciones simples y accionables sobre por qué se recomienda una ruta)*: [Ver explicación por capas - Usuario](https://www.canva.com/design/DAG4xBGh7dI/gHNBcctG5l8QT4iYjO1mzg/view?utm_content=DAG4xBGh7dI&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h2cf2b3e517)
- **A nivel de auditoría** *(Detalles técnicos y criterios de revisión para garantizar seguridad, ética y ausencia de sesgos)*: [Ver explicación por capas - Auditoría](https://www.canva.com/design/DAG4xvKp2d8/6j1FU8-b0V8-JX9KGNS57Q/view?utm_content=DAG4xvKp2d8&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h642127c5eb)



## 4. Crédito y roles

Integrantes del equipo *GPS-Safe*:

- Mario Baldocchi
- Pablo Manuel Rodríguez Sosa
- Carlota Salazar Martín
- Artem Vartanov
- Yushan Yang Xu

### Asignación de roles

|Rol | Miembro | Breve descripción |
|----|---------|-------------------|
| *Scrum Master*| **Carlota** Salazar Martín | Responsable de seguir la metodología Scrum |
| *Product Owner* | **Pablo** M. Rodríguez Sosa | Responsable de que el grupo haga el trabajo productivo requerido |
| *Experto Git* | **Artem** Vartanov | Responsable de apoyar el uso de Git y Github y resolver dudas al respecto |
| *Team Advocate* | **Yushan** Yang | Responsable de defender y cuidar al grupo |



## 5. Protocolo *commits* en GitHub

Con el fin de unificar criterios, los *commits* en GitHub se escribirán en castellano como lengua imperante, y se ceñirán a las siguientes reglas (*Durán, M. Á. (2021, 22 de julio). Buenas prácticas para escribir commits en Git. Midudev.*):

1. Se usará el verbo imperativo ("actualizar", "eliminar", "añadir", "crear"...)
2. No se usará punto final ni puntos suspensivos en los mensajes
3. Se usarán como máximo 50 carácteres para el mensaje de commit
4. Se añadirá todo el contexto que sea necesario en el cuerpo del mensaje de commit



## 6. Referencias

**Importante:** Las referencias serán escritas en formato APA (7ª edición).

- *Maidana, G. (2023, 10 de noviembre). Waze, la app de tránsito ahora da alertas sobre rutas peligrosas y su historial de accidentes. Perfil – Modo Fontevecchia.* https://www.perfil.com/noticias/modo-fontevecchia/waze-la-app-de-transito-ahora-da-alertas-sobre-rutas-peligrosas-y-su-historial-de-accidentes-modof.phtml

- *Khandakar, A., Michelson, D.G., Naznine, M. et al. Harnessing Smartphone Sensors for Enhanced Road Safety: A Comprehensive Dataset and Review. Sci Data 12, 418 (2025).* https://www.nature.com/articles/s41597-024-04193-0

- *Campo Yanguas, L. (2025, 8 de septiembre). Adiós a los robos en la calle: este es el dispositivo superventas de Amazon que te ayuda a evitarlos. El País – Escaparate: Estilo de vida.* https://elpais.com/escaparate/estilo-de-vida/2025-09-08/alarma-personal.html

- *Yoigo Alarmas. (2024, 4 de octubre). Descubre cuáles son los 10 barrios más peligrosos de Barcelona. Yoigo Alarmas Blog.* https://yoigoalarmas.es/blog/descubre-cuales-son-10-barrios-mas-peligrosos-barcelona

- *Citizen. (n.d.). Citizen App – Urban Safety Platform. Citizen.* https://citizen.com

- *SafeGraph. (n.d.). The ultimate guide to mobility data: Sources, benefits, and applications. SafeGraph Guides.* https://www.safegraph.com/guides/mobility-data

- *Hontoria, N. (2025, 6 de agosto). Hay algo que echo de menos en Google Maps: no es capaz de evitar las zonas más inseguras. Xataka Android.* https://www.xatakandroid.com/navegacion-y-mapas/hay-algo-que-echo-google-maps-no-capaz-evitar-zonas-inseguras-ia-tampoco-sabe-como-ayudarme

- *Wood, M. (2022, June 30). Algorithm predicts crime a week in advance, but reveals bias in police response. The University of Chicago – Biological Sciences Division.* https://biologicalsciences.uchicago.edu/news/algorithm-predicts-crime-police-bias

- *Durán, M. Á. (2021, 22 de julio). Buenas prácticas para escribir commits en Git. Midudev.* https://midu.dev/buenas-practicas-escribir-commits-git/

- *Syndicated Maps. (2025, August 22). Why Google Maps doesn’t show you unsafe areas.* https://blog.syndicatedmaps.com/2025/08/why-google-maps-doesnt-show-you-unsafe.html

 - *AP News. (2025, October). The danger of false trails: How non-existent hiking routes on Google Maps can lead to disaster.*
https://apnews.ca/article/the-danger-of-false-trails-how-non-existent-hiking-routes-on-google-maps-can-lead-to-disaster/

- *Sharma, V., Kulshreshtha, R., Singh, P., Agrawal, N., & Kumar, A. (2015). Analyzing newspaper crime reports for identification of safe transit paths. In Proceedings of the NAACL-HLT 2015 Student Research Workshop (SRW) (pp. 17–24). Association for Computational Linguistics.* https://aclanthology.org/N15-2003.pdf

- *Berhanu, Y., Schröder, D., Wodajo, B. T., & Alemayehu, E. (2024). Machine learning for predictions of road traffic accidents and spatial network analysis for safe routing on accident and congestion-prone road networks. Results in Engineering, 21, 101021. Elsevier.* https://www.sciencedirect.com/science/article/pii/S2590123024009927
- Zuboff, S. (2019). *La era del capitalismo de la vigilancia: La lucha por un futuro humano en la nueva frontera del poder*. Paidós.
  
- O'Neil, C. (2017). *Armas de destrucción matemática: Cómo el big data aumenta la desigualdad y amenaza la democracia*. Capitán Swing.


