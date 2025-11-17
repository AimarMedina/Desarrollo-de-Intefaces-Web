# Guía Completa de Clases Bootstrap 5

## 📋 Índice
1. Colores
2. Espaciado (Margin y Padding)
3. Sistema Grid
4. Display
5. Flexbox
6. Tipografía
7. Imágenes
8. Tamaños
9. Bordes
10. Posicionamiento
11. Componentes Principales

---

## 🎨 1. COLORES

### Colores de Texto
```
text-primary      (azul)
text-secondary    (gris)
text-success      (verde)
text-danger       (rojo)
text-warning      (amarillo)
text-info         (azul claro)
text-light        (gris claro)
text-dark         (gris oscuro)
text-white        (blanco)
text-muted        (gris apagado)
text-body         (color del texto base)
```

### Colores de Fondo
```
bg-primary
bg-secondary
bg-success
bg-danger
bg-warning
bg-info
bg-light
bg-dark
bg-white
bg-transparent
bg-body
```

### Colores de Bordes
```
border-primary
border-secondary
border-success
border-danger
border-warning
border-info
border-light
border-dark
border-white
```

---

## 📏 2. ESPACIADO (Margin y Padding)

### Estructura: `{propiedad}{lados}-{tamaño}`

**Propiedades:**
- `m` = margin
- `p` = padding

**Lados:**
- `t` = top (arriba)
- `b` = bottom (abajo)
- `s` = start (izquierda)
- `e` = end (derecha)
- `x` = horizontal (izquierda y derecha)
- `y` = vertical (arriba y abajo)
- (vacío) = todos los lados

**Tamaños:**
- `0` = 0
- `1` = 0.25rem (4px)
- `2` = 0.5rem (8px)
- `3` = 1rem (16px)
- `4` = 1.5rem (24px)
- `5` = 3rem (48px)
- `auto` = auto

### Ejemplos:
```
m-0, m-1, m-2, m-3, m-4, m-5, m-auto
mt-3           (margin-top: 1rem)
mb-4           (margin-bottom: 1.5rem)
ms-2           (margin-left: 0.5rem)
me-5           (margin-right: 3rem)
mx-3           (margin horizontal: 1rem)
my-4           (margin vertical: 1.5rem)

p-3            (padding: 1rem)
pt-2           (padding-top: 0.5rem)
pb-5           (padding-bottom: 3rem)
px-4           (padding horizontal: 1.5rem)
py-3           (padding vertical: 1rem)
```

### Responsive:
```
mt-2 mt-md-4 mt-lg-5
p-3 p-md-4 p-lg-5
```

---

## 📐 3. SISTEMA GRID

### Contenedores
```
container              (ancho fijo responsive)
container-fluid        (100% ancho)
container-sm          (fluido hasta sm)
container-md          (fluido hasta md)
container-lg          (fluido hasta lg)
container-xl          (fluido hasta xl)
container-xxl         (fluido hasta xxl)
```

### Filas
```
row
row-cols-1, row-cols-2, row-cols-3, row-cols-4, row-cols-5, row-cols-6
row-cols-auto
g-0, g-1, g-2, g-3, g-4, g-5     (gap/gutter)
gx-3, gy-3                        (gap horizontal/vertical)
```

### Columnas
```
col                    (igual tamaño)
col-auto              (tamaño automático)
col-1 hasta col-12    (1/12 hasta 12/12)

Responsive:
col-sm-6              (mitad en pantallas small+)
col-md-4              (1/3 en pantallas medium+)
col-lg-3              (1/4 en pantallas large+)
col-xl-2              (1/6 en pantallas xlarge+)
```

### Offset (desplazamiento)
```
offset-1 hasta offset-11
offset-sm-3
offset-md-4
offset-lg-2
```

### Orden
```
order-first
order-last
order-0 hasta order-5
order-sm-1
order-md-2
```

---

## 📱 4. DISPLAY

```
d-none               (display: none)
d-inline            (display: inline)
d-inline-block      (display: inline-block)
d-block             (display: block)
d-grid              (display: grid)
d-table             (display: table)
d-flex              (display: flex)
d-inline-flex       (display: inline-flex)

Responsive:
d-none d-sm-block d-md-inline d-lg-flex
```

