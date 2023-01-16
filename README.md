# Introducción

Node.js es un entorno de ejecución de JavaScript para servidores. Permite a los desarrolladores escribir código JavaScript en el lado del servidor para crear aplicaciones web y servicios. Utiliza el motor JavaScript V8 de Google para ejecutar el código, y proporciona una serie de módulos de Node.JS que facilitan el desarrollo de aplicaciones web escalables y de alto rendimiento.

# Material Necesario

- [VirtualBox](https://github.com/RaulToribio/01-Instalar-VirtualBox)
- [Ubuntu 22.04.1 LTS](https://github.com/RaulToribio/02-Descargar-Ubuntu)
- [Crear Máquina Virtual](https://github.com/RaulToribio/03-Crear-Maquina-Virtual)
- [Configurar Máquina Virtual](https://github.com/RaulToribio/04-Configurar-Maquina-Virtual)
- [Instalar Ubuntu](https://github.com/RaulToribio/05-Instalar-Ubuntu)
- [Instalar Guest Additions](https://github.com/RaulToribio/06-Instalar-Guest-Additions)
- [Comandos Linux](https://github.com/RaulToribio/07-Comandos-Linux)

# Material de Referencia

- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(1).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(1).png)

Dirigirse a la página web de [NodeJS](https://nodejs.org/en/).
Clic en “[Other Downloads](https://nodejs.org/en/download/)”.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(2).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(2).png)

Clic en “[Installing Node.JS via package manager](https://nodejs.org/en/download/package-manager/)”.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(3).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(3).png)

Clic en “[Debian and Ubuntu Based Linux Distributions](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions)”.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(4).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(4).png)

Clic en “[Node.js Binary Distributions](https://github.com/nodesource/distributions/blob/master/README.md)”

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(5).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(5).png)

Dirigirse a la versión LTS (Long-Term Support).

Actualmente la versión LTS es *Node.js LTS (v18.x)*.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(6).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(6).png)

Para poder descargar los archivos del servidor web de NodeJS es necesario instalar *cURL*.

Usar la línea de comando `sudo apt-get install curl` para instalar cURL.

Es una herramienta ampliamente utilizada para automatizar tareas de red, como descargar archivos de un servidor web, enviar solicitudes POST y GET, y recopilar datos de una URL específica.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(7).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(7).png)

Ingresar contraseña.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(8).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(8).png)

Se habrá instalado cURL.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(9).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(9).png)

Utilizar la línea de comando `curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash - &&\` para descargar los archivos del servidor web de NodeJS.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(10).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(10).png)

Utilizar la línia de comando `sudo apt-get install -y nodejs` para instalar NodeJS.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(11).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(11).png)

Comenzará la instalación.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(12).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(12).png)

Se habrá instalado NodeJS.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(13).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(13).png)

Utilizar la línea de comando `node —version` para comprobar la versión instalada de NodeJS.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(14).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(14).png)

La versión de NodeJS es *v18.12.1*.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(15).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(15).png)

Utilizar la línea de comando `sudo apt-get install build-essentials`.

Es un paquete de Ubuntu que contiene las herramientas y librerías necesarias para compilar y construir software desde el código fuente. Incluye herramientas como GCC (GNU Compiler Collection), Make, y g++, así como librerías como libc-dev y libstdc++-dev.

Al instalar build-essential, se asegura que tienes las herramientas y librerías necesarias para compilar y construir software desde el código fuente. Esto es especialmente útil si quieres instalar programas o paquetes que no están disponibles en los repositorios oficiales de Ubuntu, o si quieres modificar el código fuente de un programa existente.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(16).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(16).png)

Se habrá instalado build-essentials.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(17).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(17).png)

Utilizar la línea de comando `sudo npm install -g —unsafe-perm node-red` para que npm instale NodeRed con permisos de administrador.

Cuando se utiliza la opción "--unsafe-perm" npm instala los paquetes con permisos de administrador incluso si el usuario actual no es administrador.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(18).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(18).png)

Comenzará la instalación de NodeRed.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(19).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(19).png)

Se habrá instalado NodeRed.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(20).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(20).png)

Iniciar NodeRed escribiendo `node-red` en la terminal.

Se mostrará el mensaje “Server now running at http://127.0.0.1:1880/” una vez que NodeRed se haya iniciado.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(21).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(21).png)

Ingresar a NodeRed desde un navegador con `localhost:1880`.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(22).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(22).png)

Habrá que instalar nodos adicionales que se utilizarán más adelante.

Para instalarlos desde la terminar utilizar `npm install node-red-dashboard` para instalar los nodos *Dashboard* y `npm install node-red-node-mysql` para instalar los nodos *MySQL*.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(23).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(23).png)

Es posible instalar estos nodos desde la interfaz de NodeRed en nuestro navegador.

Ir al menú y clic en “Manage palette”.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(24).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(24).png)

En la pestalla “Install” buscar “Node-Red-Dashboard”.

Clic en “Install”.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(25).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(25).png)

Clic en “Install”.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(26).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(26).png)

Comenzará la instalación de los nodos *Dashboard*.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(27).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(27).png)

NodeRed notificará que nodos han sido agregados.

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(28).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(28).png)

NodeRed está listo para ser utilizado.

# Evidencias

![https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(28).png](https://raw.githubusercontent.com/RaulToribio/13-Instalar-NodeJS/main/Im%C3%A1genes/Instalar%20NodeJS%20(28).png)

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>
