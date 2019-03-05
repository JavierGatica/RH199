# Usuarios y Grupos <h5>

**ps au =  muestra los procesos que se estn ejecutando con los usuarios**

*/etc/shadow= se almacena la contraseña de los usuarios*

*/etc/group =  se almacena informacion de los grupos*

# Obtención de acceso de superusuario <h5>

**sudo = permite al usuario ejecutar un comando como usuario root o como otro usuario**

*Sudo se puede configurar en la ruta /etc/sudoers*

**Un beneficio adicional de usar sudo es que todos los comandos ejecutados con sudo se registran de manera predeterminada en /var/log/secure**

*Nota: en RHEL7  todos los usuarios son mienbros del grupo wheel los cuales pueden hacer uso de **sudo** el cual ayudara a ejecutar comandos como si fuera root*



# Administración de cuentas de usuarios locales <h5>
  
  *useradd = agregar usuario*
  
  *usermod = modificar usuarios*
  
  *usermod -aG =agregar usuarios aun grupo conservand los que tiene*
  
  *usermod -d = nuevo directorio de inicio*
  
  *usermod -L = bloquear la cuenta de un usuario*
  
  *usermod -U =desbloquear usuario*
  
  *userdel = elimina usuario pero conserva direcotorio*
  
  userdel -r = eimina usuario y directorio*
  
  
  
  
  
  
  
