# 🎨 Intro Canvas 2D con Programación Orientada a Objetos

Proyecto web que demuestra el uso de **Canvas 2D en JavaScript** utilizando **Programación Orientada a Objetos (OOP)** para crear y renderizar círculos.

La aplicación muestra tres ejemplos:

* Un **objeto círculo fijo**
* Un **círculo generado aleatoriamente**
* **Múltiples círculos aleatorios**

El objetivo es comprender cómo crear objetos gráficos reutilizables utilizando clases en JavaScript.

---

# 📷 Vista del proyecto

El proyecto contiene tres canvas:

1. **Objeto 2D**
   Muestra un círculo centrado en el canvas.

2. **Objeto con Random**
   Genera un círculo en una posición aleatoria dentro del canvas.

3. **Múltiples objetos**
   Genera varios círculos con posiciones, radios y colores aleatorios.

---

# 🧠 Conceptos aplicados

Este proyecto utiliza los siguientes conceptos de programación:

* HTML5 Canvas
* JavaScript ES6
* Programación Orientada a Objetos
* Clases
* Métodos
* Arreglos de objetos
* Generación de valores aleatorios
* Manipulación del DOM
* Bootstrap para el diseño

---

# 📂 Estructura del proyecto

```
intro-poo-canvas
│
├── index.html
│
├── assets
│   ├── css
│   │   └── style.css
│   │
│   ├── image
│   │   └── circle-1.png
│   │
│   └── js
│       └── main.js
```

---

# ⚙️ Funcionamiento del código

## Clase `Circle`

Se creó una clase que representa un círculo dentro del canvas.

```javascript
class Circle {
  constructor(x, y, radius, color, text, backcolor, textcolor)
```

### Propiedades

* **posX** → posición X del círculo
* **posY** → posición Y del círculo
* **radius** → radio del círculo
* **color** → color del borde
* **text** → texto mostrado en el centro
* **backcolor** → color de relleno
* **textcolor** → color del texto

---

## Método `draw()`

Este método se encarga de renderizar el círculo en el canvas.

Pasos que realiza:

1. Dibuja el arco del círculo
2. Rellena el círculo
3. Dibuja el borde
4. Coloca el texto en el centro

---

# 🎲 Generación de colores aleatorios

Se utiliza una función para generar colores RGB aleatorios.

```javascript
function randomColor(){
  let r = Math.floor(Math.random() * 256);
  let g = Math.floor(Math.random() * 256);
  let b = Math.floor(Math.random() * 256);

  return `rgb(${r},${g},${b})`;
}
```

Esto permite que cada círculo tenga un color diferente.

---

# 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/intro-poo-canvas.git
```

2. Abrir la carpeta del proyecto.

3. Ejecutar el archivo:

```
index.html
```

No se requieren dependencias adicionales.

---

# 🎓 Objetivo educativo

Este proyecto fue desarrollado como ejemplo para aprender:

* Cómo usar **Canvas 2D**
* Cómo aplicar **Programación Orientada a Objetos en JavaScript**
* Cómo trabajar con **objetos gráficos dinámicos**

---

# 📌 Posibles mejoras

Algunas mejoras que pueden implementarse:

* Animación de los círculos
* Evitar que los círculos se encimen
* Generar círculos al hacer clic
* Agregar controles de usuario
* Crear figuras adicionales (rectángulos, triángulos, etc.)

---

# 👨‍💻 Autor

Proyecto educativo para prácticas de **JavaScript y Canvas 2D**.