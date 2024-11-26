# Gestión de Usuarios

## Introducción
- **Nombre del Proyecto:** Gestión de Usuarios
- **Descripción:** Una aplicación CRUD para gestionar usuarios, permitiendo crear, leer, actualizar y eliminar registros de usuarios.
- **Tecnologías Utilizadas:** Node.js, Express, MongoDB, HTML, CSS, JavaScript

## Requisitos
- **Funcionales:**
    - Crear un nuevo usuario
    - Leer información de usuarios existentes
    - Actualizar información de un usuario
    - Eliminar un usuario
- **No Funcionales:**
    - **Seguridad:** Autenticación y autorización
    - **Rendimiento:** Respuesta rápida a las solicitudes
    - **Usabilidad:** Interfaz de usuario intuitiva

## Diseño del Sistema
- **Modelo de Datos**
    - Tabla Usuarios
```sql
CREATE TABLE Usuarios (
    id VARCHAR(255) PRIMARY KEY, 
    nombre VARCHAR(255) NOT NULL, 
    email VARCHAR(255) NOT NULL UNIQUE, 
    edad INT 
);
```
- **Arquitectura:**
    - **Frontend:** HTML, CSS, JavaScript
    - **Backend:** Node.js, Express
    - **Base de Datos:** MongoDB

## Despliegue

### Servidor
Sube tu aplicación a un servicio de alojamiento como Heroku o AWS.

### Mantenimiento
Monitorea la aplicación y realiza actualizaciones y correcciones de errores según sea necesario.

## Manual de Usuario

### Instrucciones
1. **Crear Usuario:** Completa el formulario de registro y haz clic en "Guardar".
2. **Leer Usuarios:** Navega a la página de usuarios para ver la lista completa.
3. **Actualizar Usuario:** Haz clic en "Editar" junto al usuario que deseas actualizar, modifica los datos y guarda los cambios.
4. **Eliminar Usuario:** Haz clic en "Eliminar" junto al usuario que deseas eliminar.