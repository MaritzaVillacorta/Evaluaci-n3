<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>VENTA DE ROPA</title>
    <!-- Enlace al archivo CSS de Bootstrap (opcional) -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">
    <!-- Scripts de Bootstrap y jQuery -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <!-- Enlace a tu archivo de script personalizado -->
    <script src="script.js"></script>
    <!-- Estilos personalizados -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #b92d71;
            color: white;
            text-align: left;
            padding: 1em;
            display: flex;
            align-items: center;
        }
        header img {
            max-width: 150px;
            margin-right: 10px;
        }
        .container {
            margin: 20px;
        }
        .producto {
            border: 1px solid #070707;
            padding: 15px;
            margin: 10px;
            text-align: center;
        }
        .carrito {
            list-style-type: none;
            padding: 0;
        }
        .oculto {
            display: none;
        }
    </style>
</head>
<body>

<header>
     <!-- Logo -->
    <img src="Logo.png" alt="Logo de Preloved Closet">
    <h1>PRELOVED CLOSET</h1>
</header>

<div class="container">
    <h2>ROPA DE MUJER</h2>
    <button type="button" id="mostrarMujer">Mostrar Productos</button>
    <div class="row productosMujer oculto">
        <div class="col-md-6">
            <div class="producto">
                <h2 class="nombreProducto">Blusa Corta</h2>
                <img src="blusa.png" alt="Ropa de Mujeres" class="img-fluid">
                <p class="descripcionProducto">Alarga el ciclo de vida de tus prendas favoritas</p>
                <button class="btn btn-primary verProducto">AGREGAR AL CARRITO</button>
            </div>
        </div>
        <div class="col-md-6">
            <div class="producto">
                <h2 class="nombreProducto">Blusa Negra</h2>
                <img src="blusa2.png" alt="Ropa para Hombres" class="img-fluid">
                <p class="descripcionProducto">¡Cientos de prendas a precios imbatibles!</p>
                <button class="btn btn-primary verProducto">AGREGAR AL CARRITO</button>
            </div>
        </div>
        <div class="col-md-6">
            <div class="producto">
                <h2 class="nombreProducto">Blusa a Cuadros</h2>
                <img src="blusa 3.png" alt="Ropa de Mujeres" class="img-fluid">
                <p class="descripcionProducto">Alarga el ciclo de vida de tus prendas favoritas</p>
                <button class="btn btn-primary verProducto">AGREGAR AL CARRITO</button>
            </div>
        </div>
        <div class="col-md-6">
            <div class="producto">
                <h2 class="nombreProducto">Chompa Rosada</h2>
                <img src="chompa.png" alt="Ropa de Mujeres" class="img-fluid">
                <p class="descripcionProducto">Alarga el ciclo de vida de tus prendas favoritas</p>
                <button class="btn btn-primary verProducto">AGREGAR AL CARRITO</button>
            </div>
        </div>
    </div>
    <h2>ROPA DE HOMBRE</h2>
    <button type="button" id="mostrarHombre">Mostrar Productos</button>
    <div class="row productosHombre oculto">
        <div class="col-md-6">
            <div class="producto">
                <h2 class="nombreProducto">Chaleco</h2>
                <img src="chaleco.png" alt="Ropa de Mujeres" class="img-fluid">
                <p class="descripcionProducto">Alarga el ciclo de vida de tus prendas favoritas</p>
                <button class="btn btn-primary verProducto">AGREGAR AL CARRITO</button>
            </div>
        </div>
        <div class="col-md-6">
            <div class="producto">
                <h2 class="nombreProducto">Polera</h2>
                <img src="polera.png" alt="Ropa de Mujeres" class="img-fluid">
                <p class="descripcionProducto">Alarga el ciclo de vida de tus prendas favoritas</p>
                <button class="btn btn-primary verProducto">AGREGAR AL CARRITO</button>
            </div>
        </div>
    </div>
</div>

<div class="container">
    <h2>Carrito de Compras</h2>
    <ul id="carrito" class="carrito"></ul>
    <p>Total: S/. <span id="total">0.00</span></p>
</div>
</body>
</html>
        
