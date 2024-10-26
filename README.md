<a name="readme-top"></a>

# AdminProve

AdminProve es un sistema de administración de proveedores. Este proyecto utiliza XAMPP para un entorno de servidor local y emplea sesiones para manejar el acceso de usuarios con diferentes permisos.

## Características

- **Módulo de Autenticación**: Login y manejo de sesiones para controlar el acceso.
- **Escritorio Principal**: Pantalla principal donde se visualizan los datos de ingresos.
- **Control de Acceso**: Permisos específicos para los usuarios que pueden acceder al escritorio.

## Requisitos

- **Servidor Local**: XAMPP o cualquier servidor local con soporte para PHP y MySQL.
- **PHP**: Versión 7.4 o superior.
- **Base de Datos**: MySQL.
- **Navegador Web**: Cualquier navegador moderno.

## Instalación

1. Clona el repositorio en tu directorio de XAMPP:
   ```bash
   git clone https://github.com/tu-usuario/sistema.git


## Estructura del Proyecto

```plaintext
Sistema de Registros/
├── ajax/            # Scripts de procesamiento de peticiones AJAX para actualización sin recarga de página.
├── config/          # Archivos de configuración, como la conexión a la base de datos y configuraciones generales.
├── db/              # Scripts relacionados con la base de datos, como archivos SQL para creación de tablas.
├── files/           # Carpeta para almacenar archivos subidos por usuarios o documentos generados.
├── fpdf181/         # Librería FPDF para la generación de archivos PDF (reportes y documentos).
├── modelos/         # Clases y funciones que manejan la lógica de negocio del sistema (CRUD).
├── public/          # Archivos públicos accesibles desde el frontend, como CSS, JS e imágenes.
├── vistas/          # Vistas o interfaces del usuario (archivos PHP).
└── index.php        # Archivo de inicio y punto de entrada principal de la aplicación.
