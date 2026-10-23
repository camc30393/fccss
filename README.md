# Rediseño del sitio web de la Facultad de Ciencias Sociales (UNAH) · Demostración

Tres propuestas de diseño (A · Vitrina académica, B · Narrativa nocturna, C · Modular contemporánea) con **el mismo contenido**: siete páginas, todo a tres clics o menos desde la portada.

**Demostración publicada:** https://camc30393.github.io/fccss/

**Inicio de la demostración:** `index.html`

## Contenido de esta carpeta

| Ruta | Qué es |
|---|---|
| `index.html` | Selector para presentar y comparar las tres propuestas |
| `A_vitrina/`, `B_narrativa/`, `C_modular/` | Las siete páginas de cada propuesta |
| `media/` | Fotografías, escudos y logotipos que usan las páginas |
| `cms/` | Hojas de estilo e imágenes de la plantilla del portal UNAH, para mostrar cada página tal como se verá dentro del CMS |
| `capturas/` | Capturas de cada propuesta (computadora, teléfono y ventana emergente) |
| `documentos/` | Propuesta de rediseño en PDF |
| `auditoria_clics.json` | Resultado de la auditoría de la regla de tres clics |
| `.nojekyll` | Indica a GitHub Pages que publique los archivos tal cual |

## Publicar en GitHub Pages

1. Cree un repositorio (por ejemplo, `fccss-rediseno`) y suba **todo el contenido de esta carpeta** a la raíz de la rama `main` (incluido `.nojekyll`).
2. En el repositorio: **Settings › Pages › Build and deployment › Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos la demostración estará en `https://<usuario>.github.io/<repositorio>/` (publicación actual: https://camc30393.github.io/fccss/).

Todos los enlaces son relativos, por lo que la demostración funciona con cualquier nombre de repositorio y también abriendo `index.html` desde el equipo.

## Notas

- Esta es una **demostración**. Al migrar al portal de la UNAH, las páginas se regeneran con las direcciones definitivas (modo `cms` del generador); la barra superior de cambio de propuesta y la plantilla del portal (encabezado UNAH, banda de título, submenú y pie, carpeta `cms/`) no forman parte de los bloques que se pegan en el portal: el CMS las pone por sí mismo.
- El «Mensaje de la Decana» es una propuesta de texto por validar.
- Fotografías: página oficial de Facebook de la Facultad. Escudos y logotipos: sitio actual de la Facultad. Colores: los del portal UNAH (azul #253A69, oro #FFCC00, azul #235383) con acentos del escudo de la Facultad. Tipografía: Montserrat, la misma del portal.

Elaborado por Christian Alexis Manzanares Cruz · IIS/OBSAN, Facultad de Ciencias Sociales, UNAH · Octubre de 2026.
