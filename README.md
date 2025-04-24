# 🏃 Taller Formularios HTML - Inscripción Atletismo Bucaramanga

## 🌟 ¡Bienvenido al Proyecto de Inscripción!

¡Gracias por revisar este proyecto! 🎉 Este es el resultado del Taller de Formularios HTML, enfocado en crear un formulario de inscripción semántico y funcional para una competencia de atletismo ficticia organizada por la Alcaldía de Bucaramanga.

Este proyecto demuestra la aplicación de HTML5 semántico para estructurar contenido web y la creación de formularios bien organizados y validados utilizando únicamente atributos HTML.

Los objetivos principales fueron:

- 🏗️ Construir una página con estructura semántica (header, nav, main, section, footer).
- 📝 Diseñar un formulario de inscripción detallado con campos relevantes.
- ✅ Implementar validaciones del lado del cliente usando atributos HTML.
- 🧩 Organizar el formulario lógicamente con `fieldset` y `legend`.
- 👍 Asegurar una buena estructura base para la accesibilidad y la experiencia de usuario.

¡Explora el código y la documentación para ver cómo se cumplieron estos requisitos! 🚀

---

## 🎯 ¿Qué es este Proyecto?

```
┌─────────────────────────────────────────────────────────────┐
│  📄  Página HTML Estática con Formulario de Inscripción     │
│  ────────────────────────────────────────────────────────  │
│                                                             │
│  🏛️ Estructura semántica con HTML5                          │
│  📝 Formulario detallado para inscripción a evento deportivo│
│  ✅ Validaciones integradas con atributos HTML              │
│  🧩 Agrupación lógica de campos con Fieldset/Legend         │
│  🏷️ Uso correcto de Labels para accesibilidad              │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

Este proyecto es una implementación práctica de los conceptos fundamentales de HTML5 aplicados a la creación de formularios web. Se enfoca puramente en la estructura y semántica HTML, sin incluir CSS externo ni JavaScript.

Características clave demostradas:

- 🎯 **HTML Semántico**: Uso correcto de etiquetas para definir la estructura.
- 📝 **Formulario Completo**: Inclusión de diversos tipos de input (`text`, `number`, `date`, `radio`, `email`, `tel`, `select`, `textarea`, `checkbox`).
- ✅ **Validación Nativa**: Uso de `required`, `pattern`, `min`, `type` para validaciones básicas sin necesidad de scripts.
- 🧩 **Organización Clara**: Uso de `fieldset` y `legend`.
- 🔗 **Accesibilidad Base**: Asociación explícita de `label` con `input` usando `for` e `id`.

## 📋 Tabla de Contenidos
- [🚀 Características HTML Implementadas](#-características-html-implementadas)
- [📂 Estructura del Proyecto](#-estructura-del-proyecto)
- [🛠️ Requisitos](#-requisitos)
- [📦 Visualización](#-visualización)
- [🚀 Uso](#-uso)
- [🎥 Archivos de Soporte (Guion/Explicación)](#-archivos-de-soporte-guionexplicación)
- [📱 Compatibilidad](#-compatibilidad)
- [💡 Puntos Clave del HTML](#-puntos-clave-del-html)
- [❓ Preguntas Frecuentes](#-preguntas-frecuentes)
- [🏆 Reconocimientos](#-reconocimientos)

## 🚀 Características HTML Implementadas
- 🏗️ **Estructura Semántica**: Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`.
- 📄 **Metadatos**: `<head>` con `<meta charset="UTF-8">`, `<meta name="viewport">`, `<title>`.
- 🔗 **Navegación Interna**: Uso de `<nav>` con enlaces `<a>` apuntando a IDs de secciones (`#evento`, `#inscripcion`).
- 📝 **Formulario**: Etiqueta `<form>` con `method="post"`.
- 🧩 **Agrupación**: `<fieldset>` y `<legend>` para organizar campos.
- 🏷️ **Etiquetas Accesibles**: `<label>` con atributo `for` asociado al `id` de cada campo.
- ⌨️ **Diversidad de Campos**: `<input>` (types: `text`, `number`, `date`, `radio`, `email`, `tel`, `checkbox`), `<select>` con `<option>`, `<textarea>`.
- ✅ **Validaciones Nativas**: Atributos `required`, `pattern="[0-9]{7,10}"`, `min="100000"`, y validación implícita por `type` (`email`, `date`, `number`).
- ✨ **Contenido**: Uso de `<h1>`, `<h2>`, `<p>`, `<strong>`.
- © **Caracteres Especiales**: Uso de `&copy;`.
- 😊 **Emojis**: Integrados en textos y títulos para mejorar el atractivo visual.

## 📂 Estructura del Proyecto
```
Proyecto Taller Formularios HTML/
│
├── 📄 index.html                  # El archivo principal con toda la página y el formulario
├── 📄 explicacion_html.txt       # Explicación detallada de las etiquetas y atributos usados
```

