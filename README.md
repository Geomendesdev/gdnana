<!DOCTYPE html> 
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poesias Espalhadas</title>
    <style>
        /* Estilo da Página */
        body {
            font-family: 'Georgia', serif;
            background-color: #f9f5f2;
            color: #333;
            margin: 0;
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }
        .quote-container {
            background: rgba(255, 255, 255, 0.9); /* Fundo levemente transparente */
            padding: 15px;
            width: 250px; /* Largura fixa para alinhamento */
            border-radius: 8px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s; /* Para efeito de hover */
            cursor: pointer; /* Muda o cursor para indicar interatividade */
        }
        .quote {
            font-size: 1rem;
            line-height: 1.5;
            color: #555;
        }
       .author {
            margin-top: 5px;
            font-style: italic;
            color: #888;
        }
        .source {
            margin-top: 3px;
            font-size: 0.8rem;
            color: #b84e88;
        }
        /* Efeito de hover */
        .quote-container:hover {
            transform: scale(1.05); /* Leve aumento no tamanho */
        }
    </style>
</head>
<body>
    <div class="quote-container">
        <p class="quote">"Eu preciso respirar o mesmo ar que te rodeia, e na pele quero ter o mesmo sol que te bronzeia"</p>
        <p class="author">– Gal Costa</p>
        <p class="source">Livro: Um dia de Domingo</p>
    </div>
    <!-- Frase 1: Livro "É Assim Que Acaba" -->
    <div class="quote-container">
        <p class="quote">"Às vezes as coisas mais simples podem ser as mais impactantes."</p>
        <p class="author">– Colleen Hoover</p>
        <p class="source">Livro: É Assim Que Acaba</p>
    </div>
    <!-- Frase 2: Livro "É Assim Que Acaba" -->
    <div class="quote-container">
        <p class="quote">"Você me deu paz em um mundo que eu não sabia que existia."</p>
        <p class="author">– Colleen Hoover</p>
        <p class="source">Livro: É Assim Que Acaba</p>
    </div>
    <!-- Frase 3: Música "Always" - Daniel Caesar -->
    <div class="quote-container">
        <p class="quote">"E eu estarei aqui, por quê nós duas sabemos como é, eu não quero que as coisas mudem, eu rezo para que permaneçam as mesmas, sempre."</p>
        <p class="author">– Daniel Caesar</p>
        <p class="source">Música: Always</p>
    </div>
    <!-- Frase 4: Música "Always" - Daniel Caesar -->
    <div class="quote-container">
        <p class="quote">"Só saiba que eu não sou uma fase, eu sou pra sempre."</p>
        <p class="author">– Daniel Caesar</p>
        <p class="source">Música: Always</p>
    </div>
    <!-- Frase 5: Música "Um dia de Domingo" - Gal Costa -->
    <div class="quote-container">
        <p class="quote">"Eu preciso te falar, te encontrar de qualquer jeito."</p>
        <p class="author">– Gal Costa</p>
        <p class="source">Música: Um Dia de Domingo</p>
    </div>
    <!-- Frase 6: Música "Eu Amo Você" - Tim Maia -->
    <div class="quote-container">
        <p class="quote">"Eu amo você, menina."</p>
        <p class="author">– Tim Maia</p>
        <p class="source">Música: Eu Amo Você</p>
    </div>
    <!-- Frase 7: Música "Ainda Bem" - Marisa Monte -->
    <div class="quote-container">
        <p class="quote">"Ainda bem que agora eu encontrei você."</p>
        <p class="author">– Marisa Monte</p>
        <p class="source">Música: Ainda Bem</p>
    </div>
    <!-- Frase 8: Música "Pra Você Guardei o Amor" - Nando Reis -->
    <div class="quote-container">
        <p class="quote">"Pra você guardei o amor que nunca soube dar."</p>
        <p class="author">– Nando Reis</p>
        <p class="source">Música: Pra Você Guardei o Amor</p>
    </div>
    <!-- Frase 9: Música "All Star Azul" - Nando Reis -->
    <div class="quote-container">
        <p class="quote">"Estranho seria se eu não me apaixonasse por você."</p>
        <p class="author">– Nando Reis</p>
        <p class="source">Música: All Star</p>
    </div>
    <!-- Frase 10: Música "Tudo em Volta Tem Me Confirmado Bebê" - Tim Bernardes -->
    <div class="quote-container">
        <p class="quote">"Tudo em volta tem me confirmado, bebê, que eu e você somos coisa de alma."</p>
        <p class="author">– Tim Bernardes</p>
        <p class="source">Música: Bebê</p>
    </div>

</body>
</html>
