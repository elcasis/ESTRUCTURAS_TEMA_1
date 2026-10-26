# ☕ POO Quest: ¿Clase, Objeto, Atributo o Método? — Juego Web de Java

Aplicación web educativa y gamificada en **un único archivo autónomo (`index.html`)**, lista para publicar directamente en **GitHub Pages** y diseñada específicamente con enfoque **Mobile-First** para jugar desde el teléfono móvil.

---

## ✨ ¿Qué puede hacer el programa?

### 1. Chuleta Visual Interactiva en Portada (Los 4 Pilares de POO)
Antes de empezar la partida, el alumno dispone de un resumen visual con código de colores neón sobre fondo negro para distinguir de un vistazo los **4 conceptos clave** de la Programación Orientada a Objetos (POO) en Java:
- 📐 **1. CLASE (`class`)**: El molde general, plano o plantilla que define cómo serán las cosas de ese tipo (*ej. `Perro`, `Coche`, `Alumno`*).
- 🧸 **2. OBJETO (`new`)**: El ejemplar concreto, único e individual creado a partir de la clase (*ej. `Mi perro Toby`, `El Seat Ibiza 4589-KLM`, `La alumna Laura`*).
- 🏷️ **3. ATRIBUTO (*variable / dato*)**: La característica, cualidad o propiedad que describe a cada objeto (*ej. `El color de un perro`, `La velocidad máxima`, `La nota media`*).
- ⚡ **4. MÉTODO (`accion()`)**: La acción, verbo o comportamiento que el objeto sabe realizar y que en Java siempre lleva paréntesis `()` (*ej. `ladrar()`, `acelerar()`, `llamarPorTelefono()`*).

---

### 2. Parte 1: 21 Preguntas con Comparaciones de la Vida Real
- Incluye **exactamente 21 preguntas** distribuidas entre los 4 conceptos (**Clase, Objeto, Atributo y Método**) con situaciones cotidianas (animales, coches, teléfonos móviles, universidad, videojuegos RPG, cuentas bancarias y moldes de cocina), incluyendo el ejemplo: *«¿El color de un perro qué es?»* o *«¿La acción de ladrar() o acelerar() qué es?»*.
- **Orden 100% Aleatorio y Sin Repetición**: Cada vez que se inicia una partida, las 21 preguntas se barajan mediante el algoritmo **Fisher-Yates**, asegurando que salgan siempre en distinto orden y nunca se repitan.
- **Explicación Pedagógica Inmediata**: Al pulsar cualquiera de los 4 botones (`Clase`, `Objeto`, `Atributo` o `Método`), el juego indica al instante por qué es correcta o incorrecta antes de pasar a la siguiente.

---

### 3. Parte 2: Cazador de Código Java (Marcar los 4 Elementos)
- Tras superar las 21 preguntas de la realidad (o entrando directamente desde el menú principal), el jugador pasa a analizar **fragmentos reales de código Java** (`Perro.java`, `Coche.java`, `Smartphone.java`, `Alumno.java`, `CuentaBancaria.java`, `PersonajeRPG.java`, `Libro.java`, `Cafetera.java`), también barajados de forma aleatoria y sin repetición.
- **Interacción táctil paso a paso en el código (4 Pasos)**:
  1. **Paso 1/4**: Tocar en el código el identificador de la **CLASE** (`public class ...`).
  2. **Paso 2/4**: Tocar en el código el identificador del **ATRIBUTO** declarado dentro de la clase.
  3. **Paso 3/4**: Tocar en el código el identificador del **MÉTODO** (acción con `()`).
  4. **Paso 4/4**: Tocar en el código el identificador del **OBJETO** instanciado con `new`.
- **Distractores inteligentes**: Los fragmentos de código incluyen tipos de datos (`int`, `double`, `String`) y valores literales (`"¡Guau!"`, `120`, `8.75`). Si el alumno toca uno por error, el programa le explica exactamente por qué ese elemento no es lo que busca.

---

### 4. Sistema de Puntuación, Rachas y Trofeos
- **Marcador superior en vivo (HUD)**: Muestra los **Puntos**, la **Racha de aciertos seguidos (`🔥`)**, el total de **Aciertos a la primera** y una barra de progreso animada.
- **Bonificación por Racha**: Cuantos más aciertos consecutivos consiga el jugador sin fallar, mayor es la bonificación de puntos por pregunta.
- **Rangos y Medallas Finales**: Al terminar, calcula la precisión global y otorga un rango (*👑 Arquitecto Supremo de Java*, *🥇 Programador Senior POO*, *🥈 Programador Junior en Ascenso* o *🥉 Aprendiz de Java*).

---

### 5. Estilo Black, Selector de Tamaño de Fuente y Audio Sintetizado
- **Estilo Black (`#050609` / `#0e1118`)**: Tema oscuro puro que ahorra batería en pantallas OLED de móviles y evita la fatiga visual, con acentos neón de alto contraste (azul cian para Clase, morado para Objeto, ámbar para Atributo y verde esmeralda para Método).
- **Selector de Tamaño de Fuente en Tiempo Real (`A-`, `A`, `A+`, `A++`)**: Barra accesible en todo momento en la parte superior para ajustar el tamaño de toda la interfaz y del código Java a la vista del usuario en su móvil. La preferencia queda guardada automáticamente en `localStorage`.
- **Efectos de Sonido Web Audio API (`🔊` / `🔇`)**: Sonidos de acierto, fallo y superación de nivel generados por código sin necesidad de archivos `.mp3` externos.

---

## 🚀 Cómo subirlo a GitHub Pages

1. Crea un repositorio nuevo en tu cuenta de **GitHub**.
2. Sube el archivo [`index.html`](file:///c:/Users/elcas/Desktop/APP_Antigravity/Juego_Java_POO/index.html) y este archivo [`README.md`](file:///c:/Users/elcas/Desktop/APP_Antigravity/Juego_Java_POO/README.md).
3. Entra en **Settings ➔ Pages**, elige la rama `main` (carpeta `/root`) y pulsa **Save**.
4. En unos segundos tendrás tu enlace web listo para abrir desde el navegador de tu teléfono móvil.