## 🛠️ Requisitos
- 🌐 Un navegador web moderno (Chrome, Firefox, Edge, Safari, etc.) que soporte HTML5.
- ❌ No se requiere instalación de software adicional, ni servidor web, ni dependencias.

## 📦 Visualización
Simplemente abre el archivo `index.html` directamente en tu navegador web preferido.

```bash
# Ejemplo en Linux/macOS:
open index.html

# Ejemplo en Windows (desde CMD o PowerShell):
start index.html
```
O haz doble clic sobre el archivo en tu explorador de archivos.

## 🚀 Uso
1.  Abre `index.html` en tu navegador.
2.  Observa la estructura de la página: cabecera, navegación, sección de detalles, formulario y pie de página.
3.  Interactúa con el formulario:
    *   Intenta enviarlo vacío para ver las validaciones `required`.
    *   Ingresa datos con formatos incorrectos (email, teléfono) para ver las validaciones de `type` y `pattern`.
    *   Selecciona opciones en los campos `radio` y `select`.
    *   Utiliza el campo `date` para ver el selector de fecha.
    *   Llena el formulario correctamente y envíalo (notarás que la página se recarga o no hace nada visiblemente, ya que `action="#"` y no hay backend).

## 🎥 Archivos de Soporte (Guion/Explicación)
- **`guion_video.txt`**: Contiene una guía paso a paso para grabar el video de presentación del proyecto, explicando la estructura, el formulario, las validaciones y la UX desde la perspectiva HTML.
- **`explicacion_html.txt`**: Ofrece una descripción detallada de cada etiqueta HTML y atributo utilizado en `index.html`, ideal para entender a fondo el código.

## 📱 Compatibilidad

### 💻 Sistemas Operativos
- 🪟 Windows
- 🍎 macOS
- 🐧 Linux

### 🌐 Navegadores
- Compatible con las versiones recientes de los principales navegadores que soportan HTML5.

## 💡 Puntos Clave del HTML

### ✅ Validaciones Nativas
- Aprovecha las validaciones integradas del navegador para mejorar la experiencia del usuario sin JavaScript.
- `required` asegura campos obligatorios.
- `type` (email, number, date, tel) valida formatos comunes.
- `pattern` permite validaciones personalizadas con expresiones regulares.
- `min` establece límites numéricos.

### 🏛️ Semántica y Accesibilidad
- Usar etiquetas semánticas (`header`, `main`, etc.) ayuda a los motores de búsqueda y tecnologías de asistencia a entender la estructura.
- La correcta asociación `<label for="id">` con `<input id="...">` es crucial para que los usuarios puedan hacer clic en las etiquetas y para los lectores de pantalla.
- `fieldset` y `legend` agrupan controles relacionados, mejorando la comprensión.

## ❓ Preguntas Frecuentes

### 💾 ¿Por qué no se guardan los datos al enviar el formulario?
El HTML solo define la *estructura* del formulario. Para guardar datos se necesita un *backend* (un lenguaje del lado del servidor como PHP, Python, Node.js, etc.) que reciba los datos enviados por el formulario (definido en el atributo `action`) y los procese (guardándolos en una base de datos, enviando un email, etc.). Este proyecto se enfoca únicamente en la parte HTML (frontend).

### 🤔 ¿Qué significa `action="#"` en el `<form>`?
Es un marcador de posición común. Indica que el formulario, al enviarse, debe apuntar a la misma página actual. Como no hay un script esperando para procesar los datos en esta página, usualmente solo causa que la página se recargue.

### 🎨 ¿Se puede mejorar la apariencia?
¡Definitivamente! La apariencia visual se controla con CSS (Cascading Style Sheets). Este proyecto intencionalmente no incluye CSS para enfocarse en la estructura HTML pura. Un siguiente paso natural sería crear un archivo `.css` y enlazarlo en el `<head>` para darle estilos, colores, márgenes, etc.

## 🏆 Reconocimientos

### 🎯 Logro del Proyecto
- ✅ Cumplimiento de todos los requisitos del Taller de Formularios HTML especificados.
- 📄 Creación de documentación de soporte (guion y explicación).

### 🙏 Agradecimientos
- A la entidad organizadora del taller por la propuesta del ejercicio.
- A las herramientas y recursos de desarrollo web que facilitan el aprendizaje y la creación.

---

Desarrollado como parte del Taller de Formularios HTML  ❤️ .

### 📄 Creado Por:
Este Proyecto fue desarrollado por: 
- 👨‍💻 **Daniel Santiago Vinasco**

---

### ✅ ¿Qué incluye este README?
✔ 🏃 Descripción del proyecto del formulario de inscripción.
✔ 📋 Características HTML implementadas.
✔ 📂 Estructura del proyecto simple y clara.
✔ 🛠️ Requisitos mínimos (solo navegador).
✔ 🚀 Instrucciones de visualización y uso.
✔ 💡 Puntos clave sobre HTML semántico y validaciones.
✔ ❓ Preguntas frecuentes sobre el funcionamiento. 

--- 

- 🔥 **¡Github: https://github.com/DanielSantiagoV !🚀**