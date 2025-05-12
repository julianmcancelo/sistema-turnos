
# Sistema de Turnos para Peluquería

Sistema de gestión de turnos para una peluquería, desarrollado en **PHP** y **MySQL**. 
El objetivo principal es facilitar la administración de turnos y servicios, así como la gestión de clientes y estilistas desde un panel web.

## 📸 Captura de Pantalla (placeholder)
![Sistema de Turnos Placeholder](https://via.placeholder.com/800x400.png?text=Sistema+de+Turnos+Peluquer%C3%ADa)

## 🌟 Características Principales
- Registro e inicio de sesión de usuarios (clientes y estilistas).
- Gestión de turnos con selección de servicios y estilistas.
- Administración de servicios (alta, baja y modificación).
- Gestión de usuarios (alta de clientes y estilistas).
- Notificaciones por correo electrónico para confirmación de turnos.
- Panel de administración para gestionar el negocio.
- Calendarización de turnos con vista general.

## 💻 Requisitos del Sistema
- **Servidor Web:** Apache o Nginx.
- **PHP:** Versión 7.4 o superior.
- **Base de Datos:** MySQL o MariaDB.
- **Extensiones PHP:** mysqli, pdo, session, mail.
- **Composer:** Para cargar variables de entorno con Dotenv.
- **Navegador Web:** Compatible con Chrome, Firefox, Edge.

## 🚀 Instalación y Configuración
1. Clonar el repositorio:
```bash
git clone https://github.com/usuario/sistema-turnos-peluqueria.git
cd sistema-turnos-peluqueria
```

2. Instalar dependencias:
```bash
composer install
```

3. Crear el archivo `.env` en la carpeta `config/`:
```env
DB_HOST=localhost
DB_NAME=peluqueria
DB_USER=root
DB_PASSWORD=
```

4. Importar la base de datos:
```bash
mysql -u root -p peluqueria < database.sql
```

5. Iniciar el servidor:
```bash
php -S localhost:8000
```

6. Acceder al sistema desde el navegador:
[http://localhost:8000](http://localhost:8000)

## 📁 Estructura del Proyecto
```
/sistema-turnos-peluqueria/
├── css/                 # Archivos CSS para el estilo
├── js/                  # Archivos JavaScript para funcionalidades
├── img/                 # Imágenes del sistema
├── includes/            # Archivos PHP reutilizables (header, footer)
├── admin/               # Panel de administración
├── user/                # Panel del usuario
├── config/              # Configuración de conexión a la base de datos
│   └── config.php
├── docs/                # Documentación adicional
├── index.php            # Página principal
├── login.php            # Página de inicio de sesión
├── register.php         # Página de registro
├── database.sql         # Estructura de la base de datos
├── README.md            # Documentación del proyecto
├── .env                 # Archivo de configuración del entorno
├── .gitignore           # Archivos y carpetas a ignorar
├── CHANGELOG.md         # Registro de cambios del proyecto
├── CONTRIBUTING.md      # Guía para contribuir al proyecto
└── LICENSE.md           # Licencia del proyecto
```

## 📝 Contribuciones y Issues
Las contribuciones son bienvenidas. Para colaborar:
1. Realiza un fork del proyecto.
2. Crea una nueva rama:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus modificaciones y documenta los cambios en `CHANGELOG.md`.
4. Sube tu rama al repositorio:
   ```bash
   git push origin feature/nueva-funcionalidad
   ```
5. Abre un Pull Request en GitHub.

## ✉️ Contacto y Créditos
- **Desarrollador:** Julián Cancelo
- **Correo Electrónico:** juliancancelo@gmail.com
- **GitHub:** [Julián en GitHub](https://github.com/usuario)
- **LinkedIn:** [Perfil de LinkedIn](https://www.linkedin.com/in/juliancancelo/)
