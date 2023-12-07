<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pra vc 💖</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #111;
            color: #fff;
            text-align: center;
            padding: 50px;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        h1 {
            color: #e6005c;
        }

        label {
            font-size: 18px;
            color: #ccc;
            margin-top: 20px;
        }

        #nome {
            padding: 10px;
            font-size: 16px;
            width: 200px;
            margin-top: 10px;
            background-color: #444;
            color: #fff;
            border: 1px solid #555;
        }

        #enviar {
            background-color: #e6005c;
            color: #fff;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            margin-top: 20px;
        }

        #mensagem {
            font-size: 24px;
            color: #e6005c;
            margin-top: 20px;
        }

        #imagem-banda {
            max-width: 70%;
            margin-top: 20px;
        }
    <style>

    /* ... Outros estilos ... */

    #imagem-banda {
        max-width: 100%;
        width: 270px; /* Ajuste o tamanho conforme necessário */
        margin-top: 20px;
    }
</style>



    </style>S
</head>
<body>

    <h1>Declaração de Amor 💖</h1>

    <label for="nome">digite seu nome ai more, quero te dizer algo:</label>
    <input type="text" id="nome" placeholder="Nome">

    <button id="enviar" onclick="exibirMensagem()"> clica ai gostosa</button>

    <div id="mensagem"></div>

    <!-- Adicione o caminho da imagem da banda -->
    <img id="imagem-banda" src="system.jpg" alt="System of a Down">

    <script>
        function exibirMensagem() {
            var nome = document.getElementById("nome").value;
            var mensagemDiv = document.getElementById("mensagem");

            if (nome.trim() !== "") {
     var mensagem = nome + " obg por tudo, vc sempre vai ser unica pra mim. nuca me deixe, sua presença significa muito pra mim.💖"
                mensagemDiv.innerHTML = mensagem;
            } else {
                mensagemDiv.innerHTML = "Por favor, insira um nome válido.";
            }
        }
    </script>
<p>Compartilhe este link com a pessoa amada: <a href="file:///C:/Users/USUARIO/Desktop/JAVA%20SCRIPT/Aula%2009/index.html ">Clique aqui</a></p>
</body>
</html>
