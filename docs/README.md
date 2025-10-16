# Asociación de Artesanos Mochica Chimú

Este sitio web institucional reúne información, identidad visual y recursos descargables de la Asociación de Artesanos Mochica Chimú (AAMC). A continuación se detalla la nueva estructura de activos.

## Identidad visual

- **Logotipo principal**: `images2/logo-asociacion-mochica.svg`
- **Favicon**: incorporar manualmente archivos `favicon.png` (256x256) y `favicon.ico` (16/32/64 px) dentro de `images2/` antes de desplegar.
- **Paleta cromática**: Terracota (`#b84f2e`), dorado (`#d88c2d`), marrón oscuro (`#1f1b1a`), crema (`#f7f2ea`).
- **Tipografías institucionales**: Merriweather (titulares) y Source Sans 3 (texto).

## Fotografías optimizadas

Para evitar advertencias de archivos binarios en las solicitudes de extracción, las fotografías no se incluyen en el repositorio. Coloca manualmente en `images2/` las imágenes optimizadas (ancho máximo 1600 px, calidad JPEG 80-85%) respetando los nombres de archivo documentados abajo.

| Categoría | Archivo(s) sugerido(s) |
|-----------|------------------------|
| Hero | `hero-ceramica-comunitaria.jpg`, `hero-tejidos-ancestrales.jpg` |
| Misión e historia | `sala-exposicion-ceramica.jpg`, `artesania-ceramica-proceso.jpg`, `taller-textil-comunitario.jpg` |
| Servicios | `servicio-tour-taller.jpg`, `servicio-capacitacion-artesanas.jpg`, `servicio-comercializacion-solidaria.jpg`, `servicio-educacion-cultural.jpg` |
| Catálogo | `galeria-ceramica-ancestral.jpg`, `galeria-textiles-naturales.jpg`, `galeria-orfebreria-chimu.jpg`, `artesania-orfebreria-detalle.jpg`, `taller-textil-comunitario.jpg` |
| Testimonios | `testimonio-artesana-1.jpg`, `testimonio-artesano-2.jpg`, `testimonio-colaboradora-3.jpg`, `testimonio-investigador-4.jpg`, `visita-guiada-ninos.jpg`, `taller-ninos-arte.jpg`, `expo-feria-cultural.jpg`, `vista-aerea-centro-cultural.jpg` |
| Apoyo institucional | `centro-interpretacion-chimu.jpg`, `banner-taller-alfareria.jpg`, `detalle-iconografia-mochica.jpg` |

Consulta también `images2/README.md` para recordar por qué los archivos binarios no se versionan y cómo prepararlos antes de desplegar.

## Estructura de páginas

- `index.html`: Presentación general, misión, servicios destacados, catálogo y testimonios.
- `about.html`: Historia de la asociación, misión, visión y línea de tiempo.
- `service.html`: Programas culturales, educativos y de comercialización.
- `menu.html`: Catálogo detallado de colecciones y servicios complementarios.
- `reservation.html`: Formulario para visitas guiadas, talleres y residencias.
- `testimonial.html`: Voces de artesanos, aliados y visitantes.
- `contact.html`: Información de contacto, formulario de alianzas y guía de llegada.

Todas las páginas comparten cabecera, pie de página y estilos unificados.

## Estilos y scripts

- Hoja de estilos principal: `css/style.min.css` (con variables de color, tipografías y componentes institucionales).
- Script básico: `js/main.js` (interacciones comunes como el botón "volver al inicio").

## Cómo actualizar el contenido

1. Sustituir o agregar fotografías en `images2/` (no versionadas). Recuerda añadirlas fuera del repositorio git antes de desplegar la web.
2. Editar el texto directamente en los archivos HTML según la sección correspondiente.
3. Ajustar estilos globales en `css/style.min.css`; mantener el uso de variables CSS para coherencia cromática.
4. Documentar cambios adicionales en este archivo para mantener el inventario actualizado.

## Créditos y uso

Las imágenes y textos corresponden al acervo de la AAMC y pueden emplearse únicamente para fines institucionales autorizados. Para colaboraciones externas escribir a `alianzas@artesanosmochica.org`.

## Notas sobre solicitudes de extracción y archivos binarios

Las plataformas de control de cambios suelen mostrar avisos de que "los archivos binarios no se admiten" cuando se intenta previsualizar imágenes JPEG/PNG en un diff. Para evitar bloqueos durante la creación de solicitudes de extracción, las fotografías se gestionan fuera del repositorio.

Antes de publicar o desplegar el sitio, recuerda copiar manualmente los recursos fotográficos optimizados a `images2/`. De este modo se mantienen los nombres esperados por el código sin incorporar archivos binarios al historial de Git.
