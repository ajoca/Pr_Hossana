# Proyecto Hossana

Sistema web en **PHP + MySQL** para la gestión de una tienda con carrito de compras, administración de inventario y ventas, manejo de usuarios por roles y generación de reportes en PDF.

## 🚀 Características

- Catálogo de productos por categorías.
- Carrito de compras con actualización por AJAX.
- Registro y gestión de usuarios (Admin, Vendedor, Cliente).
- Panel de administración con control de inventario y ventas.
- Generación de reportes en PDF con **FPDF**.
- Sistema de login y control de acceso por roles.

## 🛠️ Tecnologías utilizadas

- **PHP 8.x**
- **MySQL/MariaDB**
- **Bootstrap 5**
- **FPDF**
- **jQuery**

## 📂 Estructura principal

```
ProyectoHossana/
├─ Config/              # Conexión y configuración
├─ Controller/          # Lógica y controladores
├─ Views/               # Vistas públicas y del panel admin
├─ pdf/                 # Generación de reportes PDF
├─ Assets/              # CSS, JS, imágenes
└─ gestion_hosanna.sql  # Base de datos
```

## ⚙️ Instalación

1. Clonar o descargar el repositorio en tu carpeta de servidor web:
   ```bash
   git clone https://github.com/usuario/ProyectoHossana.git
   ```
2. Crear la base de datos e importar el archivo:
   ```bash
   gestion_hosanna.sql
   ```
3. Configurar las credenciales de base de datos en:
   - `Config/conexion.php`
   - `Views/pagina/configuracion/database.php`
4. Asegurarte de tener Apache y MySQL ejecutándose.
5. Acceder en el navegador:
   - Página principal: `http://localhost/ProyectoHossana/`
   - Login: `http://localhost/ProyectoHossana/Views/public/iniciar.php`

## 👤 Usuarios de prueba

En el archivo SQL se incluyen usuarios de ejemplo.  
**Admin**:  
Correo: `info@alancanto.net`  
Contraseña: `admin`

## 📄 Licencia

Este proyecto se desarrolla con fines educativos.
