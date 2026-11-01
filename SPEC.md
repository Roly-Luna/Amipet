# AmiPet - SPEC HTML y CSS

## Referencia
Figma: https://www.figma.com/design/m3ScRTyUXHut7UHqiYpiiE/Ami-pet-Miercoles?node-id=3-3

## Alcance TB3
- HTML5 semantico y CSS3 puro
- Landing Page y Web Application estaticas
- Sin JavaScript, frameworks, librerias, CDNs ni fuentes externas
- Formularios y controles como prototipos visuales

## Estructura
- `index.html`
- `css/styles.css`
- `img/`
- `pages/auth/`, `pages/adopcion/`, `pages/adoptante/`, `pages/rescatista/`, `pages/educacion/`, `pages/publico/`
- `js/` permanece vacia durante TB3

## Reglas HTML
- Un archivo HTML por pantalla y un solo `h1` por pagina
- Usar etiquetas semanticas cuando corresponda
- Todas las imagenes deben tener `alt`
- Cada campo debe tener `label`, `name` y validacion HTML cuando corresponda
- Navegacion mediante enlaces `href`

## Reglas CSS
- Una unica hoja compartida: `css/styles.css`
- Variables CSS para colores, tipografia, radios, sombras y medidas
- Clases claras con metodologia BEM
- `box-sizing: border-box`
- Mobile-first y media queries desde 768px
- Flexbox o Grid para adaptar el contenido
- Sin estilos inline ni `!important`

## Flujo Git
- `main`: version estable
- `develop`: integracion del sprint
- `feature/*`: ramas creadas desde `develop`
- Cada feature abre PR hacia `develop`
- La liberacion se propone mediante PR de `develop` hacia `main`

## Revision antes del PR
Probar con Live Server, revisar enlaces y rutas, validar responsive, imagenes, semantica y correspondencia con Figma.
