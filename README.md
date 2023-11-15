<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title></title>
</head>
<body>
 <!-- Archivo CSS de Bootstrap -->
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
 <!--Biblioteca jQuery -->
 <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
 <!-- Biblioteca Popper (requerida por Bootstrap) -->
 <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
 <!-- Biblioteca JavaScript de Bootstrap -->
 <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
 <!-- Biblioteca Alojado de Google -->
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
 <!-- Enlace a tu archivo de script personalizado -->
 <script src="script.js"></script>

<div class="container mt-4">
    <h1>PRELOVED CLOSET</h1>
    <!-- Barra de búsqueda-->
    <div class="input-group mb-3">
        <input type="text" class="form-control" placeholder="Buscar..." aria-label="Buscar" aria-describedby="basic-addon2">
        <div class="input-group-append">
            <button class="btn btn-outline-secondary" type="button">
                <i class="fa fa-search"></i> <!-- Ícono de lupa (puedes cambiar la clase según la biblioteca de íconos que estés utilizando) -->
            </button>
        </div>
    </div>
        <nav class="navbar navbar-expand-lg navbar-light bg-info">
        <a class="navbar-brand" href="#">Menú</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Mujer <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Niñ@s</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Hombres</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Nuevos Ingresos</a>
              </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Sale</a>
            </li>
          </ul>

            </div>
        </nav>

          
      
          <!-- Optional JavaScript -->
          <!-- jQuery first, then Popper.js, then Bootstrap JS -->
          <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
          <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
          <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>


    </div>

    <button id="Registro" class="btn btn-primary">Registro</button>
    <button id="Inicio" class="btn btn-primary">Inicio sesión</button>
    <p id="demoHideShow">Alarga el ciclo de vida de tus prendas favoritas.</p>

    <!-- Ejemplo de On -->
    <div id="onExample">
        <p>Haz clic en este párrafo.</p>
    </div>

    <!-- Ejemplo de Submit -->
    <form id="submitForm">
        <label for="submitInput">Escribe algo:</label>
        <input type="text" id="submitInput" name="submitInput" class="form-control">
        <button type="submit" class="btn btn-primary mt-2">Submit</button>
    </form>

    <!-- Ejemplo de Mouseover y Mouseout -->
    <div id="mouseExample" class="mt-4 p-3 border border-primary">
        Pasa el ratón sobre este cuadro.
    </div>

    <!-- Ejemplo de Mousedown -->
    <button id="mouseDownBtn" class="btn btn-primary mt-4">Presiona aquí</button>

    <!-- Ejemplo de Input y Focus -->
    <label for="focusInput">Haz clic en este campo:</label>
    <input type="text" id="focusInput" class="form-control">

    <!-- Ejemplo de Click -->
    <button id="clickBtn" class="btn btn-primary mt-4">Haz clic aquí</button>
    <p id="clickOutput"></p>
</div>

</body>
</html># Evaluaci-n3
Evaluación
