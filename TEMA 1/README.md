# TEMA 1 (Introducion a JavaScript)
**JavaScript** es un lenguaje de programación multiplataforma orientado a objetos que se utiliza para hacer que las páginas web sean interactivas (p. ej., Que tienen animaciones complejas, botones en los que se puede hacer clic, menús emergentes, etc.). También hay versiones de **JavaScript** de lado del servidor más avanzadas, como Node.js, que te permiten agregar más funcionalidad a un sitio web que simplemente descargar archivos (como la colaboración en tiempo real entre varias computadoras). Dentro de un entorno (por ejemplo, un navegador web), **JavaScript** se puede conectar a los objetos de su entorno para proporcionar control programático sobre ellos.

- ## Uso y instalaciones
    Al ser un leguaje que se ejecuta al lado del cliente no debemos de instalar ningun entorno como JDK en Java. En nuestro caso necesitaremos de un IDE como puede ser **Visual Studio Code**, **Sublime Text**, **Atom** o cualquier otro.

    > Tambien para practicar con los ejemplos o aprender, se puede usar la consola que trae incorporado los navegadores ( <kbd>F12</kbd> o <kbd>Click derecho</kbd> + <kbd>inspeccionar</kbd>)
    <br>
    Para practicar podemos utilizar en el navegador una <about:blank>, que es una pagina en blanco.

    Otra opcion de uso es unir el archivo con un archivo HTML, esto es lo que nos vamos a encontrar normalmente. Para ello hay dos forma de unir un codigo **JavaScript**:

    - Incrustacion de codigo Js en HTML:
        
        Creamos un archivo HTML y queremos utilizar JavaScript dentro de el sin tener otros archivos externos, pues podemos incorporarlo en el codigo HTML mediante la etiqueta **\<script>**:
        ~~~HTML
        <html>
            <head>
            </head>
            <body>
                <h1>Ejemplo incrustacion Js en HTML</h1>
                <script>
                    //...Codigo js
                </script>
            </body>
        </html>
        ~~~
    - Incorporacion de archivo externo a HTML:

        En este caso tendremos dos archivos por separados, uno que será nuestro **HTML** y otro nuestro codigo JavaScript, para unirlos deberemos indicar en el codigo del **HTML** el archivo que queremos unir con la etiqueta **\<script src="codigo.js">\</script>**.

        >Aqui deberemos de entender que son las rutas  absolutas y relativas para buscar y colocar el archivo correctamente.
        ><br>
        ><br>

        >>- **Ruta absoluta:**
        >    <br>
        >   Imaginemos que nuestro archivo se encuentra en el **Escritorio** y se llama **"codigo.js"**.
        >    <br>

        >    Entonces para saber su ruta absoluta tendrá que ser la ruta completa desde el disco que tengamos, es decir : **_"C:\Users\jesus\Desktop\codigo.js"_**
        >    <br>
        >    <br>
        
        >>  - **Ruta relativa:**<br>
        >    La ruta relativa es desde nos encontramos buscar el archivo, es decir, imaginemos que tenemos esta estructura:<br>
        >>    ~~~
        >>        app
        >>        ├── img
        >>        ├── index.html
        >>        └── js
        >>            └── codigo.js
        >>    ~~~
        >> Pues para introducir la ruta relativa desde el archivo "**index.html**" al archivo "**codigo.js**", sería **_"js/codigo.js"_**

        Un ejemplo sería:

        ~~~HTML
        <html>
            <head>
            </head>
            <body>
                <h1>Ejemplo incrustacion Js en HTML</h1>
                <script src="js/codigo.js"></script>
            </body>
        </html>
        ~~~

        > Tambien hay que saber que según donde lo pongamos el codigo se ejecutará antes o después.
    <br>

    ## Links de IDEs recomendados:

    - [Visual Studio Code](https://code.visualstudio.com/)
    - [Sublime](https://www.sublimetext.com/)
    - [Atom](https://atom.io/)
        

    
