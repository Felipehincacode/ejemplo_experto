# Panadería Artesanal - Sitio Web

Este es un sitio web responsive para una panadería artesanal, con un diseño vintage y minimalista que incluye modo oscuro.

## Características

- Diseño responsive que se adapta a todos los dispositivos
- Modo oscuro/claro con persistencia en localStorage
- Integración con Google Maps
- Formulario de contacto
- Animaciones suaves y efectos de transición
- Estilo vintage con textura de madera
- Timeline interactivo en la página de historia
- Galería de productos
- Testimonios de clientes

## Estructura del Proyecto

```
.
├── index.html
├── productos.html
├── historia.html
├── contacto.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── img/
    ├── hero-bg.jpg
    ├── pan1.jpg
    ├── pan2.jpg
    ├── pan3.jpg
    ├── pan4.jpg
    ├── historia1.jpg
    ├── cliente1.jpg
    └── cliente2.jpg
```

## Configuración

1. Clona este repositorio:
```bash
git clone <url-del-repositorio>
```

2. Reemplaza las imágenes en la carpeta `img/` con tus propias imágenes:
   - `hero-bg.jpg`: Imagen de fondo para la sección hero
   - `pan1.jpg` a `pan4.jpg`: Imágenes de productos
   - `historia1.jpg`: Imagen histórica de la panadería
   - `cliente1.jpg` y `cliente2.jpg`: Fotos de clientes para testimonios

3. Configura la API de Google Maps:
   - Obtén una clave de API de Google Maps
   - Reemplaza `YOUR_GOOGLE_MAPS_API_KEY` en `contacto.html` con tu clave de API
   - Actualiza las coordenadas en la función `initMap()` con la ubicación de tu panadería

## Personalización

### Colores
Los colores del sitio se pueden personalizar modificando las variables CSS en `css/styles.css`:

```css
:root {
    --primary-color: #8B4513;
    --secondary-color: #DEB887;
    --text-color: #2C1810;
    --background-color: #FFF8DC;
    /* ... más variables de color ... */
}
```

### Contenido
- Actualiza el texto en los archivos HTML según tu necesidad
- Modifica los productos en `productos.html`
- Actualiza la historia en `historia.html`
- Ajusta la información de contacto en `contacto.html`

### Fuentes
El sitio utiliza las fuentes Georgia y Playfair Display. Para cambiar las fuentes:
1. Modifica las declaraciones `font-family` en `css/styles.css`
2. Si usas fuentes web, añade los enlaces correspondientes en el `<head>` de cada archivo HTML

## Desarrollo

Para desarrollar localmente, puedes usar un servidor local simple como:

```bash
python -m http.server 8000
```

O con Node.js:

```bash
npx serve
```

## Optimización de Imágenes

Para un mejor rendimiento, asegúrate de:
1. Optimizar todas las imágenes antes de subirlas
2. Usar formatos modernos como WebP cuando sea posible
3. Proporcionar diferentes tamaños de imagen para diferentes dispositivos

## SEO

El sitio incluye metaetiquetas básicas para SEO. Personaliza las siguientes etiquetas en cada página:
- `<title>`
- `<meta name="description">`
- `<meta name="keywords">`

## Soporte de Navegadores

El sitio es compatible con:
- Chrome (últimas 2 versiones)
- Firefox (últimas 2 versiones)
- Safari (últimas 2 versiones)
- Edge (últimas 2 versiones)

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
