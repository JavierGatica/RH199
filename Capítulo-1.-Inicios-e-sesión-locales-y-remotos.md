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
  
  ** ssh-agent = buscar mas informacion sobre este comando en el man**
  
  
  
  
