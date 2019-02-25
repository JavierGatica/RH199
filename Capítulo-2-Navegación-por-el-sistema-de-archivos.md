# Jerarquía del sistema de archivos Linux <h5>

*Los subdirectorios de / se usan con fines estandarizados para organizar archivos por tipo y objetivo. Esto facilita la posibilidad de encontrar archivos. Por ejemplo, en el directorio root, el subdirectorio /boot se usa para guardar archivos que se necesitan para arrancar el sistema.*

* /usr = Software instalado, librerías compartidas, incluye archivos y datos de programa estáticos de solo lectura.
  * /usr/bin: Comandos del usuario.
  * /usr/sbin: Comandos de administración del sistema.
  * /usr/local: Software personalizado en forma local.

* /etc	= Archivos de configuración específicos para este sistema.
* /var = Datos variables específicos de este sistema que deberían conservarse entre los arranques. 
* /run = Datos de tiempo de ejecución para procesos que se iniciaron desde el último arranque. 
* /home = Los directorios de inicio son aquellos donde los usuarios habituales guardan sus datos personales y los archivos de configuración.
* /root = Es el directorio de inicio para el superusuario administrativo, root.
* /tmp = Es un espacio con capacidad de escritura para archivos temporales. Los archivos a los que no se haya accedido, y que no se hayan cambiado ni modificado durante 10 días se eliminan de este directorio automáticamente
* /boot = 	Son los archivos necesarios para iniciar el proceso de arranque.
* /dev = Contiene archivos de dispositivo especiales que son usados por el sistema para acceder al hardware.


# Los directorios de inicio son aquellos donde los usuarios habituales guardan sus datos personales y los archivos de configuración. <h5>
 
 **La opción -p parent crea directorios de inicio faltantes para el destino solicitado.**
 
 **cp =  copia uno o más archivos para que se conviertan en archivos nuevos e independientes**
 **mv = cambia el nombre a los archivos en el mismo directorio o reubica archivos en un directorio nuevo. **
 **rm = elimina archivos, pero no directorios**
 **-f que fuerza la eliminación sin solicitar confirmación al usuario.**
 **rmdir = elimina directorios solo si están vacíos. Los directorios eliminados no pueden recuperarse.**
 
 
# Creación de enlaces entre archivos <h5>
 
 **ln =  crea enlaces duros nuevos a archivos existentes**
 **ln -s = permite crear un enlace blando, que también se conoce como "enlace simbólico". **
 
 
