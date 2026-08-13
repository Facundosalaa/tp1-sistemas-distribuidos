# TP1 · Sistemas Operativos Distribuidos

Página web del **Eje Temático 1 — Fundamentos de los Sistemas Operativos Distribuidos**.

Es un solo archivo (`index.html`) con todo adentro: HTML, estilos y JavaScript. No hay que instalar nada ni compilar nada.

---

## Cómo cargar el material

Todo se configura en un solo lugar. Abrí `index.html`, buscá el bloque `const CONFIG = {` (está casi al final, dentro del `<script>`) y completá lo que tengas. **No hace falta tocar nada más.**

```js
const CONFIG = {
  integrantes: ["Nombre 1", "Nombre 2", "Nombre 3"],

  podcast: {
    src: "audio/podcast.mp3",
    duracion: "2 min"
  },

  video: {
    url: "https://youtu.be/XXXXXXXXXXX",
    duracion: "5 min"
  },

  imagenes: {
    mapaMental: "img/mapa-mental.png",
    tema1:      "img/tema1.png",
    tema2:      "img/tema2.png",
    tema3:      "img/tema3.png",
    tema4:      "img/tema4.png",
    tema5:      "img/tema5.png",
    tema6:      "img/tema6.png",
    cierre:     "img/cierre.png"
  }
};
```

Lo que dejes vacío (`""`) no rompe nada: muestra un recuadro que dice qué va en ese lugar.

### Imágenes

Van en la carpeta `img/`. Con estos nombres exactos:

| Archivo | Dónde aparece |
|---|---|
| `mapa-mental.png` | Portada |
| `tema1.png` | Tema 01 · Introducción a los SOD |
| `tema2.png` | Tema 02 · Modelos y Arquitecturas |
| `tema3.png` | Tema 03 · Redes de Interconexión |
| `tema4.png` | Tema 04 · Cliente-Servidor y P2P |
| `tema5.png` | Tema 05 · Características de Diseño |
| `tema6.png` | Tema 06 · Funciones y Servicios |
| `cierre.png` | Sección final |

Formato horizontal (16:9 va perfecto). Si pesan más de 2 MB, pasalas por [squoosh.app](https://squoosh.app) antes de subirlas.

### Podcast

Va en `audio/podcast.mp3`. Si tiene otro nombre, cambiá `CONFIG.podcast.src`.

### Video

**No lo subas al repo**, pesa demasiado. Subilo a YouTube como *no listado* y pegá el link en `CONFIG.video.url`. Acepta cualquiera de estos formatos y los convierte solo:

- `https://www.youtube.com/watch?v=XXXXXXXXXXX`
- `https://youtu.be/XXXXXXXXXXX`
- `https://drive.google.com/file/d/ID/view`

---

## Cómo se ve

La página se publica sola con GitHub Pages cada vez que se hace un push a `main`.

---

## Cómo ponerla en Google Sites

En Google Sites: **Insertar → Insertar código → Por URL**, y pegás la dirección de GitHub Pages.

Importante: usar la opción **por URL** y no pegar el código a mano. Las imágenes y el audio están referenciados con rutas relativas (`img/…`, `audio/…`), y esas rutas sólo funcionan si la página se sirve desde su propia dirección.

---

## Qué hay en cada archivo

| Archivo | Qué es |
|---|---|
| `index.html` | La página. Es lo único que importa. |
| `img/` | Las imágenes del eje. |
| `audio/` | El podcast. |
| `README.md` | Esto. |

---

## Contenido de la página

- **Portada** — podcast, mapa mental y video general
- **Tema 01** — Introducción a los SOD: definición, SOR vs SOD, conceptos básicos, evolución histórica
- **Tema 02** — Modelos y Arquitecturas: estilos arquitectónicos y modelos fundamentales
- **Tema 03** — Redes de Interconexión: PAN/LAN/MAN/WAN y las cuatro topologías
- **Tema 04** — Cliente-Servidor y Peer to Peer, con tabla comparativa
- **Tema 05** — Características clave de diseño: los ocho tipos de transparencia y el resto
- **Tema 06** — Funciones y Servicios, y los objetivos de diseño
- **Cierre** — síntesis y bibliografía

Los diagramas de las cuatro topologías de red y el de Cliente-Servidor vs P2P están dibujados en código dentro de la página, así que no dependen de las imágenes.
