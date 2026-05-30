# 🚀 Desafío Web: Matemáticas en el Mundo Real
### Proyecto: Fibonacci y Números Primos en la Vida Real

Este proyecto consiste en una aplicación web interactiva que aplica conceptos matemáticos avanzados para resolver y analizar situaciones del mundo real, cumpliendo con los criterios del Desafío Web 2025.

---

## 📋 Respuestas al Cuestionario de Planificación (Rúbrica)

### 1. ¿Qué problema real voy a resolver?
El proyecto resuelve la necesidad de proyectar modelos de crecimiento financiero (planes de ahorro automatizados basados en la sucesión de Fibonacci) y analizar la distribución y seguridad de datos numéricos mediante la identificación de números primos (aplicables en criptografía y validación).

### 2. ¿Usará Fibonacci, números primos o ambos?
Se utilizan **ambos** conceptos matemáticos de manera simultánea e interactiva para demostrar sus aplicaciones prácticas en diferentes paneles de la interfaz.

### 3. ¿Qué datos ingresará el usuario?
El usuario interactúa mediante formularios donde ingresa:
- La cantidad de meses para el cálculo del plan de ahorro.
- Rangos numéricos o valores específicos para verificar propiedades matemáticas.

### 4. ¿Qué resultado debe mostrar la página?
La página despliega de forma dinámica:
- Tablas organizadas con el progreso del ahorro mes a mes.
- Alertas visuales indicando si un número generado pertenece a la serie Fibonacci o si es un número primo.
- Diagramas de flujo interactivos que guían al usuario.

### 5. ¿Cómo explicaré el algoritmo en lenguaje sencillo?
- **Fibonacci:** Funciona como una bola de nieve. El sistema toma los ahorros de los dos meses anteriores y los suma para calcular el total del mes actual. Así, el crecimiento se acelera automáticamente en cada paso.
- **Números Primos:** El sistema intenta dividir el número seleccionado por cualquier otro número más pequeño (excepto el 1 y sí mismo). Si descubre que no se puede dividir de forma exacta por ningún otro, lo corona como número primo.

### 6. ¿Cómo haré que la página se vea bien en celular y computadora?
Se implementó un diseño responsivo utilizando CSS moderno (Flexbox, CSS Grid y Media Queries). Los paneles se apilan verticalmente en pantallas móviles para mantener la legibilidad y se expanden horizontalmente en pantallas de escritorio para aprovechar el espacio.

---

## 🛠️ Tecnologías Utilizadas
- **HTML5:** Estructuración semántica del sitio.
- **CSS3:** Diseño estilo *Dark Mode* con acentos neón y animaciones fluidas (*Scroll Reveal*).
- **JavaScript (Vanilla):** Lógica de los algoritmos y manipulación dinámica del DOM mediante `document.getElementById()`.
