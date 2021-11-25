<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">

    <title>Calculadora</title>
</head>
<body>
    <label for="inputNum1">Digite um número para calcular:</label>
    <br>
    <input type="number" id="inputNum1" placeholder="123">
    <br>
    <label for="inputNum2">Digite outro número para calcular:</label>
    <br>
    <input type="number" id="inputNum2" placeholder="123">
    <br>
    <label>Clique em alguma operação:</label>
    <br>
    <button id="btnSoma">+</button>
    <button id="btnSubtrair" onclick="subtrair()">-</button>
    <button id="btnMultiplicar" onclick="multiplicar()">*</button>
    <button id="btnDividir" onclick="dividir()">/</button>
    <br>
    <label>Resultado:</label>
    <br>
    <input type="number" id="inputResultado" readonly>

    <script src="script.js"></script>
</body>
</html>

