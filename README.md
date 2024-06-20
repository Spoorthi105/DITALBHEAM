<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resizable Calculator</title>
    <link rel="stylesheet" href="calculator_style.css">
</head>
<body>
    <div class="calculator">
        <input type="text" id="display" value="0" disabled>
        <button onclick="appendNumber('1')">1</button>
        <button onclick="appendNumber('2')">2</button>
        <button onclick="appendNumber('3')">3</button>
        <button onclick="appendNumber('+')">+</button>
        <button onclick="appendNumber('4')">4</button>
        <button onclick="appendNumber('5')">5</button>
        <button onclick="appendNumber('6')">6</button>
        <button onclick="appendNumber('-')">-</button>
        <button onclick="appendNumber('7')">7</button>
        <button onclick="appendNumber('8')">8</button>
        <button onclick="appendNumber('9')">9</button>
        <button onclick="appendNumber('*')">*</button>
        <button onclick="calculateResult()">=</button>
        <button onclick="appendNumber('0')">0</button>
        <button onclick="appendNumber('.')">.</button>
        <button onclick="appendNumber('/')">/</button>
        <button onclick="clearDisplay()">C</button>
        <div class="resize-handle"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>