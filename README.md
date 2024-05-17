# PARA CAMILA IMPORTANTE
<!DOCTYPE html>
<html>
<head>
    <title>Convite para o Parque</title>
    <style>
        body {
            background-color: #C8A2C8; /* Cor lilás */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-size: 2rem;
            color: white;
        }

        #no {
            position: absolute;
            transition: 1s; /* Efeito de transição suavizado */
        }
    </style>
</head>
<body>
    <h1>Quer ir ao parque comigo amanhã às 18:45?</h1>
    <button id="yes">Sim</button>
    <button id="no">Não</button>

    <script>
        document.getElementById('yes').addEventListener('click', function() {
            window.location.href = 'https://youtu.be/orWnzqBA63w?si=icu_EMrRG4AcaD2B';
        });

        document.getElementById('no').addEventListener('mouseover', function() {
            const maxVal = 500;
            let x = Math.floor(Math.random() * maxVal);
            let y = Math.floor(Math.random() * maxVal);
            this.style.left = `${x}px`;
            this.style.top = `${y}px`;
        });
    </script>
</body>
</html>
