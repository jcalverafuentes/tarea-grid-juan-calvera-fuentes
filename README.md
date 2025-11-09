# Tarea: Reconstrucción de 3 interfaces con Grid + Flex (HTML + CSS puros)

## Uso de Grid y Flex — Landing

**Landing**
He usado Grid para el layout general (header, hero, features, cta, footer) y Flex dentro de cada bloque. El hero usa un grid de 12 columnas, las features un grid responsive con auto-fit, y Flex para alinear elementos como el header, botones y CTA. Se adapta a tablet y móvil con media queries.

**Dashboard**
El layout principal usa Grid con áreas (sidebar, header, main, footer). Dentro, Flex organiza el contenido: la sidebar en columna, el header con buscador y botones, y las tarjetas KPI en grid flexible. Todo se vuelve una sola columna en móvil.

**Portfolio**
El layout está hecho con Grid (header, gallery, contact, footer). La gallery usa grid con auto-fit y alturas variables para simular un masonry. Flex se aplica en el header, en cada tarjeta de proyecto y en la distribución interna del formulario y footer.

---

**Notas de accesibilidad**

Se cumplen los requisitos básicos de accesibilidad indicados en el brief:

Se usa lang="es" en todas las páginas.

Se aplican landmarks semánticos (`header`, `nav`, `main`, `section`, `footer`, `aside`, `article`).

Los enlaces y botones incluyen :focus-visible con borde de color --accent para navegación por teclado.

Colores con contraste AA y tipografía del sistema para legibilidad.

Se incluyen roles ARIA y descripciones (aria-label, aria-hidden, role="img") en elementos decorativos o navegables.

Las tablas del dashboard usan `thead`, `tbody` y `th scope="col"` para estructura semántica y lectura con lector de pantalla.

---

## Capturas de pantalla

- **Landing**  
  - ![Desktop 1](/img/landing_desktop_1.png)
  - ![Desktop 2](/img/landing_desktop_2.png)
  - ![Tablet 1](/img/landing_tablet_1.png) 
  - ![Tablet 2](/img/landing_tablet_2.png)  
  - ![Mobile 1](/img/landing_mobile_1.png)  
  - ![Mobile 2](/img/landing_mobile_2.png)  


- **Dashboard**  
  - ![Desktop](/img/dashboard_desktop.png)
  - ![Tablet](/img/dashboard_tablet.png)  
  - ![Mobile](/img/dashboard_mobile.png)  

- **Portfolio**  
  - ![Desktop 1](/img/portfolio_desktop_1.png)
  - ![Desktop 2](/img/portfolio_desktop_2.png)
  - ![Tablet 1](/img/portfolio_tablet_1.png)
  - ![Tablet 2](/img/portfolio_tablet_2.png)
  - ![Tablet 3](/img/portfolio_tablet_3.png)
  - ![Tablet 4](/img/portfolio_tablet_4.png)
  - ![Mobile 1](/img/portfolio_mobile_1.png)
  - ![Mobile 2](/img/portfolio_mobile_2.png)
  - ![Mobile 3](/img/portfolio_mobile_3.png)
  - ![Mobile 4](/img/portfolio_mobile_4.png)
  - ![Mobile 5](/img/portfolio_mobile_5.png)

---

## Tecnologías utilizadas

- **HTML** (estructura semántica con `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- **CSS** (variables, grid, flex, media queries)
- **:focus-visible**, **roles ARIA** y **lang="es"** para accesibilidad

---

## Estructura del proyecto

landing/

├── index.html

└── styles.css
dashboard/

├── index.html

└── styles.css

portfolio/

├── index.html

└── styles.css

README.md
