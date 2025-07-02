<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Minha Página Pessoal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Título principal -->
    <h1>João da Silva</h1>

    <!-- Parágrafo com autobiografia -->
    <p>
        Meu nome é João da Silva, tenho 25 anos, moro em Belo Horizonte - MG e sou apaixonado por tecnologia, música e viagens.
        Gosto de aprender coisas novas e estou sempre em busca de novos desafios.
    </p>

    <!-- Botão com JavaScript -->
    <button onclick="mostrarMensagem()">Clique para ver uma mensagem!</button>
    <p id="mensagem"></p>

    <!-- Lista com hobbies -->
    <h2>Meus Hobbies</h2>
    <ul>
        <li>Tocar violão</li>
        <li>Viajar</li>
        <li>Assistir filmes</li>
    </ul>

    <!-- Imagem representando um hobby -->
    <h2>Imagem de um Hobby</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/45/Guitar_%28cort_guitar%29.jpg/320px-Guitar_%28cort_guitar%29.jpg"
         alt="Tocando violão" class="hobby-img">

    <!-- Tabela com países -->
    <h2>Países que gostaria de visitar</h2>
    <table>
        <tr>
            <th>País</th>
            <th>Imagem</th>
        </tr>
        <tr>
            <td>Japão</td>
            <td><img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Tokyo_Montage_2015.jpg" alt="Japão" width="200"></td>
        </tr>
        <tr>
            <td>Itália</td>
            <td><img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Colosseum_in_Rome%2C_Italy_-_April_2007.jpg" alt="Itália" width="200"></td>
        </tr>
        <tr>
            <td>Canadá</td>
            <td><img src="https://upload.wikimedia.org/wikipedia/commons/c/c9/Canada_Montage.png" alt="Canadá" width="200"></td>
        </tr>
    </table>

    <!-- Link de interesse -->
    <h2>Site de Interesse</h2>
    <p>Confira as últimas novidades em tecnologia no <a href="https://www.tecmundo.com.br" target="_blank">TecMundo</a>.</p>

    <!-- Script JavaScript -->
    <script>
        function mostrarMensagem() {
            const mensagem = document.getElementById("mensagem");
            mensagem.textContent = "Seja bem-vindo à minha página! Nunca pare de aprender. 🚀";
        }
    </script>

</body>
</html>
