# Ejercicio Angular
1. Para comenzar nuestro ejercicio, debemos tener instalado node.js, si no hemos intalado angular cli lo debemos hacer o de lo contrario comenzamos con el siguiente comando ng new PROJECT-NAME, para que instale todo lo que necesitamos.
2. Una vez que esté creado nuestro proyecto, nos posicionamos dentro de este, y hacemos correr ng server.
3. Si nos podemos a revisar las carpetas creadas podemos analizar lo siguiente, angular es como una caja que guarda todo:
..* package.json: este archivo es donde estan nuestras herramientas que necesitaremos y no lo tocaremos.
..* Nuestro componente incial esta dentro de la carpeta src en app, app.component.ts 
~~Toda nuestra aplicacion que haremos en varios componentes esta contenido en nuestro archivo index.html en <app-root></app-root>~~
..* ngFor, lo que hace es hacer es empezar a iterrar con un ciclo for nuestro arreglo de hobbies que tenemos declarado, esto lo declaro en mi etiqueta li, para que no se repita ul y li cada vez que se haga la iterración.
