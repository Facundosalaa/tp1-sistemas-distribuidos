# TP1 · Sistemas Operativos Distribuidos

Página web del **Eje Temático 1 — Fundamentos de los Sistemas Operativos Distribuidos**.

**Verla online:** https://facundosalaa.github.io/tp1-sistemas-distribuidos/

Es un solo archivo (`index.html`) con todo adentro: HTML, estilos y JavaScript. No hay que instalar nada ni compilar nada.

---

## Estado del material

| | Estado |
|---|---|
| Podcast introductorio (1:49) | Cargado |
| Video general (6:43, en 3 partes) | Cargado |
| 8 imágenes del eje | Cargadas |
| Nombres de las integrantes | **Falta** |

Lo único pendiente es completar los nombres. Están en `index.html`, en `CONFIG.integrantes`.

---

## Cómo se edita

Todo se configura en un solo lugar. Abrí `index.html`, buscá el bloque `const CONFIG = {` (está casi al final, dentro del `<script>`) y cambiá lo que necesites. **No hace falta tocar nada más.**

```js
const CONFIG = {
  integrantes: ["Nombre 1", "Nombre 2", "Nombre 3"],

  podcast: {
    src: "audio/podcast.m4a",
    duracion: "1:49"
  },

  video: {
    duracion: "6:43 · 3 partes",
    partes: [
      { titulo: "Parte 1", src: "video/parte-1.mp4", duracion: "3:37" },
      { titulo: "Parte 2", src: "video/parte-2.mp4", duracion: "1:46" },
      { titulo: "Parte 3", src: "video/parte-3.mp4", duracion: "1:20" }
    ]
  },

  imagenes: {
    mapaMental: "img/mapa-mental.jpeg",
    tema1:      "img/tema1.jpeg",
    ...
  }
};
```

Si dejás un campo vacío (`""`) no se rompe nada: muestra un recuadro que dice qué va en ese lugar.

### Reemplazar una imagen

Pisá el archivo en `img/` con el mismo nombre y listo. Si le cambiás la extensión, actualizá también la ruta en `CONFIG.imagenes`.

| Archivo | Dónde aparece |
|---|---|
| `mapa-mental.jpeg` | Portada |
| `tema1.jpeg` | Tema 01 · Introducción a los SOD |
| `tema2.jpeg` | Tema 02 · Modelos y Arquitecturas |
| `tema3.jpeg` | Tema 03 · Redes de Interconexión |
| `tema4.jpeg` | Tema 04 · Cliente-Servidor y P2P |
| `tema5.jpeg` | Tema 05 · Características de Diseño |
| `tema6.jpeg` | Tema 06 · Funciones y Servicios |
| `cierre.jpeg` | Sección final |

Los prompts con los que se generaron están en [PROMPTS.md](PROMPTS.md), por si hay que rehacer alguna.

### El video

Están los tres archivos en `video/`. La página muestra un selector de partes y, cuando termina una, arranca la siguiente sola.

Si en algún momento preferís pasarlos a YouTube: subilos como *no listados*, vaciá `CONFIG.video.partes` y pegá el link en `CONFIG.video.url`. Acepta formato `youtube.com/watch?v=…`, `youtu.be/…` o un archivo de Drive.

---

## Cómo ponerla en Google Sites

**Insertar → Insertar código → Por URL**, y pegás la dirección de GitHub Pages.

Importante: usar la opción **por URL** y no pegar el código a mano. Las imágenes, el audio y los videos están referenciados con rutas relativas (`img/…`, `audio/…`, `video/…`), y esas rutas sólo funcionan si la página se sirve desde su propia dirección.

---

## Qué hay en cada archivo

| Archivo | Qué es |
|---|---|
| `index.html` | La página. Es lo único que importa. |
| `img/` | Las 8 imágenes del eje. |
| `audio/` | El podcast. |
| `video/` | Las tres partes del video. |
| `PROMPTS.md` | Los prompts con los que se generaron las imágenes. |
| `README.md` | Esto. |

La página se republica sola con GitHub Pages cada vez que se hace un push a `main`.

---

## Contenido

- **Portada** — podcast, mapa mental y video general
- **Tema 01** — Introducción a los SOD: definición, SOR vs SOD, conceptos básicos, evolución histórica
- **Tema 02** — Modelos y Arquitecturas: estilos arquitectónicos y modelos fundamentales
- **Tema 03** — Redes de Interconexión: PAN/LAN/MAN/WAN y las cuatro topologías
- **Tema 04** — Cliente-Servidor y Peer to Peer, con tabla comparativa
- **Tema 05** — Características clave de diseño: los ocho tipos de transparencia y el resto
- **Tema 06** — Funciones y Servicios, y los objetivos de diseño
- **Cierre** — síntesis y bibliografía

Los diagramas de las cuatro topologías de red y el de Cliente-Servidor vs P2P están dibujados en código dentro de la página, así que no dependen de las imágenes.
