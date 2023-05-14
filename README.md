<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF=8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Mi Página Web</title>
	<style>
		/* Estilo para el menú */
		nav {
			background-color: #333;
			overflow: hidden;
		}

		nav a {
			float: left;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
			font-size: 17px;
		}

		nav a:hover {
			background-color: #ddd;
			color: black;
		}

		/* Estilo para el contenido */
		.content {
			padding: 20px;
		}

		/* Estilo para el fondo */
		body {
			background-color: #c6e2ff;
		}
	</style>
</head>
<body>
	<!-- El menú -->
	<nav>
		<a href="#">Inicio</a>
		<a href="conexion.html">Gestión de Clientes</a>
		<a href="proveedores.html">Gestión de Proveedores</a>
		<a href="inventario.html">Gestión de Inventario</a>
		<a href="ventas.html">Gestión de Ventas</a>
		<a href="compras.html">Gestión de Compras</a>
		<a href="financiera.html">Gestión Financiera</a>
		<a href="#">Configuración del Sistema</a>
	</nav>

    <?php
      include_once("conexion.php");
      Cconexion:conexionBD();
    ?>

	<!-- El contenido -->
	<div class="content">
		<h1>Bienvenido a mi página web</h1>
		<p>En esta página encontrarás información sobre nuestras diferentes herramientas de gestión.</p>
	</div>
</body>
</html>
