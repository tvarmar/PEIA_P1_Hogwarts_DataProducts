# Unidad Didáctica 1, 2, 3:
## 1. Objetivo
La retroalimentación consiste en una respuesta verbal, escrita o gestual por parte del docente con relación al desempeño o comportamiento de un estudiante. Su objetivo es potenciar al estudiante para que obtenga buenas calificaciones confiando en sus capacidades para resolver un problema. El diseño de estos módulos pretende exponer al estudiante a un escenario de equipos de trabajo realizando proyectos de inteligencia artificial.
## 2. Enunciado
El Ministerio de Magia ha iniciado una inspección detallada de los Data Products implementados en los distintos departamentos de la Escuela de Magia y Hechicería de Hogwarts. Esta revisión busca asegurar que cada recurso digital esté en línea con las regulaciones del mundo mágico, promoviendo un manejo de datos eficaz, seguro y en cumplimiento con los estándares de la comunidad mágica.
A lo largo del año, el Ministerio ha llevado a cabo tomas trimestrales para evaluar el estado de los Data Products y observar su evolución en el tiempo. Estas tomas trimestrales se encuentran documentadas en tres datasets que encontrarás junto este entregable.
Tu objetivo como funcionario del Ministerio de Magia es elaborar un reporte en formato notebook (los magos son muy quisquillosos en esto), donde se respondan unas preguntas de negocio de magia.
## 3. Fuente de datos
Los datos los tenéis disponibles en este enlace:
`Hogwards - 2024xT.zip`
Éste es el esquema:
| Columna | Descripción | Ejemplo |
|-|-|-|
| ID | Identificador único del Data Product, en formato
"DPXXX". | DP001 |
| Name | Nombre breve del Data Product sin espacios. | TrackHechizo |
| Descriptive Name | Nombre descriptivo y expandido del Data Product. | Sistema de Seguimiento de Hechizos |
| Description | Breve descripción del Data Product y su contexto de uso en Hogwarts. | Data Product relacionado con encantamientos, utilizado en Hogwarts. |
| Domain | Dominio o departamento de Hogwarts al que pertenece el Data Product. | Defensa Contra las Artes Oscuras |
| Owner | Nombre del responsable del Data Product, específico del dominio. | Severus Snape |
| IsCompliance | Valor booleano que indica si el Data Product cumple con los estándares de compliance del Ministerio. | True |
| Status | Estado del Data Product (Development, Planned, Production, Deprecated). | Production |
| Version | Versión del Data Product en formato "x.x.x". | 1.0.0 |
| NumberUsers | Número de usuarios que interactúan con el Data Product, entre 0 y 100. | 75 |
## 4. Ejecución
Para cumplir con los rigurosos estándares del Ministerio de Magia y brindar claridad en la inspección de los Data Products de Hogwarts, deberás entregar un informe en formato notebook. Este informe estará estructurado en dos partes muy definidas:
- Primera Parte: Aquí va todo el código y las transformaciones necesarias para el análisis. Piensa en esto como el "backstage" de tu hechizo, donde muestras los pasos para llegar a los resultados. Asegúrate de que esté todo bien comentado, ¡no queremos que ningún mago se pierda en la bruma del código!
- Segunda Parte: La magia hecha realidad. En esta sección presentas los resultados en tablas y gráficos claros. Recuerda que el Ministerio aprecia la simplicidad: todo debe estar pensado para que incluso el más despistado de los magos entienda los resultados sin lanzar un encantamiento de aclaración.
### Preguntas de Negocio que el Ministerio quiere resolver
El Ministerio tiene una serie de preguntas clave que necesita responder. ¡Están en juego la seguridad y el buen funcionamiento de los Data Products mágicos! Los temas que debes abordar son los siguientes:
-  Estado actual de los Data Products:
  - ¿Cuántos Data Products existen actualmente? Desglosa esta información por dominio y estado. Queremos saber qué áreas de Hogwarts están mejor (y peor) preparadas.
- Análisis trimestral de los Data Products en estado "Planned" o "Production":
  - ¿Cuántos de estos cumplen con las normas de compliance?
  - ¿Cuántos usuarios están utilizando estos Data Products en cada área?
  - ¿Cuál es el promedio de usuarios por área?
  - Y en aquellos que no cumplen con compliance, ¿cuántos usuarios tienen de todas formas? (¡Esto es importante para identificar posibles brechas de seguridad!).
- Análisis trimestral de los Data Products "Deprecated":
  - ¿Cuántos Data Products en estado "Deprecated" hay en cada dominio?
  - ¿Cuántos usuarios siguen conectados a estos Data Products que, oficialmente, ya no están en servicio?
- Análisis de los funcionarios (Owners) por cada trimestre:
  - ¿Cuántos funcionarios están trabajando, y cuántos Data Products (por estado) tienen asignados?
  - En cada dominio, ¿quiénes son los tres Owners con más usuarios en sus Data Products en estado "Planned" o "Production"?
  - Por otro lado, ¿quién es el Owner menos productivo en cada dominio? Esto significa que tiene el mayor porcentaje de Data Products en estado "Deprecated" sobre el total que le han asignado. Si hay empate, ¡queremos saber todos los nombres!
  - Y finalmente, debido a la importancia de la ubicuidad, ¿hay algún funcionario que esté trabajando en varios dominios a la vez? El Ministerio quiere saber si tiene a algún mago "polifacético" en su equipo. 
### Visualizaciones Esperadas
No puede faltar una pizca de magia visual en el informe. Las gráficas que espera el Ministerio son:
- Gráfica de Data Products actuales por dominio y su estado.
- Evolución temporal del número de usuarios de Data Products en producción.
- Evolución temporal de Data Products totales frente a aquellos que cumplen con compliance.
- Evolución temporal del número de Owners por dominio.
Recuerda, el Ministerio de Magia no solo valora el contenido del informe, sino también la claridad y facilidad de interpretación de los resultados. Cada gráfico, tabla y explicación debe ser tan claro como un hechizo bien ejecutado.
