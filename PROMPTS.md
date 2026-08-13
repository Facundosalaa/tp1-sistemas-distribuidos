# Prompts de las 8 imágenes

> **Las 8 imágenes ya están generadas y cargadas** en la carpeta `img/`. Este archivo queda como referencia por si hay que rehacer alguna o mantener el estilo en los ejes 2 y 3.

## Si tenés que rehacer una

1. Usá el bloque de estilo de abajo al principio del prompt, para que la imagen nueva combine con las siete que ya están.
2. Guardala en `img/` **con el mismo nombre** que la que reemplaza y listo, no hay que tocar el código.
3. Si necesitás varias de una, generalas todas en el mismo chat, una atrás de otra: si abrís un chat nuevo para cada una salen distintas entre sí.

---

## Bloque de estilo

La página tiene **fondo azul marino oscuro** con acentos en azul y violeta. Las imágenes tienen que salir en ese mismo mundo.

```
ESTILO OBLIGATORIO:
Ilustración técnica sobre fondo oscuro, estilo diagrama de red luminoso.
Fondo azul marino muy oscuro, casi negro (#070B14).
Las formas se dibujan con líneas finas luminosas en azul eléctrico (#5B8CFF)
y violeta (#A472FF), con un resplandor suave.
Las computadoras se representan como monitores simples de contorno fino, no
como dibujos detallados ni fotorrealistas.
Las conexiones son líneas o líneas punteadas con pequeños puntos de luz.
PROHIBIDO: fondo blanco o claro, fotografías, personas realistas, iconos de
stock, colores fuera de la gama azul-violeta (nada de rojo, verde, naranja
ni amarillo salvo un detalle mínimo).
Composición horizontal 16:9, ordenada, con bastante espacio vacío alrededor.
Poco texto o directamente sin texto.
```

---

## 1 · `img/mapa-mental.png`

> **Portada de la página**

```
[BLOQUE DE ESTILO]

CONTENIDO:
Mapa mental de "Fundamentos de los Sistemas Operativos Distribuidos".
Un rectángulo azul eléctrico grande en el centro-izquierda representa el tema
principal. De él salen seis líneas rectas blancas en ángulo recto hacia seis
rectángulos blancos más chicos, ordenados en una columna a la derecha, uno por
cada tema: introducción, arquitecturas, redes, cliente-servidor y P2P,
características de diseño, y funciones y servicios.
De dos o tres de esos rectángulos salen a su vez dos ramas cortas más finas.
Estructura de árbol clara y ordenada, alineada a una grilla, no un diagrama
orgánico ni radial.
```

---

## 2 · `img/tema1.png` — Introducción a los SOD

```
[BLOQUE DE ESTILO]

CONTENIDO:
Cuatro cuadrados blancos iguales, separados entre sí sobre el fondo oscuro,
conectados por líneas blancas rectas en ángulo recto que forman un circuito
cerrado entre los cuatro.
Sobre las líneas, tres pequeños cuadrados azul eléctrico representan mensajes
viajando entre los nodos.
Un rectángulo grande de contorno fino y punteado rodea a los cuatro cuadrados:
representa que todos juntos forman un único sistema.
Sin servidor central. Sin jerarquía: los cuatro son idénticos y del mismo tamaño.
```

---

## 3 · `img/tema2.png` — Modelos y Arquitecturas

```
[BLOQUE DE ESTILO]

CONTENIDO:
Composición dividida en dos mitades exactas por una línea vertical blanca fina.

Mitad izquierda: tres cuadrados blancos alineados en una columna a la izquierda,
cada uno conectado por líneas en ángulo recto a un único rectángulo azul
eléctrico grande ubicado a la derecha. Las líneas llevan flechas que apuntan
hacia el rectángulo azul. Es una arquitectura centralizada.

Mitad derecha: cuatro cuadrados azul eléctrico iguales dispuestos en las
esquinas de un cuadrado imaginario, conectados todos contra todos con líneas
blancas de flechas dobles. Sin ningún elemento central. Es una arquitectura
entre pares.

El contraste entre "todo apunta a uno" y "todos con todos" tiene que leerse de
un vistazo.
```

---

## 4 · `img/tema3.png` — Redes de Interconexión

