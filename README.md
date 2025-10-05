# Hamburger Restaurant Website

Este proyecto es una página web para un restaurante de hamburguesas, diseñada para mostrar información sobre el restaurante, su menú, servicios y permitir contacto y suscripción a ofertas. El sitio está construido con **HTML5** y **CSS** y es completamente **responsivo**.

---

## Autor

**Carlos Castro Fernández**

---

## Estructura del proyecto

- `index.html` – Archivo principal con la estructura de la página.
- `css/style.css` – Archivo de estilos CSS para toda la página.
- `img/` – Carpeta que contiene todas las imágenes usadas en la web (logo, hamburguesas, iconos, etc.).

---

## Descripción de la página

La página está organizada en varias secciones principales:

### 1. Header

- Contiene el **logo del restaurante**.
- Un **menú de navegación** con enlaces a `HOME`, `MENU`, `SERVICES` y `CONTACT US`.
- Iconos adicionales: **lupa** (búsqueda), **teléfono** y un número de contacto.
- Diseñado con **flexbox** para alinear los elementos horizontalmente y mantenerlos centrados.

---

### 2. Sección Home (`#home`)

- Contiene un **título principal** y subtítulos promocionales.
- Texto descriptivo de bienvenida al restaurante.
- Una **imagen de hamburguesa** a la derecha.
- Diseño responsivo usando **flexbox** para mantener texto e imagen alineados en desktop y adaptables en móviles.

---

### 3. Sección de Estadísticas (`container-2`)

- Muestra **estadísticas clave** del restaurante:
  - Visitantes del sitio web.
  - Pedidos diarios.
  - Repartidores.
  - Años de experiencia.
- Cada estadística está dentro de un contenedor con **flexbox**, permitiendo distribución uniforme.

---

### 4. Sección About Us / Menu (`#menu` – `container-3`)

- Breve descripción sobre el restaurante.
- Texto explicativo con párrafos de información.
- Imagen relacionada con la comida.
- Botón "Read More" para más información.
- Diseño **grid y flex** para distribuir texto e imagen lado a lado.

---

### 5. Sección Servicios (`#services` – `container-4`)

- Explica la **misión del restaurante**.
- Contiene imagen de chef y lista de servicios o beneficios.
- Uso de **flexbox** y **grid** para organizar imagen, texto y listas de forma clara.
- Botón "Read More" para ampliar información.

---

### 6. Sección Contacto (`#contact` – `container-5`)

- Formulario de contacto con:
  - Input para nombre.
  - Input para email.
  - Textarea para mensaje.
- Botón de envío "Message".
- Imagen decorativa a un lado.
- Uso de **grid** para organizar los inputs y **media queries** para que se adapte a móviles (una columna).

---

### 7. Sección Suscripción a Ofertas (`container-6`)

- Permite a los usuarios **suscribirse con su email**.
- Contiene input para correo y botón de suscripción.
- Imagen decorativa a un lado.
- Diseño responsivo para que el botón e input se ajusten en pantallas pequeñas.

---

### 8. Footer

- Contiene información de la empresa, enlaces rápidos y contacto.
- Distribución en **grid** para organizar secciones de links, información y contacto.
- Segunda sección del footer con aviso de copyright.

---

## Tecnologías utilizadas

- **HTML5**
- **CSS3**
  - Flexbox para layout de filas y columnas.
  - Grid para secciones con múltiples columnas (formularios y footer).
  - Media queries para diseño responsivo.
- Imágenes y iconos para mejorar la estética del sitio.

---

## Responsividad

- El sitio está diseñado para ser **adaptable a dispositivos móviles, tablet y desktop**.
- Uso de **media queries** para ajustar:
  - Columnas de grids.
  - Tamaño de imágenes y botones.
  - Distribución de los elementos en flexbox.

---

## Estructura de carpetas recomendada

