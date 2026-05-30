# Evaluacion_Despliegue_LMS_CMS_MiledJovel
Informes técnicos de despliegue y configuración de LMS, CMS, Cloud Computing y Arquitectura de Software.
Guía de Trabajo simulando entornos laborales reales: DevOps, Cloud Computing y Arquitectura de Software.
 	Operaciones Básicas y Gestión de Contenidos (Nivel Operativo)
Plataformas a evaluar: MoodleCloud e InfinityFree. 
Ejercicio Práctico 1.1: Despliegue de Entorno LMS (MoodleCloud)
Y	Pasos a seguir: 
1.	Crear una instancia gratuita en MoodleCloud. 
  
 


2.	Configurar los roles (crear un usuario con rol "Profesor" y otro "Estudiante"). 
Rol: Maestro
 
Rol: Alumno
 
 
3.	Diseñar un curso de prueba llamado "Introducción a la Ingeniería de Software", subiendo al menos 2 recursos (un PDF y un enlace externo) y configurando 1 tarea evaluable.

 	Podemos observar a los usuarios creados con sus respectivos roles:
 

 	Creamos el curso solicitado:
 
 

 	Subimos dos recursos:
 
 



 	Creamos la primera asignación: 
 

Ejercicio Práctico 1.2: Despliegue de CMS Tradicional (InfinityFree)
Y	Pasos a seguir:
1.	Registrarse en InfinityFree
 






2.	Crear el subdominio gratuito
 

 
 

3.	Crear la base de datos MySQL 
 
 
4.	Realizar la instalación manual de WordPress (sin instalador automático, descargando el .zip de WordPress).
 

5.	Documentar el proceso de conexión FTP (usar FileZilla) para subir los archivos de WP. 
 
Se realizó la instalación del cliente FTP FileZilla versión 3.70.5, herramienta utilizada para establecer la conexión FTP con el servidor de InfinityFree y subir los archivos de WordPress.
 
 
 
 
Se abrió el cliente FTP FileZilla para realizar la conexión con el servidor de hosting InfinityFree mediante protocolo FTP.
 

Se estableció correctamente la conexión FTP entre FileZilla y el servidor de InfinityFree utilizando el servidor ftpupload.net. Se visualizaron los directorios remotos del hosting, incluyendo la carpeta htdocs donde se alojarán los archivos del sitio WordPress.
 
Se realizó la transferencia del archivo wordpress-7.0.zip desde el equipo local hacia la carpeta htdocs del servidor remoto utilizando FileZilla. La transferencia se completó correctamente mediante protocolo FTP
 

En esta etapa se completó la configuración inicial de WordPress, ingresando los datos necesarios para el funcionamiento del sitio web. Se definió el título del sitio, el nombre de usuario administrador, la contraseña y el correo electrónico de administración. Posteriormente, se ejecutó la instalación del sistema de gestión de contenidos WordPress para preparar el entorno web.
 
En esta captura se visualiza el panel principal de administración de WordPress, también conocido como “Dashboard”. Desde este entorno es posible gestionar el contenido del sitio web, crear páginas, administrar plugins, personalizar la apariencia y configurar todas las funcionalidades necesarias para el desarrollo del proyecto web.
 
6.	Mostrar capturas de la configuración del wp-config.php donde se enlaza la base de datos creada.
La siguiente imagen muestra la configuración del archivo wp-config.php de WordPress, donde se estableció la conexión con la base de datos MySQL creada previamente en InfinityFree. En este archivo se definen parámetros importantes como el nombre de la base de datos, el usuario MySQL, la contraseña y el servidor de la base de datos, permitiendo el correcto funcionamiento del sitio web.
 

