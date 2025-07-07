## ✅ ACTIVIDAD 2 – Anatomía de una aplicación web moderna

**🎯 Objetivo:** Comprender los componentes principales de una app web (frontend, backend, base de datos).

**📋 Instrucciones:**
1. Investiga los conceptos de:
   - Frontend
   - Backend
   - Base de datos

   ## 🧩 **1. Conceptos clave**



### ⚙️ **Backend**
* Es la parte **lógica y funcional** que ocurre en el servidor.
* Procesa datos, gestiona usuarios, valida formularios, ejecuta reglas de negocio.
* Tecnologías comunes: **Node.js, Java + Spring Boot, Python + Django**.

### 🗄️ **Base de datos**
* Es donde se **almacenan los datos** de la aplicación (usuarios, productos, mensajes, etc.).
* Puede ser relacional (como **MySQL, PostgreSQL**) o no relacional (como **MongoDB**).

2. Realiza un diagrama simple que muestre cómo se comunican entre sí.

## 🧠 **2. Diagrama simple en formato `mermaid`**

``` mermaid
graph TD
  A[👤 Usuario] --> B[🎨 Frontend (HTML/CSS/JS)]
  B --> C[⚙️ Backend (API / Lógica del servidor)]
  C --> D[🗄️ Base de datos (MySQL / PostgreSQL)]
  D --> C
  C --> B
  B --> A

Explicación:
Este diagrama muestra cómo fluye la información:
* El usuario interactúa con el **frontend**.
* El frontend envía solicitudes al **backend**.
* El backend consulta o guarda datos en la **base de datos**.
* Luego responde al frontend, que actualiza la vista para el usuario.