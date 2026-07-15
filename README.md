# Pérez Torres Abogados — Sitio Web Oficial

Sitio web estático profesional para el **Despacho de Abogados Pérez Torres**, especializado en asesoría jurídica integral, litigio de alta complejidad y defensa patrimonial en la Ciudad de México y la República Mexicana.

---

## 🏛️ Descripción del Proyecto

El proyecto consiste en una plataforma web de alto impacto institucional compuesta por una **Landing Page principal** y **5 páginas de áreas legales especializadas**, convertidas desde los prototipos de diseño de Stitch en una arquitectura estática limpia, semántica, responsiva y altamente optimizada.

### 📄 Estructura del Sitio

- `index.html` — **Landing Page Principal**: Presentación institucional, estadísticas, áreas de práctica, equipo legal, metodología, testimonios, recursos legales, preguntas frecuentes y sección de contacto/ubicación con mapa interactivo.
- `administrativo.html` — **Derecho Administrativo**: Licitaciones públicas, procedimientos sancionadores, juicios de nulidad, defensa al consumidor y actos de autoridades en CDMX.
- `fiscal.html` — **Derecho Fiscal**: Litigio ante el SAT, IMSS, INFONAVIT, juicios de nulidad fiscal, devoluciones de impuestos y protección frente a embargos o inmovilización de cuentas.
- `familiar.html` — **Derecho Familiar**: Divorcios incausados y contenciosos, pensiones alimenticias, guarda y custodia (interés superior del menor), patrimonio familiar y sucesiones.
- `civil.html` — **Derecho Civil**: Elaboración, revisión, cumplimiento y rescisión de contratos civiles, juicios de arrendamiento inmobiliario e hipotecarios.
- `mercantil.html` — **Derecho Mercantil**: Cobranza judicial y extrajudicial de cartera vencida, títulos de crédito y ejecutivos, controversias de socios y accionistas, y contratos corporativos.

---

## 🎨 Sistema de Diseño y Tokens (`DESIGN.md`)

El diseño visual se basa estrictamente en el sistema oficial definido para el despacho (`juris_prestige/DESIGN.md`), caracterizado por una estética sobria, elegante y autoritaria:

- **Paleta de Colores Institucional**:
  - `Oxford Navy` (`#1D3A7D` / `#002363`): Color primario que transmite autoridad, tradición y confianza jurídica.
  - `Heritage Gold` (`#A68966` / `#c2a37e`): Acento secundario para elementos de prestigio y llamadas a la acción (CTAs).
  - `Statute Gray` (`#333333` / `#444650`): Tono secundario para textos legibles y descriptivos.
  - `Parchment / Surface` (`#faf8ff` / `#F9F9F9`): Fondos limpios que garantizan máxima legibilidad e iluminación en pantalla.
  - `Silver Lining` (`#DADADA`): Bordes finos y divisiones estructurales.
- **Geometría y Tipografía**:
  - **Esquinas Rectas (`0px` / Sharp)**: Todos los contenedores, tarjetas y botones de acción utilizan bordes rectos para reforzar la firmeza e institucionalidad.
  - **Playfair Display**: Tipografía serif reservada para titulares y encabezados de autoridad (`display-lg`, `headline-md`).
  - **Inter**: Tipografía sans-serif para cuerpos de texto, etiquetas y botones de alta legibilidad (`body-lg`, `body-md`, `label-caps`).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 Semántico**: Estructura accesible (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) optimizada para motores de búsqueda (SEO).
- **CSS3 / Hoja de Estilos Centralizada (`assets/css/styles.css`)**: Consolidación de utilidades personalizadas, animaciones de micro-interacción, variables de color y estilos para íconos Material Symbols.
- **Tailwind CSS (v3 vía CDN)**: Configuración en tiempo de ejecución (`<script id="tailwind-config">`) con plugins avanzados (`forms`, `container-queries`) para garantizar cero dependencias en tiempo de compilación y máxima facilidad de despliegue en cualquier servidor estático.
- **Google Fonts & Material Symbols Outlined**: Tipografías e íconos vectoriales dinámicos cargados de forma óptima.
- **Integraciones Funcionales**:
  - **WhatsApp API**: Enlaces dinámicos codificados (`wa.me/525523963530?text=...`) adaptados a cada área de especialidad jurídica.
  - **Google Maps Embed API**: Visualización interactiva de la oficina ubicada en *C. Aniceto Ortega 817, Col del Valle Centro, Benito Juárez, 03100 Ciudad de México, CDMX*.

---

## 🚀 Cómo Visualizar y Ejecutar Localmente

Al ser un sitio web 100% estático (sin necesidad de preprocesadores de Node.js ni bases de datos), puede previsualizarse en cualquier equipo de las siguientes formas:

### Opción 1: Abrir directamente en el Navegador (Doble Clic)
1. Navega a la carpeta principal del proyecto en tu explorador de archivos.
2. Haz doble clic en el archivo `index.html`.
3. El sitio web se abrirá automáticamente en tu navegador predeterminado. Puedes navegar a cualquiera de las 5 páginas de área desde el menú superior, las tarjetas de áreas de práctica o el pie de página.

### Opción 2: Servidor de Desarrollo Local (Recomendado para testing)
Si dispones de Python o extensiones como *Live Server* en VS Code:

- **Con Python 3**:
  ```bash
  python -m http.server 8000
  ```
  Abre tu navegador en `http://localhost:8000/`.

- **Con Node (http-server)**:
  ```bash
  npx http-server ./ -p 8080
  ```
  Abre tu navegador en `http://localhost:8080/`.

---

## 📍 Ubicación y Contacto del Despacho

- **Dirección**: C. Aniceto Ortega 817, Col del Valle Centro, Benito Juárez, 03100 Ciudad de México, CDMX.
- **Teléfono / WhatsApp**: [55 2396 3530](tel:525523963530)
- **Correo**: [contacto@pereztorres.mx](mailto:contacto@pereztorres.mx)

---

© 2026 **Pérez Torres Abogados S.C.** Todos los derechos reservados.