---

## 🔲 5. FLEXBOX

### Dirección
```
flex-row                (horizontal →)
flex-row-reverse        (horizontal ←)
flex-column            (vertical ↓)
flex-column-reverse    (vertical ↑)
flex-sm-row
flex-md-column
```

### Justify Content (alineación horizontal)
```
justify-content-start     (izquierda)
justify-content-end       (derecha)
justify-content-center    (centro)
justify-content-between   (espacio entre)
justify-content-around    (espacio alrededor)
justify-content-evenly    (espacio uniforme)
```

### Align Items (alineación vertical)
```
align-items-start      (arriba)
align-items-end        (abajo)
align-items-center     (centro)
align-items-baseline   (línea base)
align-items-stretch    (estirar)
```

### Align Self (alineación individual)
```
align-self-start
align-self-end
align-self-center
align-self-baseline
align-self-stretch
```

### Wrap
```
flex-wrap             (permitir salto de línea)
flex-nowrap          (sin salto de línea)
flex-wrap-reverse    (salto inverso)
```

### Grow y Shrink
```
flex-grow-0          (no crecer)
flex-grow-1          (crecer)
flex-shrink-0        (no encoger)
flex-shrink-1        (encoger)
flex-fill            (llenar espacio)
```

---

## 📝 6. TIPOGRAFÍA

### Tamaños de Fuente
```
fs-1               (más grande)
fs-2
fs-3
fs-4
fs-5
fs-6               (más pequeño)

fs-sm-3            (responsive)
fs-md-4
fs-lg-2
```

### Peso de Fuente
```
fw-light           (300)
fw-lighter         (más ligero)
fw-normal          (400)
fw-bold            (700)
fw-bolder          (más grueso)
fw-semibold        (600)
```

### Estilo
```
fst-italic         (cursiva)
fst-normal         (normal)
```

### Alineación
```
text-start         (izquierda)
text-center        (centro)
text-end           (derecha)
text-sm-start      (responsive)
text-md-center
text-lg-end
```

### Transformación
```
text-lowercase     (minúsculas)
text-uppercase     (MAYÚSCULAS)
text-capitalize    (Primera Letra Mayúscula)
```

### Decoración
```
text-decoration-none           (sin subrayado)
text-decoration-underline      (subrayado)
text-decoration-line-through   (tachado)
```

### Line Height
```
lh-1              (compacto)
lh-sm             (pequeño)
lh-base           (base)
lh-lg             (grande)
```

### Display Headings (títulos grandes)
```
display-1         (más grande)
display-2
display-3
display-4
display-5
display-6         (más pequeño)
```

### Otras
```
text-wrap         (permitir salto de línea)
text-nowrap       (sin salto de línea)
text-break        (romper palabras largas)
text-truncate     (truncar con ...)
font-monospace    (fuente monoespaciada)
```

---

## 🖼️ 7. IMÁGENES

```
img-fluid          (max-width: 100%, responsive)
img-thumbnail      (borde y padding)

rounded            (bordes redondeados)
rounded-circle     (círculo)
rounded-pill       (píldora)
rounded-0          (sin redondeo)
rounded-1          (poco redondeado)
rounded-2          (medio redondeado)
rounded-3          (muy redondeado)

rounded-top        (redondeo superior)
rounded-end        (redondeo derecho)
rounded-bottom     (redondeo inferior)
rounded-start      (redondeo izquierdo)
```

---

## 📏 8. TAMAÑOS (Width & Height)

### Width (Ancho)
```
w-25              (25%)
w-50              (50%)
w-75              (75%)
w-100             (100%)
w-auto            (automático)
mw-100            (max-width: 100%)
vw-100            (viewport width: 100%)
```

### Height (Alto)
```
h-25              (25%)
h-50              (50%)
h-75              (75%)
h-100             (100%)
h-auto            (automático)
mh-100            (max-height: 100%)
vh-100            (viewport height: 100%)
```

