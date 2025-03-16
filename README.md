# DIU25
Prácticas Diseño Interfaces de Usuario (Tema: Mercados Ecológicos) 

[Guiones de prácticas](GuionesPracticas/)

Grupo: DIU1.JavierCarmen.  Curso: 2024/25 

Actualizado: 16/03/2025

Proyecto: EcoSierra Granada

Descripción: 

Se trata de una plataforma digital (web y móvil) que conecta a productores, vendedores y consumidores de mercados ecológicos en Granada. La propuesta se centra en:

- **Envíos Ecoamigables:**  
  No se usa plástico en los envíos. Se utilizan cajas de madera reciclada. Además, si el usuario devuelve el envase, se le ofrece un pequeño descuento en su siguiente compra.  

- **Transporte Sostenible:**  
  Todos los medios de transporte (camiones, camionetas y motos) que se utilizan para la distribución son eléctricos, reduciendo así la huella de carbono.

- **Funcionalidades del Marketplace:**  
  La plataforma permite realizar pedidos en línea con métodos de pago de forma segura. Además, incorpora funcionalidades como el seguimiento de envíos y acceso a reseñas de otros usuarios.

Logotipo: 

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 300 100">
    <rect width="300" height="100" fill="#ffffff"/>
    <!-- Ícono: círculo que simboliza la sostenibilidad y lo ecológico -->
    <circle cx="50" cy="50" r="30" fill="#6DBE45"/>
    <!-- Texto del logotipo -->
    <text x="100" y="60" font-family="Arial, sans-serif" font-size="36" fill="#333333">EcoSierra</text>
</svg>

Slogan: De la sierra a tu mesa

Miembros:
 * Javier Osakar Lozano - https://github.com/javiosl
 * Carmen García Muñoz - https://github.com/cargarmu10

----- 

>>> Este documento es el esqueleto del Case Study que explica el proceso de desarrollo de las 5 prácticas de DIU. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. Elimine este tipo de texto / comentarios desde la práctica 1 conforme proceda a cada paso


# Proceso de Diseño 

<br>

## Paso 1. UX User & Desk Research & Analisis 

### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

#### 1. Background

Este proyecto se centra en la mejora de la experiencia digital para mercados ecológicos en Granada, España. La investigación busca comprender las necesidades, motivaciones y barreras de los usuarios para diseñar una interfaz que conecte de manera efectiva a consumidores, vendedores, organizadores y promotores publicistas.

#### 2. Objectives

Business Objective & KPIs:
- Incrementar la adopción digital de los mercados ecológicos locales.
- KPIs: Tasa de participación, satisfacción del usuario, y tasa de conversión en acciones (por ejemplo, registro o compra).

Research Success Criteria:

- Recopilar información cualitativa (entrevistas, observaciones) y cuantitativa (cuestionarios).
- Crear documentos como perfiles de usuario, mapas de experiencia y recomendaciones de diseño.
- Fundamentar decisiones de diseño basadas en los insights obtenidos.

#### 3. Research Methods

Se realizará la investigación mediante entrevistas presenciales, observación (etnografía) y contextual inquiry. Esto nos ayuda a connocer las experiencias y expectativas de cada perfil, ayudando a identificar las áreas de mejora en la interfaz.

#### 4. Research Scope & Focus Areas

Question Themes:

Motivaciones y barreras para acudir a mercados ecológicos.
Impacto de la comunicación y promoción en la decisión de compra.

Design Focus Components: Utility, Learnability, Efficiency, Memorability, Errors, Satisfaction, Persuasiveness.

#### 5. (Personal) Experiencia en este campo

- Como stakeholder: Experiencia participando en iniciativas ecológicas.
- Como diseñador: Antecedentes en proyectos centrados en el usuario y sostenibilidad.
- Como observador: Visitas a mercados ecológicos locales.
- User says: Comentarios recogidos de usuarios y promotores sobre la experiencia actual.

#### 6. Reclutamiento de participantes

Se reclutarán al menos tres perfiles:

- Consumidores: Personas que frecuentan o tienen interés en adquirir productos ecológicos.
- Vendedores/Organizadores: Encargados de gestionar los mercados y asegurar la calidad de los productos.
- Promotores (Publicistas): Encargados de impulsar la imagen y alcance de los mercados ecológicos.

### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----
![Método UX](P1/CompetitorAnalysis.png) 

