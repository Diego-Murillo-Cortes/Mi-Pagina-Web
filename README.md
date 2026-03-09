# Portafolio Web - Diego Murillo Cortes

Portafolio personal desarrollado con HTML y CSS para presentar perfil profesional, experiencia laboral, formacion academica, certificaciones y proyectos.

El sitio esta enfocado en una imagen profesional para procesos de seleccion y marca personal.

## Objetivo del proyecto

Construir una pagina web clara, responsiva y visualmente consistente que permita:

- Mostrar mi perfil profesional y propuesta de valor.
- Resaltar experiencia laboral en formato expandible y facil de leer.
- Evidenciar formacion academica y certificaciones con soporte documental.
- Presentar proyectos desarrollados con enlaces de demostracion.
- Centralizar canales de contacto (correo, WhatsApp, LinkedIn, GitHub).

## Tecnologias utilizadas

- HTML5
- CSS3
- Diseño responsivo con media queries
- Componentes nativos HTML (`details` y `summary`) para interaccion sin JavaScript

## Estructura del proyecto

```text
mi Paguina/
|- index.html
|- sobre-mi.html
|- experiencia.html
|- portafolio.html
|- estilopaguina.css
|- certificados/
|- assets de imagen (*.png, *.jpg)
|- CV Diego Murillo 2025.pdf
```

## Arquitectura de paginas

### 1. `index.html`

Landing principal del portafolio:

- Presentacion personal
- Stack tecnologico principal
- Boton de descarga de hoja de vida
- Redes sociales

### 2. `sobre-mi.html`

Seccion de perfil profesional:

- Resumen personal y motivacion
- Propuesta de valor
- Aportes al equipo
- Formacion academica en tarjetas (bachiller, tecnico, profesional) con actas
- Certificados destacados + listado completo desplegable

### 3. `experiencia.html`

Historial laboral en tarjetas:

- Cargo, empresa y periodo
- Funciones por empleo con componente expandible (`Ver mas`) usando `details/summary`

### 4. `portafolio.html`

Seccion de proyectos:

- Introduccion de portafolio
- Tarjetas de proyectos con descripcion
- Tecnologias usadas por proyecto
- Enlaces de demostracion

## Estilo y UI

Toda la interfaz se centraliza en `estilopaguina.css`, incluyendo:

- Variables CSS en `:root` para colores, tipografia y escalas.
- Layout responsivo para desktop y mobile.
- Estilo unificado de header, footer, cards y botones.
- Animaciones suaves de transicion y hover.

## Certificados y documentos

La carpeta `certificados/` contiene:

- Certificados tecnicos (Cisco, Alura, Oracle One, Java, etc.)
- Actas academicas (bachiller, tecnico y profesional)

Estos archivos se enlazan directamente desde `sobre-mi.html`.

## Como ejecutar el proyecto

Al ser un proyecto estatico, puedes abrirlo directamente en navegador:

1. Abrir `index.html` con doble clic.
2. O usar una extension como **Live Server** en VS Code para desarrollo local.

## Personalizacion rapida

Para adaptar el sitio a futuro:

- Actualizar textos: editar archivos `.html`.
- Cambiar colores y tipografia: editar variables en `:root` de `estilopaguina.css`.
- Agregar nuevos proyectos: duplicar una `tarjeta-proyecto` en `portafolio.html`.
- Agregar experiencia: duplicar una `trabajo-tarjeta` en `experiencia.html`.
- Agregar certificados: copiar PDF en `certificados/` y enlazar en `sobre-mi.html`.

## Mejoras sugeridas (roadmap)

- Agregar favicon y metadatos SEO/Open Graph.
- Incorporar version bilingue (ES/EN).
- Integrar formulario de contacto con backend o servicio externo.
- Optimizar imagenes (WebP) para mejorar rendimiento.
- Publicar en Vercel/Netlify con dominio propio.

## Autor

**Diego Murillo Cortes**  
Desarrollador en transicion profesional hacia software.

- LinkedIn: `https://www.linkedin.com/in/diego-murillo-cort%C3%A9s-sistemas`
- GitHub: `https://github.com/Diego-Murillo-Cortes`

