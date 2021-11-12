<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Formulario con estilos</title>
		<link rel="Stylesheet" type="text/css" href="RVCstyles.css">
	</head>
	<body>
		<div>
			<form mnethod="POST" action="http://formadorestic.com/alumnosdaw/procesaformulario.php">
				<label for="nombre">Nombre</label><br>
					<input type="text" name="nombre" placeholder="Introduzca nombre" id="nombre" required>  <br><br>
				<label for="edad">Edad</label><br>
					<input type="number" name="edad" placeholder="Introduzca edad" id="edad" required>
					<br><br>
					<input type="submit" value="Enviar" class="tamaño">
			</form>
		</div>
	</body>
</html>
