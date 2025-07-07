## ✅ ACTIVIDAD 4 – Soy nuevo y aprendí Java… ¿y ahora qué con HTML, CSS y JS?

**🎯 Objetivo:** Dar una primera mirada sencilla a HTML, CSS y JavaScript.


**📋 Instrucciones:**
1. Investiga:
   - ¿Qué hace **HTML** en una web?
   - ¿Para qué sirve **CSS**?
   - ¿Qué aporta **JavaScript**?

## ✅ **1. ¿Qué hace cada tecnología?**

### 🧱 **HTML (HyperText Markup Language)**
* **¿Qué hace?** Define la **estructura** de una página web.
* **Ejemplo:** Encabezados, párrafos, imágenes, listas, formularios.
* **Metáfora:** Es el esqueleto de la web.

```html
<h1>Bienvenida a mi sitio</h1>
<p>Este es un párrafo de ejemplo.</p>
```

### 🎨 **CSS (Cascading Style Sheets)**
* **¿Para qué sirve?** Aplica **estilos visuales**: colores, tamaños, márgenes, animaciones.
* **Metáfora:** Es la ropa y el maquillaje del HTML.

```css
h1 {
  color: teal;
  font-family: 'Arial';
}
```

### ⚙️ **JavaScript**
* **¿Qué aporta?** Agrega **interactividad**: botones que responden, formularios que validan, contenido que cambia sin recargar.
* **Metáfora:** Es el cerebro o los reflejos de la página.

```javascript
document.querySelector("h1").addEventListener("click", () => {
  alert("¡Hola desde JavaScript!");
});
```
2. Compara Java y JavaScript brevemente: ¿en qué se parecen y en qué se diferencian?

## 🔄 **2. Java vs JavaScript: ¿en qué se parecen y en qué no?**

| Característica | Java | JavaScript |
|----------------|------|------------|
| **Tipo de lenguaje** | Compilado, orientado a objetos | Interpretado, orientado a eventos |
| **Uso principal** | Aplicaciones backend, móviles (Android) | Web frontend y backend (con Node.js) |
| **Sintaxis** | Similar a C, más estricta | Más flexible y dinámica |
| **Ejecución** | En la JVM (Java Virtual Machine) | En el navegador o Node.js |
| **Relación entre ellos** | Solo el nombre es parecido 😉 |



3. Redacta un pequeño README explicando estas tecnologías con tus propias palabras.
   - Puedes incluir ejemplos o mini bloques de código si lo deseas.

## 📘 **3. Mini README – HTML, CSS y JavaScript**

```markdown
# 🌐 Mi primer vistazo al desarrollo web

Este proyecto es una introducción a las tres tecnologías fundamentales del desarrollo web:

## 🧱 HTML
Define la estructura de la página. Es como el esqueleto del sitio.

## 🎨 CSS
Aplica estilos visuales. Permite que la web se vea bonita y adaptada a distintos dispositivos.

## ⚙️ JavaScript
Agrega interactividad. Permite que los elementos respondan a acciones del usuario.

## 💡 Ejemplo combinado

```html
<!DOCTYPE html>
<html>
  <head>
    <style>
      h1 { color: darkblue; }
    </style>
  </head>
  <body>
    <h1>¡Hola, mundo!</h1>
    <button onclick="alert('¡Haz hecho clic!')">Haz clic</button>
  </body>
</html>
```

Este ejemplo muestra cómo HTML, CSS y JS trabajan juntos para crear una experiencia web completa.
```