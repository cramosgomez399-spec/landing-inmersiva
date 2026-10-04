# Odisea — landing inmersiva en WebGL

Experiencia de una sola página donde 80 000 partículas se transforman mientras haces scroll: esfera → galaxia → nudo toroidal → túnel a la velocidad de la luz → océano → texto.

**Demo:** https://cramosgomez399-spec.github.io/landing-inmersiva/

## Qué incluye
- Partículas que cambian de forma en la GPU (shaders GLSL propios) con explosión y turbulencia entre capítulos.
- Resplandor (bloom), cámara que viaja por seis capítulos y colores que cambian en cada uno.
- El cursor aparta las partículas; un clic lanza una onda expansiva.
- Sonido ambiental generado en el navegador (Web Audio, sin archivos), activable desde el botón.
- Pantalla de carga, cursor personalizado, navegación por capítulos y enlaces directos (`#c0` … `#c5`).
- Respeta la preferencia de "reducir movimiento" y se adapta a celulares.

## Tecnologías
HTML, CSS y JavaScript en un solo archivo, con [Three.js](https://threejs.org/) desde CDN.

## Verlo en local
Cualquier servidor estático sirve, por ejemplo:

```bash
npx http-server . -p 3401
```
