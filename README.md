<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luhn's Algorithm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        h1 {
            color: #333;
            font-size: 24px;
            margin-bottom: 20px;
        }
        p {
            color: #666;
            font-size: 16px;
            margin-bottom: 10px;
        }
        ol {
            color: #444;
            font-size: 16px;
            margin-left: 20px;
        }
        li {
            margin-bottom: 5px;
        }
    </style>
</head>
<body>
    <h1>Luhn’s Algorithm (Modulus 10 Algorithm)</h1>
    <p>Luhn’s algorithm, also known as the modulus 10 algorithm, is a simple checksum formula used to validate credit card numbers.</p>
    <p>It ensures that the entered credit card number has a valid structure before further processing.</p>
    <p>The algorithm works by verifying the sum of certain digits in the card number against a check digit.</p>
    <h2>How Luhn’s Algorithm Works:</h2>
    <ol>
        <li>Starting from the rightmost digit (excluding the check digit), double every second digit.</li>
        <li>If the result of doubling exceeds 9, subtract 9 from it.</li>
        <li>Sum up all the digits (including the unchanged ones).</li>
        <li>The check digit (the last digit) should make the total sum a multiple of 10.</li>
    </ol>
</body>
</html>
