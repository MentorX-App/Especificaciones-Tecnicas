# 📄 Especificaciones Técnicas para el Despliegue

Este documento detalla los requisitos técnicos necesarios para el desarrollo y despliegue de la aplicación **MentorX**, incluyendo tanto el frontend (Flutter) como el backend (Node.js).

---

## 🛠️ Requisitos del Entorno de Desarrollo

### IDEs y Herramientas
| Herramienta         | Versión Requerida      |
|---------------------|------------------------|
| IntelliJ IDEA       | 2025.1.2               |
| Android Studio      | 2024.1.2 Patch 1       |
| Flutter             | 85.3.1                 |
| Node.js             | 22.14.0                |
| MySQL Workbench     | Última versión estable |

---

## 📱 Frontend

- **Framework:** Flutter  
- **Lenguaje:** Dart  
- **Entorno sugerido:** IntelliJ IDEA o Android Studio  
- **Uso:** Desarrollo de la aplicación móvil

---

## 🖥️ Backend

- **Entorno:** Node.js  
- **Lenguaje:** JavaScript (o TypeScript si aplica)  
- **Uso:** API REST y lógica de negocio de la aplicación

---

## 🗄️ Base de Datos

- **Motor de base de datos:** MySQL  
- **Herramienta de gestión recomendada:** MySQL Workbench  
- **Uso:** Almacenamiento de datos de usuarios, sesiones, y demás entidades del sistema

---

## ✅ Notas Adicionales

- Se recomienda clonar ambos repositorios (`flutter-app` y `backend-nodejs`) en carpetas independientes.
- Usar `.env` para configurar variables de entorno sensibles (como credenciales de base de datos o tokens de autenticación).
- No subir `node_modules/` ni `.env` al repositorio (ver archivo `.gitignore`).

---

