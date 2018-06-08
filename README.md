<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css"
     integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
      crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Eater" rel="stylesheet">
    <title>Ejemplo estilización</title>
    <style>
        body {
            font-family: 'Eater', cursive;
        }
        .container {
            border: solid 5px;
            -webkit-border-radius: 40px 10px;
            border-radius: 40px 10px;
            -webkit-box-shadow: 17px 10px 49px 6px rgba(0,0,0,0.75);
            -moz-box-shadow: 17px 10px 49px 6px rgba(0,0,0,0.75);
            box-shadow: 17px 10px 49px 6px rgba(0,0,0,0.75);
            padding: 20px;
        }
        .degradado {
            background: rgba(255,255,255,1);
            background: -moz-linear-gradient(left, rgb(0, 255, 55) 0%, rgb(235, 0, 235) 16%, rgba(216,24,161,1) 34%, rgba(216,24,161,1) 52%, rgba(232,116,199,1) 64%, rgba(255,255,255,1) 82%, rgba(219,54,164,1) 100%);
            background: -webkit-gradient(left top, right top, color-stop(0%, rgba(255,255,255,1)), color-stop(16%, rgba(151,216,195,1)), color-stop(34%, rgba(216,24,161,1)), color-stop(52%, rgba(216,24,161,1)), color-stop(64%, rgba(232,116,199,1)), color-stop(82%, rgba(255,255,255,1)), color-stop(100%, rgba(219,54,164,1)));
            background: -webkit-linear-gradient(left, rgb(136, 255, 0) 0%, rgba(151,216,195,1) 16%, rgba(216,24,161,1) 34%, rgba(216,24,161,1) 52%, rgba(232,116,199,1) 64%, rgba(25,255,255,1) 82%, rgba(219,54,164,1) 100%);
            background: -o-linear-gradient(left, rgb(155, 252, 0) 0%, rgb(255, 0, 255) 16%, rgba(216,24,161,1) 34%, rgba(216,24,161,1) 52%, rgba(232,116,199,1) 64%, rgba(25,255,255,1) 82%, rgba(219,54,164,1) 100%);
            background: -ms-linear-gradient(left, rgb(238, 255, 0) 0%, rgb(0, 153, 255) 16%, rgba(216,24,161,1) 34%, rgba(216,24,161,1) 52%, rgba(232,116,199,1) 64%, rgba(25,255,255,1) 82%, rgba(219,54,164,1) 100%);
            background: linear-gradient(to right, rgb(150, 9, 9) 0%, rgb(99, 148, 133) 16%, rgba(216,24,161,1) 34%, rgba(216,24,161,1) 52%, rgba(232,116,199,1) 64%, rgba(25,255,255,1) 82%, rgba(219,54,164,1) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient( 
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="yo.html">Daniel</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <a class="nav-link" href="file:///D:/desarrollo/8jun2018/index.html">Inicio<span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                Opciones
                </a>
                <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="https://www.youtube.com/">Youtube</a>
                <a class="dropdown-item" href="https://www.Facebook.com/">Facebook</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="https://www.Twitter.com/">Twitter</a>
                </div>
            </li>
            <li class="nav-item">
                <a class="nav-link disabled" href="https://www.google.com">Google</a>
            </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Buscar" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Buscar</button>
            </form>
        </div>
    </nav>
    <script language="javascript">
            function abrir2paginas(){
            window.open('http://www.google.com/', '_blank');
            }
            </script>
    <a href="javascript:abrir2paginas()">Abre google. Clic acá</a>
    <div>
        <a href="da.html">Otra página</a>
    </div>
    <div>
        <img src="danioel.jpeg" >
        <div class="container degradado">
                <h1>Lorem Ipsum</h1>
                <p>
                    Este es un ejemplo de una página
                </p>
                <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
                <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
                <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T" crossorigin="anonymous"></script>
        </div>
    </div>
</body>
</html>
