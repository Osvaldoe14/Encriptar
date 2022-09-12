<html>
    <html lang="es">
    <head>
        <meta charset="UTF8">
        <meta name="viewport" content="width=device-width, initial scale=1.0">
        <link rel="stylesheet" href="Estilos.css">

    </head>
    <body>
        <header>
           
            <h1 class="titulo">Juego de encriptar y desencriptar texto</h1>
            <img src="img/letra.jpg" alt="logo alura" class="letra">
        </header>

        <main>
            <section class="seccion1">
                <textarea class="area" placeholder="Ingrese el texto que deseas encriptar"></textarea>

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
        
               <div class="contenedor-resultado">
                 <h3>Mensaje encriptado:</h3>
                 <P class="texto-resultado"></P>
            </section>

        </main>
        <footer>
            <p>Tarea realizada por Osvaldo Estrada 2022. Derechos de Alura</p>
        </footer>
        <script src="encriptado.js"></script>
    </body>
</html>