---

## 🔲 9. BORDES

### Bordes Básicos
```
border            (borde en todos los lados)
border-0          (sin borde)
border-top        (borde superior)
border-end        (borde derecho)
border-bottom     (borde inferior)
border-start      (borde izquierdo)

border-top-0      (sin borde superior)
border-end-0      (sin borde derecho)
border-bottom-0   (sin borde inferior)
border-start-0    (sin borde izquierdo)
```

### Grosor de Bordes
```
border-1          (1px)
border-2          (2px)
border-3          (3px)
border-4          (4px)
border-5          (5px)
```

### Border Radius
```
rounded           (bordes redondeados)
rounded-0         (sin redondeo)
rounded-1         (poco redondeado)
rounded-2         (medio redondeado)
rounded-3         (muy redondeado)
rounded-circle    (círculo)
rounded-pill      (píldora)

rounded-top
rounded-end
rounded-bottom
rounded-start
```

---

## 📍 10. POSICIONAMIENTO

### Position
```
position-static     (normal)
position-relative   (relativo)
position-absolute   (absoluto)
position-fixed      (fijo)
position-sticky     (pegajoso)
```

### Top/Bottom/Start/End
```
top-0, top-50, top-100
bottom-0, bottom-50, bottom-100
start-0, start-50, start-100
end-0, end-50, end-100
```

### Translate Middle
```
translate-middle      (centrar)
translate-middle-x    (centrar horizontalmente)
translate-middle-y    (centrar verticalmente)
```

---

## 📊 11. OVERFLOW

```
overflow-auto
overflow-hidden
overflow-visible
overflow-scroll

overflow-x-auto
overflow-x-hidden
overflow-x-visible
overflow-x-scroll

overflow-y-auto
overflow-y-hidden
overflow-y-visible
overflow-y-scroll
```

---

## 👁️ 12. VISIBILIDAD

```
visible           (visible)
invisible         (invisible pero ocupa espacio)

opacity-0         (transparente)
opacity-25        (25% opaco)
opacity-50        (50% opaco)
opacity-75        (75% opaco)
opacity-100       (completamente opaco)
```

---

## 🔘 13. BOTONES

### Tipos
```
btn               (botón base)
btn-primary       (azul)
btn-secondary     (gris)
btn-success       (verde)
btn-danger        (rojo)
btn-warning       (amarillo)
btn-info          (azul claro)
btn-light         (gris claro)
btn-dark          (oscuro)
btn-link          (como enlace)
```

### Outline (solo borde)
```
btn-outline-primary
btn-outline-secondary
btn-outline-success
btn-outline-danger
btn-outline-warning
btn-outline-info
btn-outline-light
btn-outline-dark
```

### Tamaños
```
btn-lg            (grande)
btn-sm            (pequeño)
```

### Estados
```
active            (activo)
disabled          (deshabilitado)
```

### Grupos
```
btn-group         (grupo horizontal)
btn-group-vertical (grupo vertical)
btn-group-lg      (grupo grande)
btn-group-sm      (grupo pequeño)
btn-toolbar       (barra de herramientas)
```

---

## 🃏 14. COMPONENTES PRINCIPALES

### Alerts
```
alert
alert-primary, alert-secondary, alert-success
alert-danger, alert-warning, alert-info
alert-light, alert-dark
alert-dismissible
alert-heading
alert-link
```

### Badges
```
badge
bg-primary, bg-secondary, bg-success, etc.
rounded-pill      (badge redondeado)
```

### Cards
```
card
card-body
card-title
card-subtitle
card-text
card-link
card-header
card-footer
card-img
card-img-top
card-img-bottom
card-img-overlay
```

### Forms
```
form-control      (input, textarea, select)
form-control-lg   (grande)
form-control-sm   (pequeño)
form-label        (etiqueta)
form-text         (texto de ayuda)
form-select       (select estilizado)
form-check        (checkbox/radio)
form-check-input
form-check-label
form-check-inline
form-switch       (switch toggle)
input-group       (grupo de inputs)
input-group-text
form-floating     (label flotante)
is-valid          (estado válido)
is-invalid        (estado inválido)
valid-feedback
invalid-feedback
```

