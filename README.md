<!DOCTYPE html>
<html>
<head>
    <style>
        @keyframes blink {
            0%, 100% {
                visibility: hidden;
            }
            50% {
                visibility: visible;
            }
        }
        .blinking-text {
            animation: blink 1s infinite;
        }
    </style>
</head>
<body>
    <h1 class="blinking-text">Texto Piscante</h1>
</body>
</html>
