# Mi portafolio web

Portafolio personal de Lauren, creado con HTML y Tailwind CSS. Incluye la página
de inicio con información y habilidades, y una página de proyectos con enlaces
editables.

## Archivos principales

- `Mi-Portafolio.html`: página principal.
- `proyectos.html`: página de proyectos.
- `img/lauren.jpeg`: foto mostrada en la página principal.
- `src/input.css`: entrada de Tailwind CSS.
- `dist/output.css`: estilos compilados que carga la página.

## Uso

Instala las dependencias y compila los estilos:

```bash
npm install
npm run build
```

Abre `Mi-Portafolio.html` en el navegador para visitar el inicio. La navegación
permite ir a `proyectos.html`; el enlace de contacto lleva al pie de página de
cualquiera de las dos páginas. En `proyectos.html`, reemplaza `#` en cada enlace
«Ver proyecto» por la URL correspondiente.

El botón de WhatsApp abre directamente el chat con el número configurado y deja
un mensaje listo para enviar.
Si cambias clases de Tailwind, vuelve a ejecutar `npm run build`; para
recompilar al guardar, usa `npm run watch`.
