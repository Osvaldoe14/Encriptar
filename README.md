<html>
    <head>
        <link rel="stylesheet" href="Estilos.css">

    </head>
    <body>
        <header>
            <img src="img/Vector.jpg" alt="logo alura" class="vector">

        </header>

        <main>
            <section class="seccion1">
                <textarea class="area" placeholder="Ingrese el texto aqui"></textarea>

                <div class="contenedor-botones">
                <input type="button" class="btn-encriptar" value="Encriptar">
                <input type="button" class="btn-desencriptar" value="Desencriptar">
                </div>
            </section>
            <section class="seccion2">
               <div class="contenedor-muneco">
                <img src="img/muneco.png" alt="muneco" class="muneco">
               </div>
               <div class="contenedor-h3">
                <h3>Ningun mensaje fue encontrado</h3>
               </div>
               <div class="contenedor-parrafo">
                <p>Ingresa el texto que deseas encriptar o desencriptar</p>
               </div>

               <div class="contenedor-resultado">
                 <h3>Mensaje encriptado:</h3>
                 <P class="texto-resultado"></P>

               </div>
               <div class="contenedor-copiar">
                <input type="button" class="btn-copiar" value="Copiar">
               </div>
            </section>
        </main>
        <footer>
            <p>Tarea realizada por Osvaldo Estrada. Derechos de Alura</p>
        </footer>
        <script src="encriptado.js"></script>
    </body>
</html>
