# pagina-del-robot
24/09/2025
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIENDA SUPER ROBOT</title>
    <link rel="icon" type="image/png" href="imagen/eva2.webp">
    <style>
        /*MENU SUPERIOR*/
        nav{
        background: yellowgreen;
        padding: 10px 0;
        }
        nav ul{
            list-style: none;
            margin: 0;
            padding: 0;
            justify-content: center;
            display: flex;}
            nav ul li{
                margin: 0 15px;

            }
            nav ul li a{
                color : #fff;
                text-decoration: none; 
                font-weight: bold;
                transition: color 0.3s;
            }
            nav ul li a:hover{
                color:#ff0000
            }
        .contenedor {
            background-color: gray;
            display: flex;
            flex-direction: column;
        flex-wrap: wrap;
        justify-content: space-around;}
            .titulo, .imagen{
                text-align: center;
                flex-basis: 100px;
                flex-grow: 1;}
                .imagen img{
                    max-width: 100%;
                    height: auto;
                    border-radius: 15px;
                    box-shadow: 0px 4px 10px  rgba(0,0,0.3);
                    height: auto;}
        footer{ background: #022;
        color: #fff;
        text-align: center;
        padding: 15px 0;
        margin-top: 20px;
        font-size: 14px;}
    </style>
</head>

<body>
    <!--MENU DE NAVEGACION-->
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">productos</a></li>
            <li><a href="#">ofertas</a></li>
            <li><a href="#">contactos</a></li>
        </ul>


    </nav>
    <div class="contenedor">

        <div class='titulo'>
            <h1>Bienvenidos a la tienda SuperRobot</h1>
        </div>

        <div class="imagen">
            <img src='imagen/eva2.webp' ; width="300">
        </div>
        
        <div class="titulo">
            <h2>Descubre el juguete mas emocionante del año</h2>
        </div>
    </div>
        <footer>
            @ 2025 
        </footer>


</body>
</html>
