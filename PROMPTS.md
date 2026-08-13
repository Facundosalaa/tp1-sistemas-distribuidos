# Prompts de las 8 imágenes

Estos prompts están escritos para que las imágenes salgan con **la misma paleta y el mismo lenguaje visual que la página**. Si se generan con otro estilo, van a chocar contra el diseño.

## Antes de empezar

1. **Generá las 8 en el mismo chat, una atrás de otra.** Así el modelo mantiene la línea. Si abrís un chat nuevo para cada una, van a salir distintas entre sí.
2. **Copiá el bloque de estilo completo** (el de abajo) al principio de cada prompt. Sí, las ocho veces.
3. Si una sale con colores de más (violeta, celeste, verde, naranja), pedile: *"rehacela usando únicamente blanco, negro, azul #1A1AE5 y amarillo #EBFF00"*.
4. Guardalas en `img/` con el nombre que dice cada una.

---

## Bloque de estilo (va al principio de los 8 prompts)

```
ESTILO OBLIGATORIO:
Ilustración vectorial plana, estilo póster suizo / diseño gráfico internacional.
Paleta estricta de 4 colores únicamente: fondo blanco puro #FFFFFF, negro #0A0A0A,
azul ultramarino #1A1AE5 y amarillo ácido #EBFF00. Ningún otro color.
Colores planos y sólidos.
PROHIBIDO: degradados, sombras, brillos, resplandores, texturas, efectos 3D,
perspectiva isométrica, reflejos, personas realistas, iconos de stock.
Formas geométricas duras y simples: rectángulos, cuadrados, círculos y líneas rectas.
Cada computadora o nodo se representa como un rectángulo o cuadrado simple, no como
un dibujo detallado de un monitor.
Las conexiones son líneas rectas, preferentemente en ángulo recto (horizontal y
vertical), como un diagrama de circuito o un esquema técnico.
Grosor de línea uniforme.
Sin texto dentro de la imagen, o como máximo una o dos palabras en mayúsculas.
Composición horizontal 16:9, alineada a una grilla, con mucho espacio en blanco.
```

---

## 1 · `img/mapa-mental.png`

> **Portada de la página**

```
[BLOQUE DE ESTILO]

CONTENIDO:
Mapa mental de "Fundamentos de los Sistemas Operativos Distribuidos".
Un rectángulo azul ultramarino grande en el centro-izquierda representa el tema
principal. De él salen seis líneas rectas en ángulo recto hacia seis rectángulos
negros más chicos, ordenados en una columna a la derecha, uno por cada tema:
introducción, arquitecturas, redes, cliente-servidor y P2P, características de
diseño, y funciones y servicios.
De dos o tres de esos rectángulos salen a su vez dos ramas cortas más finas.
Estructura de árbol clara y ordenada, alineada a una grilla, no un diagrama
orgánico ni radial.
```

---

## 2 · `img/tema1.png` — Introducción a los SOD

```
[BLOQUE DE ESTILO]

CONTENIDO:
Cuatro cuadrados negros iguales, separados entre sí, distribuidos sobre un fondo
blanco y conectados por líneas rectas en ángulo recto que forman un circuito
cerrado entre los cuatro.
Sobre las líneas, tres pequeños cuadrados azul ultramarino representan mensajes
viajando entre los nodos.
Un rectángulo grande de contorno fino, dibujado con línea punteada, rodea a los
cuatro cuadrados: representa que todos juntos forman un único sistema.
Sin servidor central. Sin jerarquía: los cuatro son idénticos y del mismo tamaño.
```

---

## 3 · `img/tema2.png` — Modelos y Arquitecturas

```
[BLOQUE DE ESTILO]

CONTENIDO:
Composición dividida en dos mitades exactas por una línea vertical negra fina.

Mitad izquierda: tres cuadrados negros alineados en una columna a la izquierda,
cada uno conectado por líneas en ángulo recto a un único rectángulo azul
ultramarino grande ubicado a la derecha. Las líneas llevan flechas que apuntan
hacia el rectángulo azul. Es una arquitectura centralizada.

Mitad derecha: cuatro cuadrados azul ultramarino iguales dispuestos en las
esquinas de un cuadrado imaginario, conectados todos contra todos con líneas
rectas de flechas dobles. Sin ningún elemento central. Es una arquitectura
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
iguales, separadas por líneas verticales negras finas.

Columna 1, BUS: una línea horizontal negra gruesa, con cuatro cuadrados negros
colgando de ella por líneas verticales cortas.
Columna 2, ANILLO: seis cuadrados negros dispuestos formando un hexágono,
conectados en círculo cerrado.
Columna 3, ESTRELLA: un rectángulo azul ultramarino en el centro y cinco
cuadrados negros alrededor, cada uno conectado al centro por una línea recta.
Columna 4, MALLA: cinco cuadrados negros conectados todos contra todos por
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

Paso 1: un cuadrado negro (el cliente) del que sale una flecha gruesa hacia la
derecha, con un cuadrado azul ultramarino sobre la flecha representando la
solicitud viajando.
Paso 2: la flecha atraviesa una zona de red, representada por una franja
vertical de líneas horizontales paralelas finas.
Paso 3: un rectángulo azul ultramarino alto y vertical (el servidor) que devuelve
una flecha hacia la izquierda con un cuadrado amarillo ácido encima,
representando la respuesta.

Los tres pasos numerados con dígitos grandes 1, 2, 3 en negro, arriba de cada
etapa. Las flechas de ida y de vuelta deben distinguirse claramente.
```

---

## 6 · `img/tema5.png` — Características de Diseño

```
[BLOQUE DE ESTILO]

CONTENIDO:
Composición en tres bloques horizontales separados por líneas verticales negras
finas, cada uno ilustrando una idea.

Bloque 1, TRANSPARENCIA: un círculo negro (una persona, representada de forma
totalmente abstracta y geométrica) mirando hacia un rectángulo grande de
contorno punteado que contiene cuatro cuadrados chicos adentro. La persona ve
un solo rectángulo, aunque adentro haya varios.

Bloque 2, ESCALABILIDAD: cuatro cuadrados negros conectados, y un quinto
cuadrado amarillo ácido acercándose desde afuera con una flecha, sumándose a la
red.

Bloque 3, TOLERANCIA A FALLOS: cuatro cuadrados conectados donde uno está
dibujado como cuadrado vacío con una cruz X adentro, y sus líneas de conexión
son punteadas. Los otros tres siguen conectados con líneas sólidas entre sí.
```

---

## 7 · `img/tema6.png` — Funciones y Servicios

```
[BLOQUE DE ESTILO]

CONTENIDO:
Composición dividida horizontalmente en dos franjas por una línea negra gruesa.

Franja superior, más chica: un círculo negro (una persona, abstracta y
geométrica) frente a un único rectángulo azul ultramarino grande y limpio. Lo
que el usuario ve.

Franja inferior, más grande: seis cuadrados negros de distintos tamaños
conectados entre sí por líneas rectas en ángulo recto, con pequeños cuadrados
azules sobre las líneas representando mensajes. Lo que hay realmente por debajo.

Una flecha vertical fina conecta la franja de arriba con la de abajo, mostrando
que el rectángulo único de arriba es en realidad toda la red de abajo.
```

---

## 8 · `img/cierre.png` — Síntesis

```
[BLOQUE DE ESTILO]

CONTENIDO:
Una única escena que resume todo el eje, sobre fondo blanco y muy espaciada.

A la izquierda, un grupo de tres cuadrados negros conectados a un rectángulo
azul ultramarino: funcionan como cliente-servidor.
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
