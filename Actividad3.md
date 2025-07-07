## ✅ ACTIVIDAD 3 – Explorando las herramientas de desarrollo

**🎯 Objetivo:** Familiarizarse con las DevTools del navegador.


**📋 Instrucciones:**
1. Investiga cómo abrir DevTools en tu sistema operativo:
   - **Windows:** `F12` o `Ctrl + Shift + I`
   - **Linux:** `Ctrl + Shift + I`
   - **Mac:** `Cmd + Option + I`

## 🧭 **1. Cómo abrir DevTools según tu sistema operativo**

| Sistema Operativo | Atajo de teclado |
|-------------------|------------------|
| **Windows** | `F12` o `Ctrl + Shift + I` |
| **Linux** | `Ctrl + Shift + I` |
| **Mac** | `Cmd + Option + I` |

También puedes hacer clic derecho sobre cualquier parte de la página y seleccionar **"Inspeccionar"**.


2. Explora las siguientes pestañas:
   - Elementos
   - Consola
   - Red (Network)
   - Almacenamiento (Storage)

## 🔍 **2. Explora estas pestañas clave**

| Pestaña | ¿Para qué sirve? |
|---------|------------------|
| **Elementos** | Muestra el HTML y CSS de la página. Puedes editar estilos en tiempo real. |
| **Consola** | Muestra errores, advertencias y mensajes de `console.log()` de JavaScript. |
| **Red** | Visualiza todas las solicitudes HTTP: archivos, imágenes, APIs, tiempos de carga. |
| **Almacenamiento** | Muestra cookies, localStorage, sessionStorage y bases de datos del navegador. |


3. Abre una web (ej: google.com), inspecciona y captura:
   - Una solicitud HTTP
   - Un error en consola (si aparece)
   - El HTML de un elemento

## 🌐 **3. Abre una web (ej: google.com) y captura:**

### ✅ Una solicitud HTTP
* Ve a la pestaña **Red (Network)**.
* Recarga la página (`F5`) y verás muchas solicitudes.
* Haz clic en una (por ejemplo, `googlelogo.png`) y captura su método (GET/POST), estado (200, 404), y tipo (documento, imagen, etc.).

### ⚠️ Un error en consola
* Ve a la pestaña **Consola (Console)**.
* Si hay errores, aparecerán en rojo. Captura uno (puede ser un `Uncaught ReferenceError` o algo similar).

### 🧱 El HTML de un elemento
* Ve a la pestaña **Elementos (Elements)**.
* Haz clic derecho sobre un botón o imagen y selecciona **"Inspeccionar"**.
* Se resaltará el código HTML correspondiente. Captura esa sección.