```
[BLOQUE DE ESTILO]

CONTENIDO:
Cuatro topologías de red, dispuestas en una fila horizontal de cuatro columnas
iguales, separadas por líneas verticales blancas finas.

Columna 1, BUS: una línea horizontal blanca gruesa, con cuatro cuadrados blancos
colgando de ella por líneas verticales cortas.
Columna 2, ANILLO: seis cuadrados blancos dispuestos formando un hexágono,
conectados en círculo cerrado.
Columna 3, ESTRELLA: un rectángulo azul eléctrico en el centro y cinco
cuadrados blancos alrededor, cada uno conectado al centro por una línea recta.
Columna 4, MALLA: cinco cuadrados blancos conectados todos contra todos por
múltiples líneas.

Las cuatro estructuras deben verse claramente distintas entre sí y del mismo
tamaño visual. Todas ocupan la misma altura.
```

---

## 5 · `img/tema4.png` — Cliente-Servidor y P2P

```
[BLOQUE DE ESTILO]

CONTENIDO:
Diagrama de tres pasos en una fila horizontal, de izquierda a derecha, que
explica una petición cliente-servidor.

Paso 1: un cuadrado blanco (el cliente) del que sale una flecha gruesa hacia la
derecha, con un cuadrado azul eléctrico sobre la flecha representando la
solicitud viajando.
Paso 2: la flecha atraviesa una zona de red, representada por una franja
vertical de líneas horizontales paralelas finas.
Paso 3: un rectángulo azul eléctrico alto y vertical (el servidor) que devuelve
una flecha hacia la izquierda con un cuadrado amarillo ácido encima,
representando la respuesta.

Los tres pasos numerados con dígitos grandes 1, 2, 3 en blanco, arriba de cada
etapa. Las flechas de ida y de vuelta deben distinguirse claramente.
```

---

## 6 · `img/tema5.png` — Características de Diseño

```
[BLOQUE DE ESTILO]

CONTENIDO:
Composición en tres bloques horizontales separados por líneas verticales blancas
finas, cada uno ilustrando una idea.

Bloque 1, TRANSPARENCIA: un círculo blanco (una persona, representada de forma
totalmente abstracta y geométrica) mirando hacia un rectángulo grande de
contorno punteado que contiene cuatro cuadrados chicos adentro. La persona ve
un solo rectángulo, aunque adentro haya varios.

Bloque 2, ESCALABILIDAD: cuatro cuadrados blancos conectados, y un quinto
cuadrado amarillo ácido acercándose desde afuera con una flecha, sumándose a la
red.

Bloque 3, TOLERANCIA A FALLOS: cuatro cuadrados conectados donde uno está
dibujado como cuadrado vacío de contorno blanco con una cruz X adentro, y sus
líneas de conexión son punteadas. Los otros tres siguen conectados entre sí con
líneas sólidas.
```

---

## 7 · `img/tema6.png` — Funciones y Servicios

```
[BLOQUE DE ESTILO]

CONTENIDO:
Composición dividida horizontalmente en dos franjas por una línea blanca gruesa.

Franja superior, más chica: un círculo blanco (una persona, abstracta y
geométrica) frente a un único rectángulo azul eléctrico grande y limpio. Lo
que el usuario ve.

Franja inferior, más grande: seis cuadrados blancos de distintos tamaños
conectados entre sí por líneas rectas en ángulo recto, con pequeños cuadrados
azules sobre las líneas representando mensajes. Lo que hay realmente por debajo.

Una flecha vertical fina conecta la franja de arriba con la de abajo, mostrando
que el rectángulo único de arriba es en realidad toda la red de abajo.
```

---

## 8 · `img/cierre.png` — Síntesis

> **Atención:** esta es la única que va sobre **fondo claro**, porque la sección
> final de la página se invierte. Para esta imagen, cambiá en el bloque de estilo
> "fondo casi negro #0B0D12" por **"fondo hueso #F2F2ED"** y "blanco hueso
> #EDEFF4 para las formas" por **"negro #0A0A0A para las formas"**. El azul y el
> amarillo quedan igual.

```
[BLOQUE DE ESTILO, con fondo hueso #F2F2ED y formas en negro #0A0A0A]

CONTENIDO:
Una única escena que resume todo el eje, muy espaciada.

A la izquierda, un grupo de tres cuadrados negros conectados a un rectángulo
azul eléctrico: funcionan como cliente-servidor.
A la derecha, un grupo de cuatro cuadrados azules conectados todos contra
todos: funcionan como peer-to-peer.
Los dos grupos están unidos entre sí por dos o tres líneas largas en ángulo
recto, con cuadrados chicos encima representando mensajes que cruzan.
Uno de los cuadrados está dibujado vacío con una cruz X adentro y sus líneas
punteadas: cayó, pero el resto sigue conectado.
Un cuadrado amarillo ácido se acerca desde un borde con una flecha: un nodo
nuevo sumándose.

Composición amplia y ordenada, alineada a una grilla, sin saturar. Debe leerse
como un plano técnico, no como una ilustración decorativa.
```
