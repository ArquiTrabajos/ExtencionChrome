<p align="center">
  <a href="https://chrome.google.com/webstore/detail/vibrant-color-dropper-pic/fcekakhpgmlaihglgajajbceajnhlgfn?hl=en&authuser=0">
    <img src="https://i.postimg.cc/NMgskpQg/DALL-E-2023-03-07-23-17-04-creame-un-logo-para-una-extension-en-chrme-que-con-un-boton-escoje-colo.png" height="100">
    <h3 align="center">Color Hex Finder</h3>
  </a>
</p>

#  Escoge tu color
  

Descripción

¿Alguna vez has visto un color en una página web que te encanta y te gustaría usarlo en tu propio sitio web? Color Hex Finder es una extensión de navegador para Google Chrome que te permite encontrar los colores de una página en formato hexadecimal de manera fácil y rápida.

Características principales

Encuentra los colores en hezxadecimal: La extensión escanea la página web solo chrome y encuentra todos los colores que están en formato hexadecimal.
Selección fácil de colores: Puedes hacer clic en un color para copiarlo en el panel que aparece sobre el icono de la extencion y  usarlo en tu propio sitio web o proyecto.
NOTA: no funciona en cualquier pagina de chrome por sus permisos con las extenciones no puede ser utiliza. 
----
## Arquitectura Chrome
![image](https://cdn.tutsplus.com/cdn-cgi/image/width=600/net/uploads/2013/07/architecture.png)

* **UI** - Interfaces with [Chrome](https://developer.chrome.com/docs/extensions/mv2/architecture-overview/) and [Chrome Debugging Protocol](https://developer.chrome.com/devtools/docs/debugger-protocol)  ([API viewer](https://chromedevtools.github.io/debugger-protocol-viewer/))La interfaz de usuario de una extensión debe tener un propósito y ser mínima. La interfaz de usuario debe personalizar o mejorar la experiencia de navegación sin distraerla. La mayoría de las extensiones tienen una acción de navegador o una acción de página, pero pueden contener otras formas de interfaz de usuario, como menús contextuales, el uso del omnibox o la creación de un atajo de teclado.
Las páginas de IU de extensión, como una ventana emergente, pueden contener páginas HTML normales con lógica de JavaScript. Las extensiones también pueden llamar a tabs.create o window.open() para mostrar archivos HTML adicionales presentes en la extensión.
Una extensión que usa una acción de página y una ventana emergente puede usar la API de contenido declarativo para establecer reglas en la secuencia de comandos en segundo plano para cuando la ventana emergente esté disponible para los usuarios. Cuando se cumplen las condiciones, la secuencia de comandos de fondo se comunica con la ventana emergente para que los usuarios puedan hacer clic en su icono.

* **imagen arquitectura** -  
Script emergente: archivo JavaScript local para la extensión DOM
Script de fondo: proporciona persistencia y maneja eventos de fondo
Script de contenido: scripts que se ejecutan de forma aislada en el contexto de la página web
Script inyectado: scripts que se inyectan mediante programación en la página web

[![imagen-2023-03-07-233010173.png](https://i.postimg.cc/ry5PGMKN/imagen-2023-03-07-233010173.png)](https://postimg.cc/RqVd4r1W)
----

 Captura de pantalla de la interfaz de usuario de la extensión, mostrando los colores encontrados en una página web.
 
[![imagen-2023-03-07-233206712.png](https://i.postimg.cc/KvqrBHr5/imagen-2023-03-07-233206712.png)](https://postimg.cc/VdtCc4hS)
 Captura de pantalla de la página de opciones de la extensión, mostrando cómo se pueden personalizar las opciones de búsqueda.
Instalación

[Doc] (https://docs.google.com/document/d/1dRGkLMey_CFyq7yB0Td0L9itEfCBcWzFFzROKf5UZpk/edit?usp=sharing)

Uso
Chrome https://developer.chrome.com/docs/extensions/mv3/getstarted/

----

### :wrench: Tools Used
- Javascript / CSS / HTML / Chrome web APIs / Local storage

-----

### ⚙️ Version v1.0 released
- En la sección de juegos, se agrega una nueva función de nombre de color.
- Se eliminó el efecto de animación no deseado y se actualizó la interfaz de usuario.


-----

### Features:<br>
- Esta extensión extrae colores de la pantalla actual.
- Esta extensión tiene dos características principales i) Cuentagotas y ii) Selector de color.
- Cuentagotas para seleccionar cualquier color de la ventana actual y Selector de color para hacer posibles combinaciones de RGB y formar un color requerido.
- Los usuarios pueden guardar hasta 50 colores recientes y copiar el código hexadecimal de color haciendo clic en él.
- Cuentagotas de esta extensión es lo suficientemente potente como para extraer el color de todos los sitios. También funciona en las páginas de nuevas pestañas, las páginas de configuración de Chrome y la tienda web de Chrome.
- Haga clic en los cuadros de color en una sección de colores recientes para copiar el valor hexadecimal en el portapapeles.
- Esta extensión también proporciona herramientas adicionales como un clasificador de color, un nombre de color, un mezclador de color y un convertidor de código de color.
- Una interfaz simple y fácil de usar, simplemente haga clic en el cuadro de color o en el código hexadecimal en el que se puede hacer clic para copiar el valor hexadecimal.
### Referencias
  https://www.freecodecamp.org/news/chrome-extension-message-passing-essentials/

### Support 
Esta extensión solo ha sido compatible con navegadores web basados ​​en Chrome/Edge.



### :v: Contributing

#### Step 1: Clone The Repo

Fork the repository and then clone the repo locally by -
```bash
git clone https://github.com/ArquiTrabajos/ExtencioChrome.git
```
#### Step 2: Install Dependencies
Visite brave://extensions, en modo de desarrollo, pruebe sus actualizaciones.<br>

¡Genial! Después de clonar y configurar el proyecto local y hacer actualizaciones, puede enviar los cambios a su bifurcación de GitHub y hacer una solicitud de extracción.
-----

Licencia
Incluye información sobre la licencia de la extensión, por ejemplo, si se trata de software libre o de código cerrado.

-----

<p align="center">
Give the extension a :star: if you liked it.<br>
Made with :heart: and javascript.
</p>



