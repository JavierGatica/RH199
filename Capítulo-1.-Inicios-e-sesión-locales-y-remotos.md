# Acceso a la línea de comandos a través de la consola local <h1>


*Una línea de comandos es una interfaz basada en texto que puede utilizarse para introducir instrucciones en un sistema informático.* 

# Consolas virtuales <h5>
*Cuando se esté ejecutando un entorno gráfico, presione Ctrl+Alt y presione una tecla de función (de F2 a F6) para acceder a un prompt de inicio de sesión de texto en una consola virtual. Presione Ctrl+Alt+F1 para regresar a la primera consola virtual y al escritorio gráfico.*

# Conceptos básicos de la shell <h6>

*Los comandos ingresados en el prompt de shell están compuestos por tres partes básicas:*

* Comando para ejecutar

* Opciones para ajustar el comportamiento del comando

* Argumentos, que generalmente son destinos del comando

 Las opciones generalmente comienzan con uno o dos guiones (-a o --all, por ejemplo) para que se distingan de los argumentos.
 
 *Por ejemplo, la línea de comandos usermod -L morgan tiene un comando (usermod), una opción (-L) y un argumento (morgan). El efecto de este comando es bloquear la contraseña de la cuenta del usuario morgan.*
 
 * Los corchetes, [], comprenden elementos opcionales.
 * Todo lo que vaya seguido de ... representa una lista con longitud arbitraria de elementos de ese tipo.
 * Cuando hay múltiples elementos separados por tuberías, |, solo uno de ellos puede especificarse.
 * El texto incluido entre corchetes angulares, <>, representa datos variables. Por ejemplo, <filename> significa “inserte aquí el nombre de archivo que desee usar”. En ocasiones, estas variables simplemente se escriben con mayúsculas (por ejemplo, FILENAME).
  
  **El comando exit finaliza la sesión de la shell actual. Otra forma de finalizar una sesión es presionando Ctrl+d.**
  
  # Configuración de autenticación basada en claves SSH <h5>
  *La generación de claves se realiza con el comando ssh-keygen.* 
  * clave privada ~/.ssh/id_rsa
  * clave pública ~/.ssh/id_rsa.pub.
  
  **ssh-agent = buscar mas informacion sobre este comando en el man**
  **Para poder usar la autenticación mediante claves, la clave pública debe copiarse en el sistema de destino. Esto puede realizarse con ssh-copy-id.**
  
  **Ejemplo**
  *[student@desktopX ~]$ ssh-copy-id root@desktopY*
  
  # Obtención de ayuda de Red Hat <h5>
 
  *El comando redhat-support-tool puede utilizarse como una shell interactiva o invocarse como si fuera un comando que se ejecuta en forma individual con opciones y argumentos.*
  *La herramienta redhat-support-tool permite que los suscriptores busquen y muestren el mismo contenido de la base de conocimientos que se ve cuando están en el portal de clientes de Red Hat.*
  
  *kb = buscar informacion con el ID  del producto *
  
  *existen 4 niveles de gravedad para los problemas que se presenten*
  
  * Urgente (gravedad 1) = Perdida de los datos de producción o en las que los sistemas de produccion no están duncionando
  * Alta (Gravedad 2) = Un problema donde el software funciona, pero su uso en un entorno de producción se ve gravemente reducido.  
  * Media (gravedad 3) = Un problema que implica una pérdida parcial no fundamental de la capacidad de uso del software en un entorno de producción o desarrollo.  
  * Baja (Gravedad) =  Un asunto de uso general, la comunicación de un error de documentación o una recomendación para una mejora o modificación futura del producto. 
  
  
  
  
