# 🧠 Quiz Web en HTML

## 📌 Descripción

Este proyecto consiste en una página web de tipo quiz (cuestionario) desarrollada con HTML. Permite mostrar preguntas con múltiples opciones de respuesta para que el usuario seleccione la opción correcta.

El objetivo principal es practicar la estructura básica de una página web y la creación de formularios interactivos.

---

## 🚀 Características

* Estructura básica en HTML5
* Preguntas con opciones tipo selección (radio buttons)
* Botón para enviar respuestas
* Diseño simple y fácil de entender
* Base para agregar estilos (CSS) y lógica (JavaScript)

---

## 🛠️ Tecnologías utilizadas

* HTML5

---

## 📂 Estructura del proyecto

```
quiz/
│── index.html
│── README.md
```

---

## 🧩 Funcionamiento

El archivo `index.html` contiene:

* Un título principal del quiz
* Una pregunta
* Varias opciones de respuesta
* Un botón para enviar

Actualmente, el quiz no valida respuestas automáticamente, pero puede mejorarse agregando JavaScript para calcular resultados y mostrar retroalimentación.

---

## 💡 Ejemplo de código

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Quiz Simple</title>
</head>
<body>
  <h1>Quiz de Cultura General</h1>
  <p>Responde la siguiente pregunta:</p>

  <form>
    <p>¿Cuál es la capital de Colombia?</p>
    <label><input type="radio" name="pregunta1"> Medellín</label><br>
    <label><input type="radio" name="pregunta1"> Bogotá</label><br>
    <label><input type="radio" name="pregunta1"> Cali</label><br><br>

    <button type="submit">Enviar</button>
  </form>
</body>
</html>
```

---

## 🔮 Posibles mejoras

* Agregar estilos con CSS 🎨
* Implementar validación con JavaScript ⚡
* Mostrar puntaje final
* Añadir múltiples preguntas
* Hacer el diseño responsive

---

## 👨‍💻 Autor

Proyecto creado con fines educativos.

---
