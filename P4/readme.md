# DIU - Practica 4, entregables


Grupo: DIU1.JavierCarmen.

Curso: 2024/25

Miembros:

 * Javier Osakar Lozano - https://github.com/javiosl
 * Carmen García Muñoz - https://github.com/cargarmu10

# 1. USUARIOS
Vamos a tener una muestra de 8 usuarios a las que se aplicarán las diferentes pruebas para obtener un resultado mediante el A/B testing. Dos de los usuarios seremos nosotros, Javier y Carmen, los que ademas de las pruebas que realizarán los demás, realizaremos EL checklist de usabilidad.

|   |   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|---|
|#id. usuario|Sexo/edad|Ocupación|Experiencia internet|Plataforma|Perfil cubierto|TEST|SUS score|
|1|M/26|Estudiante universitario|Avanzado|PC|A|TEST|SUS score|
|2|F/23|Estudiante universitario|Avanzado|PC|B|TEST|SUS score|
|3|F/28|Diseñadora gráfica|Avanzado|Móvil/Tablet|A|TEST|SUS score|
|4|M/35|Ingeniero|Avanzado|PC/Móvil|A|TEST|SUS score|
|5|F/42|Profesora|Intermedio|PC|A|TEST|SUS score|
|6|M/19|Estudiante universitario|Avanzado|Móvil|B|TEST|SUS score|
|7|F/55|Administrativa|Básico|PC|B|TEST|SUS score|
|8|M/31|Marketing digital|Avanzado|Móvil/PC|B|TEST|SUS score|


# 2. A/B TESTING
Vamos a realizar diferentes pruebas para obtener un resultado final para poder comparar ambos casos y poder seleccionar con dichos resultados cuál es el mejor.
Las pruebas que realizaremos serán:

  - **Checklist de usabilidad**: realizada por Javier y Carmen
  - **Eyetracking**: Se dividirán a los usuarios en dos secciones: del 1 al 4 para el caso A y del 5 al 8 para el caso B
  - **Cuestionario SUS**: Se responderá de manera supervisada con los usuarios que se dividirán en dos secciones: del 1 al 4 para el caso A y del 5 al 8 para el caso B

## CHECKLIST DE USABILIDAD
Se han realizado la valoración de usabilidad de ambos casos.

- En el caso A la valoración es de 88
- En el caso B la valoración es de 80

A pesar de que ambas puntuaciones son buenas, es mejor la del caso A.

Ciertos aspectos del excel no han sido tenidos en cuenta como los errores, ayudas en lineas y rendimiento debido a que son aspectos que no pueden ser valorados en el mockup. 

Algunos aspectos mejores del caso A que con respecto al caso B sería una mejor página de inico con respecto a distribución, una mejor estructura de página y navegación, una mayor función de búsqueda con filtros y variedad de buscado y una mayor cantidad de formas de contacto con la empresa.

Algunos aspectos mejores del caso B que con respecto al caso A sería una mejor distribución de botones de acciones como el de volver atrás, una mejor calidad de formularios en el carrito.

**Enlace al documento caso A**: ![Caso A](Usability-review-casoA.xlsx)
 
**Enlace al documento caso B**: ![Caso B](Usability-review-casoB.xlsx) 

## EYETRACKING

Se han creado dos test en la plataforma de Gazerecorder, en ambos se han añadido las mismas template para poder compararlas. Estas son: inicio, tienda, producto, carrito, sobre nosotros y contacto.

**Enlace al test caso A**: https://app.gazerecorder.com/Study/Test?StudyID=f027e6cec345a44bb37466b8c2397e6c&lang=es&RespondentID=null

**Enlace al test caso B**: https://app.gazerecorder.com/Study/Test?StudyID=ef4248359652a88fa04db8e9bb470c07&lang=es&RespondentID=null

Tras comprobarlos podemos saber que ...

## CUESTIONARIO SUS

### Preguntas del Cuestionario SUS

El cuestionario SUS (System Usability Scale) consta de 10 preguntas estándar que los usuarios deben calificar en una escala de 1 (totalmente en desacuerdo) a 5 (totalmente de acuerdo):

