# DIU - Practica 3, entregables

- Moodboard (diseño visual + logotipo)   
- Landing Page
- Mockup: LAYOUT HI-FI
- Publicación del Case Study

## Conclusiones

>>>> Este fichero se debe editar para que cada evidencia quede enlazada con el recurso subido a la carpeta de la practica. Se pide más detalle técnico en las descripciones de lo que sería el README principal del repositorio y que corresponde a la descripcion del Case Study.
>>>> Termine con la seccion de Conclusiones para aportar una valoración final del equipo sobre la propia realización de la práctica

# POR HACER:

(Todo con animaciones y adaptado a móvil usando materialUI plugin)

- ONBOARDING - Javi
- NAVBAR - Faltan animaciones - Javi
- HERO IMAGE + CAROUSEL Falta animación carrousel - Javi
- SEARCH - Faltan animaciones (tienda y productos) - Javi
- WIZARDS (explain process) - Javi
- ARTICLE LIST - Faltan animaciones scroll - Javi
- ITEM DETAILS + ACTIONS - Faltan animaciones - Javi
- FORM INPUT (Contacto) - Falta - Carmen
- SHOPPING CART - Falta - Carmen
- ABOUT (Sobre Nosotros) - Falta - Carmen
- RESPONSIVE AL FINAL
- Si da tiempo hacer BLOG

# DIU - Practica 3

Grupo: DIU1.JavierCarmen.  Curso: 2024/25
Miembros:
 * Javier Osakar Lozano - https://github.com/javiosl
 * Carmen García Muñoz - https://github.com/cargarmu10

# 1. MOODBOARD

## LOGOTIPO

- Imagen .png
![Logotipo](LOGO.png)

- Vectorial .svg
![Logotipo](LOGO.svg)

Hemos querido elegir un logotipo simple y directo, compuesto con el color verde como color principal, muy representativo de lo natural y ecológico, y el texto del nombre de la marca. La tipografía es sencilla y clara, para que sea fácil de leer y recordar y sobre todo de usar en plataformas web y móviles.


## PALETA DE COLORES

![Paleta de Colores](PALETA_COLORES.png)

| Muestra | Nombre                | Hex       | Uso / Justificación                                                                                         |
|:-------:|:----------------------|:----------|:-------------------------------------------------------------------------------------------------------------|
| 🟩      | **Verde Natural**     | `#78C043` | Color principal, tomado del logo. Evoca naturaleza, frescura y ecología.                                     |
| 🟫      | **Madera Reciclada**  | `#8B6F47` | Acento que recuerda las cajas de madera reciclada. Aporta calidez y refuerza el concepto “eco‐packaging”.     |
| 🟦      | **Azul Claro**        | `#66B2E8` | Color secundario para llamadas a la acción o elementos de tracking; ofrece sensación de confianza y tecnología. |
| ⚫️      | **Gris Carbón**       | `#333333` | Para texto y elementos UI; alto contraste y buena legibilidad sobre fondos claros.                          |
| ⚪️      | **Crema Suave**       | `#F5F5F2` | Fondo general; proporciona calidez y hace que los productos destaquen sin “cansar” la vista.                 |


## ICONOS/SÍMBOLOS Y ESTILO (HeroIcons)

### Estilo general

| Propiedad        | Valor                                  |
|:-----------------|:---------------------------------------|
| **Familia**      | Outline / Stroke                       |
| **Grosor**       | 2 px                                   |
| **Line cap/join**| Round                                  |
| **Tamaño base**  | 24 × 24 px (32 × 32 px en heroicons)   |
| **Color normal** | `#333333` (Gris Carbón)               |
| **Color hover**  | `#78C043` (Verde Natural)             |

---

### Iconos de navegación y acciones globales

| Uso                | Icono                                                                                                                                                                                         |
|:-------------------|:----------------------------------------------------------------------------------------------------|
| Menú hamburguesa   | <img src="https://unpkg.com/feather-icons/dist/icons/menu.svg" width="24" height="24" /> |
| Carrito de compra  | <img src="https://unpkg.com/feather-icons/dist/icons/shopping-cart.svg" width="24" height="24" />    |
| Usuario / sesión   | <img src="https://unpkg.com/feather-icons/dist/icons/user.svg" width="24" height="24" />     |
| Selección de idioma| <img src="https://unpkg.com/feather-icons/dist/icons/globe.svg" width="24" height="24" />    |
| Buscar             | <img src="https://unpkg.com/feather-icons/dist/icons/search.svg" width="24" height="24" />   |
| Teléfono           | <img src="https://unpkg.com/feather-icons/dist/icons/phone.svg" width="24" height="24" />    |


### Iconos de filtro y ordenación (columna lateral)

| Filtro / Orden        | Icono                                                                                           | Estado activo     |
|:----------------------|:------------------------------------------------------------------------------------------------|:------------------|
| Desplegable           | <img src="https://unpkg.com/feather-icons/dist/icons/chevron-down.svg" width="24" height="24" /> | Rotar 180° (▲)    |
| Más vendidos          | <img src="https://unpkg.com/feather-icons/dist/icons/trending-up.svg" width="24" height="24" />  | Color `#78C043`   |
|


### Iconos de producto y carrito (detalle de producto)

| Acción            | Icono                                                                                             |
|:------------------|:--------------------------------------------------------------------------------------------------|
| Añadir al carrito | <img src="https://unpkg.com/feather-icons/dist/icons/plus-circle.svg" width="24" height="24" />     |
| Quitar (-)        | <img src="https://unpkg.com/feather-icons/dist/icons/minus-circle.svg" width="24" height="24" />    |
| Envío             | <img src="https://unpkg.com/feather-icons/dist/icons/truck.svg" width="24" height="24" />     |
| Devolver envase   | <img src="https://unpkg.com/feather-icons/dist/icons/refresh-cw.svg" width="24" height="24" />      |


### Iconos de estado y feedback

| Tipo                | Icono                                                                                           | Color              |
|:--------------------|:-----------------------------------------------------------------------------------------------|:-------------------|
| Éxito / Descuento   | <img src="https://unpkg.com/feather-icons/dist/icons/check-circle.svg" width="24" height="24" /> | `#78C043` (verde)  |
| Alerta / Error      | <img src="https://unpkg.com/feather-icons/dist/icons/alert-circle.svg" width="24" height="24" /> | `#E94E4E` (rojo)   |
| Información extra   | <img src="https://unpkg.com/feather-icons/dist/icons/info.svg" width="24" height="24" />         | `#66B2E8` (azul)   |


## IMÁGENES INSPIRADORAS

#### Conexión entre productor y consumidor, enfoque sostenible, entorno local.
![Imagen Inspiradora 1](IMG_INSP_1.png)

#### Devolución de envases reciclables, descuentos o cupones, sostenibilidad.
![Imagen Inspiradora 2](IMG_INSP_2.png)

#### Transporte eléctrico, packaging sostenible, funcionalidad digital.
![Imagen Inspiradora 3](IMG_INSP_3.png)


# 2. LANDING PAGE

Se ha diseñado la siguiente página promocional
![Imagen Inspiradora 3](LANDING_PAGE.png)