### List Group
```
list-group
list-group-item
list-group-item-action
list-group-item-primary, secondary, etc.
list-group-flush  (sin bordes)
list-group-horizontal
list-group-numbered
```

### Modal
```
modal
modal-dialog
modal-content
modal-header
modal-title
modal-body
modal-footer
modal-dialog-centered
modal-dialog-scrollable
modal-fullscreen
modal-sm, modal-lg, modal-xl
```

### Navbar
```
navbar
navbar-expand-sm, md, lg, xl, xxl
navbar-light
navbar-dark
navbar-brand
navbar-nav
navbar-text
navbar-toggler
navbar-toggler-icon
navbar-collapse
nav-item
nav-link
```

### Nav & Tabs
```
nav
nav-tabs
nav-pills
nav-fill
nav-justified
nav-item
nav-link
tab-content
tab-pane
```

### Pagination
```
pagination
pagination-lg
pagination-sm
page-item
page-link
```

### Progress
```
progress
progress-bar
progress-bar-striped
progress-bar-animated
```

### Spinners
```
spinner-border
spinner-border-sm
spinner-grow
spinner-grow-sm
```

### Tables
```
table
table-sm
table-bordered
table-borderless
table-striped
table-striped-columns
table-hover
table-active
table-primary, secondary, success, etc.
table-responsive
table-responsive-sm, md, lg, xl, xxl
```

---

## 🎭 15. SHADOWS

```
shadow-none
shadow-sm         (sombra pequeña)
shadow           (sombra normal)
shadow-lg        (sombra grande)
```

---

## 🔄 16. FLOAT

```
float-start       (flotante izquierda)
float-end         (flotante derecha)
float-none        (sin flotante)

float-sm-start    (responsive)
float-md-end
float-lg-none

clearfix          (limpiar flotantes)
```

---

## 🎨 17. INTERACCIONES

```
user-select-all   (seleccionar todo)
user-select-auto  (selección automática)
user-select-none  (no seleccionable)

pe-none           (pointer-events: none)
pe-auto           (pointer-events: auto)
```

---

## 🔗 18. RATIO (Aspect Ratio)

```
ratio             (contenedor de ratio)
ratio-1x1         (1:1 cuadrado)
ratio-4x3         (4:3)
ratio-16x9        (16:9)
ratio-21x9        (21:9)
```

---

## 📍 19. Z-INDEX

```
z-n1              (-1)
z-0               (0)
z-1               (1)
z-2               (2)
z-3               (3)
```

---

## 🔊 20. SCREEN READERS

```
visually-hidden   (oculto visualmente pero accesible)
visually-hidden-focusable (visible al enfocar)
```

---

## 📱 BREAKPOINTS RESPONSIVE

Todos los breakpoints disponibles:

```
sin sufijo        <576px (extra pequeño)
-sm              ≥576px (pequeño)
-md              ≥768px (mediano)
-lg              ≥992px (grande)
-xl              ≥1200px (extra grande)
-xxl             ≥1400px (extra extra grande)
```

### Ejemplo de uso responsive:
```html
<div class="col-12 col-sm-6 col-md-4 col-lg-3">
  <!-- 100% en móvil, 50% en small, 33% en medium, 25% en large -->
</div>

<div class="d-none d-md-block">
  <!-- Oculto en móvil y small, visible en medium+ -->
</div>

<p class="text-center text-lg-start">
  <!-- Centrado en móvil, alineado izquierda en large+ -->
</p>
```

---

## 💡 CONSEJOS FINALES

1. **Combina clases** para crear diseños complejos
2. **Mobile First**: diseña primero para móvil, luego añade breakpoints
3. **No olvides** incluir Bootstrap en tu HTML
4. **Consulta** la documentación oficial: https://getbootstrap.com
5. **Practica** mezclando diferentes clases

---

**Guía creada por Claude - Bootstrap 5.3**
*Para más información visita: https://getbootstrap.com/docs/5.3*
