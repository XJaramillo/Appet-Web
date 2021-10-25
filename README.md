# Proyecto Titulación APPET :dog:
## Plataforma Web :computer:

## Integrantes : 
* **Xavier Jaramillo** 
* **Gabriel Ibujés** 

## Descripcion del proyecto:
Servicios para todo tipo de macotas

Appet tiene la finalidad de juntar multiples servicios para todo tipo de mascotas, así facilitando al usuario en encontrar el servicio especifico y evitar el uso de otras plataformas externas
Servicios que se pueden encontrar: 
* **Vetrinaria.**
* **Peluquería**
* **Hospedaje (Air bnb)**
* **Tienda (Pet Shop)**

## Aplicación Web administrativa de la plataforma APPET.

Esta plataforma web permitira, iniciar sesión únicamente a administradores, la basede datos utilizada es Firebase de Google de una manera cifrada, los registros se iran guardando constantemente, contiene funcionalidad CRUDE.

:mailbox: :email:


## Navegadores:

* **Google Chrome**
* **Microsoft Edge**
* **Mozilla Firefox**
* **Opera**
* **Safari**


## Despliegue Web Firebase:

Se ralizo con ayuda de Firebase Hosting de la siguiente manera:

Creamos un proyecto en Firebase De Google:

![image](https://user-images.githubusercontent.com/38759787/138756805-b377fefc-6a00-47d3-ba82-98b720717813.png)

PREPARAMOS ENTORNO

Para poder subir una página web al hosting de la nube de Firebase, primero tenemos que instalar las herramientas de Firebase (firebase tools), debemos tener instalado NodeJS y NPM, ya con estas dependencias, ejecutamos el siguiente comando dentro de el CMD o la Terminal, dependiendo el sistema operativo si es Windows, MacOS o Linux:
En este caso es en Windows

![image](https://user-images.githubusercontent.com/38759787/138757167-c0aa6974-1cc3-477a-982d-33b0d1d0ac03.png)

LOGIN EN FIREBASE TOOLS

Enlazamos Firebase con las firebase-tools que previamente instalamos.Ejecutamos el siguiente comando en la terminal:

![image](https://user-images.githubusercontent.com/38759787/138757495-37de7654-618d-4fb6-9e4e-26bc3ce5767c.png)

![image](https://user-images.githubusercontent.com/38759787/138757690-2ec37048-db4e-4d6b-8018-3f1b2094f311.png)

Para subir el proyecto al hosting cloud de Firebase, debemos posicionar la terminal en la carpeta que contiene el proyecto. Como esta eaplicacion está orientado a una aplicación de angular, el primer paso para la subida será genera el build de Angular.

![image](https://user-images.githubusercontent.com/38759787/138760606-18986e08-777b-4d21-b922-239242159b05.png)

El resultado de este comando debe verse como a continuación te muestro:

![image](https://user-images.githubusercontent.com/38759787/138760655-1167b5a7-76f8-4d5f-87df-c18d5f7a5ea9.png)

Se nos genera una carpeta llamda Dist en el proyecto de Angular:ç

![image](https://user-images.githubusercontent.com/38759787/138760769-96d7ba52-e9d2-4259-b9e2-798d0052d502.png)

SUBIR EL BUILD A FIREBASE

Para comenzar con la subida ejecuta el comando init de Firebase Tools para que la herramienta configure el proyecto como un proyecto de Angular, y además, enlaza el proyecto que previamente creamos en la consola de Firebase con la carpeta actual:

![image](https://user-images.githubusercontent.com/38759787/138761566-242d3a3a-adc5-496b-adc0-48f25797ac5d.png)

Este comando iniciará un asistente que te guiará por la configuración del proyecto, las opciones que debes seleccionar son:

Usando las flechas arriba/abajo selecciona qué característica de Firebase, Enter:

![image](https://user-images.githubusercontent.com/38759787/138761620-ae033d9d-85cd-43d6-87b8-b7b8848b3265.png)

El siguiente punto es muy importante cuando trabajamos con un proyecto de Angular, en este paso el asistente de Firebase nos pregunta qué directorio contiene nuestra aplicación, es muy importante que indiquemos que es el directorio dist/nombre-proyecto sustituye la parte de nombre-proyecto por la carpeta que veas dentro de dist

![image](https://user-images.githubusercontent.com/38759787/138761755-e3cc46c2-a330-4bed-97e1-7332acf4bbd5.png)

El siguiente paso, está relacionado con las Single Page Applications, como Angular suele contener su propio router (si no lo contiene, no importa no es necesario), escribiremos y y luego presionaremos Enter. 

Luego de eso, Firebase notará que ya existe un archivo index.html y nos preguntara si queremos que lo sobre escriba, o no, escribe n/y luego Enter para indicarle que no debe sobre escribirlo y se conserve el archivo index.html del proyecto Angular.
Esto debe completar el asistente de Firebase y habremos configurado con éxito nuestro directorio como una app de Angular que podemos subir al Firebase Hosting. Para terminar, vamos a ejecutar el siguiente comando que se encargará de subir nuestros archivos a Firebase para que podamos visualizar nuestra página:

![image](https://user-images.githubusercontent.com/38759787/138761825-5152e94d-9f12-479c-9b99-3d7b7a05cce3.png)

![image](https://user-images.githubusercontent.com/38759787/138762078-ca7c7264-8c76-4403-8548-e3b602a46a8e.png)

Para futuros cambios:

![image](https://user-images.githubusercontent.com/38759787/138762126-20d6bf09-938b-4e30-8050-364ae1086723.png)

## Despliegue Appet Web

Clic en el siguiente `enlace` [Appet Web](https://appet-web-d61fd.web.app/). :white_check_mark:


## Observaciones para usar la plataforma Móvil:

** *Se Necesita versión de Android 7 o más*

## Descarga El APK

Descarga el `APK` clic en el siguiente enlace [Appet](). :white_check_mark:

## Manual de Usuario

Mira el `Manual` clic en el siguiente enlace [Manual de Usuario](https://www.youtube.com/watch?v=Qz0A03kBsSc). :white_check_mark:



