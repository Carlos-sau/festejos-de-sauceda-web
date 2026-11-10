# Migración de WordPress a InfinityFree

## 1. Situación inicial
La página web estaba desarrollada en un entorno local utilizando XAMPP, WordPress y Elementor.

## 2. Exportación de la base de datos
Se exportó la base de datos MySQL desde phpMyAdmin para trasladar el contenido y la configuración de WordPress.

## 3. Preparación del hosting
Se creó una base de datos MySQL en InfinityFree y se importó el archivo SQL.

## 4. Transferencia de archivos mediante FileZilla
Se estableció una conexión FTP con el servidor remoto y se transfirieron los archivos de WordPress desde el entorno local al directorio correspondiente del hosting.

## 5. Configuración de WordPress
Se configuró el archivo `wp-config.php` con los datos de conexión de la nueva base de datos.

También se adaptaron las direcciones del sitio para utilizar el nuevo dominio.

## 6. Comprobaciones finales
Se verificó el acceso al administrador de WordPress, el funcionamiento de la página y la conexión HTTPS.

## Resultado
La página web quedó publicada y accesible desde Internet.

**Herramientas utilizadas:** XAMPP, WordPress, Elementor, phpMyAdmin, MySQL, FileZilla e InfinityFree.