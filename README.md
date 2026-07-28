# El primer timbre

**Lo que dije, lo que pensé y lo que nunca conté sobre mi ingreso a secundaria.**

Libro digital interactivo, breve y humanizado sobre la transición de primaria a secundaria en un colegio peruano. La experiencia está diseñada para adolescentes, familias y docentes.

## Enlace esperado

Una vez finalizado el primer despliegue de GitHub Pages:

`https://oprbguitar.github.io/bookdemo/`

## Qué incluye

- Diez capítulos narrativos completos.
- Tres niveles de lectura en cada capítulo: lo que sucede, lo que se dice y lo que se siente.
- Lectura por voz mediante Web Speech API con preferencia por voz `es-PE`.
- Progreso guardado en el dispositivo.
- Reflexiones privadas sin envío a servidores.
- Mapa emocional del colegio.
- Semáforo de adaptación.
- Historia de decisiones y consecuencias.
- Guía breve para familias y docentes.
- Modo de impresión para producir una versión física breve.
- Aplicación web instalable y lectura básica sin conexión.
- Diseño responsive y accesible para teléfono, tableta y escritorio.

## Privacidad

El proyecto no usa cuentas, cookies publicitarias, formularios externos ni analítica. Las respuestas del lector se guardan únicamente mediante `localStorage` en el dispositivo que utiliza.

## Estructura

```text
bookdemo/
├── index.html
├── styles.css
├── script.js
├── icon.svg
├── manifest.webmanifest
├── sw.js
└── .github/workflows/pages.yml
```

## Publicación

El workflow `pages.yml` publica automáticamente cada actualización enviada a la rama `main`.

Si el primer workflow indica que GitHub Pages no está habilitado:

1. Abrir **Settings** del repositorio.
2. Ingresar en **Pages**.
3. En **Build and deployment**, seleccionar **GitHub Actions**.
4. Volver a **Actions** y ejecutar nuevamente el workflow.

## Enfoque editorial

La historia evita presentar la adaptación como un proceso perfecto. El protagonista atraviesa despedidas, incertidumbre, nuevas reglas, soledad momentánea, dificultades académicas, búsqueda de ayuda y pertenencia. El mensaje central es:

> Adaptarse no significa dejar de sentir miedo. Significa aprender qué hacer cuando el miedo aparece.

## Próximas ampliaciones posibles

- Audios grabados por actores adolescentes y adultos.
- Ilustraciones originales por capítulo.
- Códigos QR definitivos para la edición impresa.
- Panel editorial separado para modificar capítulos sin tocar código.
- Versión docente con fichas de conversación y actividades de aula.
- Exportación editorial a PDF para imprenta.

## Autoría

Concepto y dirección: **Pierre R. / AndesNova**  
Desarrollo inicial: experiencia web estática para GitHub Pages.
