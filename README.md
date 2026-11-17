# AXEL.DEV — Portafolio interactivo con LEXA

## Estructura
- `index.html`: vista principal, visor de contenido y terminal.
- `css/styles.css`: diseño visual y comportamiento adaptable.
- `js/main.js`: intérprete de comandos LEXA y carga de secciones.
- `project.html`: plantilla de detalle de proyecto.
- `js/project.js`: contenido de las fichas individuales.

## Uso
Abre `index.html` en un navegador moderno. No requiere dependencias.

Escribe `help` o `lexa help` en la terminal.

Comandos de sección:
- `lexa run about-me`
- `lexa run projects`
- `lexa run skills`
- `lexa run education`
- `lexa run blog`
- `lexa run contact`

Fichas individuales:
- `lexa run projects -a` (HakaShoes)
- `lexa run projects -b` (Bip Bip Papel)
- `lexa run projects -c` (Erandi)

El scroll de escritorio se habilita cuando se han cargado todas las secciones principales. En pantallas pequeñas el scroll permanece disponible para evitar bloquear la navegación táctil.

## Datos pendientes
No se han inventado URLs de repositorios o demostraciones. Erandi conserva una descripción pendiente de verificación.