### 1.c Personas
![Método UX](img/Persona.png) 
-----
![Método UX](P1/Persona_1.png) 
**María Fernández**: Madre de tres hijos y se preocupa especialmente por la salud de uno de ellos, que tiene problemas de salud delicados. Trabaja como enfermera, lo que le hace reflexionar sobre la importancia de una alimentación sana y natural. Siempre busca alternativas que le permitan cuidar a su familia con productos de calidad, libres de transgénicos y respetuosos con el medio ambiente.

![Método UX](P1/Persona_2.png) 
**Antonio Ruiz**: Tras muchos años trabajando en el campo y cultivando su propia huerta, se ha mudado a la ciudad para estar más cerca de sus nietos. Aunque echa de menos el campo, quiere mantener su estilo de vida saludable y ecológico. Su experiencia en agricultura y el conocimiento de cultivo tradicionales lo hacen muy exigente en la calidad de los productos.

### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----
Los dos User Journey son situaciones comunes en la página web de www.valleyvega.org, en las que se intenta buscar un alimento y comprarlo. Ambas situaciones son increiblemente engorrosas y están mal diseñadas, con cantidad de fallos en todos los pasos del proceso.

A nuestra usuaria María Fernández le han recomendado comprar una variedad específica de aceitunas y no las ha podido encontrar mediante la búsqueda que supuestamente indexa todo el contenido de la web.
![Método UX](P1/User_Journey_Map_1.png)
A nuestro usuario Antonio Ruiz ha decidido realizar una compra de acelgas para su familia pero debido a un error poco intuitivo no ha sido capaz de conseguirlo y tuvo que pedir ayuda a un familiar más joven.
![Método UX](P1/User_Journey_Map_2.png)

### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----
- **Enlace al documento**: ![Método UX](P1/Usability-review.xlsl) 
- **URL y Valoración numérica obtenida**: www.valleyvega.org / www.tienda.valleyvega.org - 60/100
- **Comentario sobre la revisión**:  Las web principal y tienda son webs diferentes y a la tienda es engorroso acceder, demostrando poca organización y coherencia en la estructura. La tienda contiene una serie de secciones mal organizadas y una búsqueda mal indexada con alimentos disponibles mediante las secciones pero no la búsqueda, algo completamente incomprensible. El checkout es engorroso y el precio mínimo no está bien clarificado. Por lo demás la web presenta un diseño atractivo con una paleta de colores agradable y una tipografía clara y legible.

<br>

## Paso 2. UX Design  

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento

### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----

>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior. De qué carece la competencia?? Tu diagrama puede ser una figura subida a la carpeta P2/


 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas
  
    
>>> Explica el Problema y plantea una hipótesis. Es decir, explica aquí qué 
>>> se plantea como "propuesta de valor" para un nuevo diseño de aplicación propio


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

>>> Propuesta de valor, pero ahora en vez de un texto es un ScopeCanvas que has subido a P2/ y enlazado desde aqui. Tambien vale una imagen miniatura del recurso.
>>> No olvides que tu propuesta ya tiene un nombre corto y puedes actualizar la cabecera de este archivo



### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

>>> Definir "User Map" y "Task Flow" ... enlazar desde P2/ y describir brevemente


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

>>> Identificar términos para diálogo con usuario (evita el spanglish) y la arquitectura de la información. Es muy apropiado un diagrama tipo sitemap y una tabla que se ampliaría para llevar asociado la columna iconos (tanto para la web como para una app). 

Término | Significado     
| ------------- | -------
  Login  | acceder a plataforma


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

>>> Plantear el diseño del layout para Web/movil (organización y simulación). Describa la herramienta usada 

<br>

## Paso 3. Mi UX-Case Study (diseño)

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

>>> Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo. Todos los recursos estarán subidos a la carpeta P3/
>>> Explique aqui la/s herramienta/s utilizada/s y el por qué de la resolución empleada. Reflexione ¿Se puede usar esta imagen como cabecera de Instagram, por ejemplo, o se necesitan otras?


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

>>> Plantear el Landing Page del producto. Aplica estilos definidos en el moodboard


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 


### 3.d Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders


### 3.e ¿My UX-Case Study?
![Método UX](img/caseStudy.png) 
-----

>>> Publicar my Case Study en Github... Es el momento de dejar este documento para que sea evaluado y calificado como parte de la práctica
>>> Documente bien la cabecera y asegurese que ha resumido los pasos realizados para el diseño de su producto

<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




