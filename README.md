<a name="readme-top"></a>

>AdminProve es un sistema de administración de proveedores. Este proyecto utiliza XAMPP para un entorno de servidor local y emplea sesiones para manejar el acceso de usuarios con diferentes permisos.

##Características
>Módulo de Autenticación: Login y manejo de sesiones para controlar el acceso.
>Escritorio Principal: Pantalla principal donde se visualizan los datos de ingrsos.
>Control de Acceso: Permisos específicos para los usuarios que pueden acceder al escritorio.

##Requisitos
>Servidor Local: XAMPP o cualquier servidor local con soporte para PHP y MySQL.
>PHP: Versión 7.4 o superior.
>Base de Datos: MySQL.
>Navegador Web: Cualquier navegador moderno.

##Instalación
>Clona el repositorio en tu directorio de XAMPP: 
>bash Copiar código
>git clone [https://github.com/tu-usuario/sistema.git]

##Configura la Base de Datos:
>Crea una base de datos en MySQL llamada adminprove.
>Importa el archivo adminprove.sql desde la carpeta database a tu base de datos.

##Configuración de Conexión:
>En el archivo conexion.php en la carpeta config, configura las credenciales de tu base de datos:
>php
>Copiar código
>$host = "localhost";
>$user = "root"; // Usuario de MySQL
>$pass = "";     // Contraseña de MySQL
>$dbname = "adminprove";

##Iniciar el Proyecto:
>Inicia Apache y MySQL desde XAMPP.
>Accede a http://localhost/AdminProve en tu navegador para ver la aplicación en funcionamiento.

##Uso
>Inicio de Sesión: Accede con tus credenciales para ingresar al sistema.
>Visualización de Totales: Desde el escritorio, escritorio, colaboradores y registros.
>Manejo de Errores: Si ocurre algún error en las consultas, se mostrará un mensaje en pantalla para una fácil identificación.

##Estructura del Proyecto
>Este proyecto está organizado en las siguientes carpetas y archivos principales:

>ajax/: Contiene scripts de procesamiento de peticiones AJAX, que permiten actualizar datos sin recargar la página.
>config/: Carpeta que guarda archivos de configuración, como la conexión a la base de datos y la configuración general del sistema.
>db/: Archivos relacionados con la base de datos, como scripts SQL para crear tablas o realizar migraciones.
>files/: Carpeta donde se almacenan archivos subidos por los usuarios o documentos generados por el sistema.
>modelos/: Contiene las clases y funciones que manejan la lógica de negocio del sistema, incluyendo las operaciones CRUD para diferentes entidades.
>public/: Archivos públicos como imágenes, hojas de estilo (CSS), y scripts de JavaScript que son accesibles desde el frontend.
>vistas/: Contiene las vistas o interfaces del usuario. Aquí se encuentran los archivos PHP que muestran la interfaz gráfica del sistema.
>index.php: Archivo de inicio del sistema. Es el punto de entrada principal, desde donde se carga la aplicación y se redirige a las diferentes secciones.