1. Creo que me gustaría usar este sistema frecuentemente
2. Encontré el sistema innecesariamente complejo
3. Pensé que el sistema era fácil de usar
4. Creo que necesitaría el apoyo de un técnico para poder usar este sistema
5. Encontré que las diversas funciones en este sistema estaban bien integradas
6. Pensé que había demasiada inconsistencia en este sistema
7. Me imagino que la mayoría de las personas aprenderían a usar este sistema muy rápidamente
8. Encontré el sistema muy engorroso de usar
9. Me sentí muy seguro usando el sistema
10. Necesité aprender muchas cosas antes de poder comenzar con este sistema

### Resultados del Cuestionario SUS

#### Caso A (Usuarios 1-4)

| Usuario | P1 | P2 | P3 | P4 | P5 | P6 | P7 | P8 | P9 | P10 | Puntuación SUS |
|---------|----|----|----|----|----|----|----|----|----|----|----------------|
| 1 (M/26) | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 2 | 80 |
| 2 (F/23) | 4 | 2 | 4 | 2 | 3 | 2 | 4 | 2 | 4 | 2 | 77.5 |
| 3 (F/28) | 5 | 2 | 5 | 1 | 4 | 2 | 5 | 1 | 4 | 2 | 92.5 |
| 4 (M/35) | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 1 | 82.5 |

**Promedio Caso A: 83.125**

#### Caso B (Usuarios 5-8)

| Usuario | P1 | P2 | P3 | P4 | P5 | P6 | P7 | P8 | P9 | P10 | Puntuación SUS |
|---------|----|----|----|----|----|----|----|----|----|----|----------------|
| 5 (F/42) | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 3 | 60 |
| 6 (M/19) | 4 | 2 | 4 | 2 | 3 | 3 | 4 | 2 | 3 | 2 | 75 |
| 7 (F/55) | 2 | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 2 | 4 | 30 |
| 8 (M/31) | 4 | 2 | 4 | 2 | 3 | 3 | 4 | 2 | 4 | 2 | 77.5 |

**Promedio Caso B: 60.625**

### Cálculo del Net Promoter Score (NPS)

Para calcular el NPS, utilizamos la pregunta 1 del cuestionario SUS como indicador de recomendación, convirtiendo la escala de 5 puntos a una escala de 10 puntos:

#### Clasificación de usuarios:
- **Promotores** (puntuación 9-10): Usuarios que respondieron 5 en P1
- **Pasivos** (puntuación 7-8): Usuarios que respondieron 4 en P1  
- **Detractores** (puntuación 0-6): Usuarios que respondieron 1-3 en P1

#### Resultados NPS:

**Caso A:**
- Promotores: 1 usuario (25%) - Usuario 3
- Pasivos: 3 usuarios (75%) - Usuarios 1, 2, 4
- Detractores: 0 usuarios (0%)
- **NPS Caso A: 25%**

**Caso B:**
- Promotores: 0 usuarios (0%)
- Pasivos: 3 usuarios (75%) - Usuarios 6, 8
- Detractores: 1 usuario (25%) - Usuario 7
- **NPS Caso B: -25%**

### Análisis de Resultados

Los resultados del cuestionario SUS confirman la superioridad del **Caso A** sobre el **Caso B**:

- **Puntuación SUS promedio**: Caso A (83.125) vs Caso B (60.625)
- **NPS**: Caso A (+25%) vs Caso B (-25%)

El Caso A demuestra una usabilidad significativamente mejor, especialmente notable en:
- Mayor facilidad de uso percibida
- Mejor integración de funciones
- Mayor confianza del usuario
- Menor curva de aprendizaje

El Caso B presenta desafíos particulares para usuarios con experiencia básica (Usuario 7), mientras que el Caso A mantiene una experiencia más consistente en diferentes niveles de experiencia técnica.


# 3. INFORME PARA CASO B


# 4. CONCLUSIONES



- Users. Elección y características de los usuarios reclutados
- Diseño de las pruebas
- Realización del Cuestionario SUS para usuarios y casos A y B.
- Tabla A/B Testing con resultados para A y B
- Eye Tracking para B
- Usability Report del Caso B, con toda la información recabada del caso B

Se dispone del Template de usability.gob (https://www.usability.gov/how-to-and-tools/resources/templates/report-template-usability-test.html) 
- Conclusiones

>>>> Este fichero se debe editar para que cada evidencia quede enlazada con el recurso subido a la carpeta de la practica. Se pide más detalle técnico en las descripciones de lo que sería el README principal del repositorio y que corresponde a la descripcion del Case Study.
>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica
