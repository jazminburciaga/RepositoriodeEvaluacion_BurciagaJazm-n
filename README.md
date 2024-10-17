# RepositoriodeEvaluacion_BurciagaJazm-n
Jazmín Alejandra Burciaga Benítez.

Objetivo: Usar array para poner 5 empleados y su sueldo, y arrar_push para agregar otros 2.

Código:

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>
<?php

$empleados = [
    ["nombre" => "Cesar", "sueldo" => 1500],
    ["nombre" => "Ana", "sueldo" => 2000],
    ["nombre" => "Jose", "sueldo" => 1200],
    ["nombre" => "Manuel", "sueldo" => 1800],
    ["nombre" => "Jorge", "sueldo" => 1600],
];

echo "Lista original de empleados:<br><br>";

foreach ($empleados as $empleado) {
    echo "Nombre: " . $empleado['nombre'] . " - Sueldo: $" . $empleado['sueldo'] . "<br>";
}

array_push($empleados, ["nombre" => "Tyrone", "sueldo" => 2200]);
array_push($empleados, ["nombre" => "Lucia", "sueldo" => 1400]);

echo "<br>Lista actualizada de empleados:<br><br>";

foreach ($empleados as $empleado) {
    echo "Nombre: " . $empleado['nombre'] . " - Sueldo: $" . $empleado['sueldo'] . "<br>";
}

?>

</body>
</html>
