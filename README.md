# projeto-agrinho-2026-1
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agrinho 2026</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header class="hero">
    <div class="overlay">
        <h1>AGRINHO 2026</h1>
        <h2>Campo e Cidade: Conexão que Alimenta o Brasil</h2>

        <p>
            O campo e a cidade dependem um do outro. Enquanto o campo produz
            alimentos e matérias-primas, a cidade transforma, distribui e
            consome esses produtos. Essa relação fortalece a economia e melhora
            a qualidade de vida da população.
        </p>

        <a href="https://www.youtube.com/watch?v=-TgSctIqbJM" target="_blank" class="botao">
            Saiba Mais
        </a>
    </div>
</header>

<section class="sobre">
    <h2>O que é o Agrinho?</h2>

    <p>
        O Programa Agrinho é uma iniciativa educacional que incentiva a reflexão
        sobre cidadania, sustentabilidade, meio ambiente e a importância da
        integração entre o campo e a cidade.
    </p>

    <p>
        O agronegócio está presente na vida de todos os brasileiros. Os alimentos,
        roupas e diversos produtos utilizados diariamente têm origem no trabalho
        realizado no campo.
    </p>
</section>

<section class="cards">

    <div class="card">
        <h3>🌱 Agricultura</h3>
        <p>
            A agricultura fornece alimentos essenciais para milhões de pessoas
            e contribui significativamente para a economia brasileira.
        </p>
    </div>

    <div class="card">
        <h3>🚜 Tecnologia</h3>
        <p>
            Máquinas modernas, drones e sensores ajudam os produtores a aumentar
            a produtividade e reduzir desperdícios.
        </p>
    </div>

    <div class="card">
        <h3>🌎 Sustentabilidade</h3>
        <p>
            O uso consciente dos recursos naturais garante produção eficiente
            sem comprometer o futuro das próximas gerações.
        </p>
    </div>

    <div class="card">
        <h3>🏙 Cidade</h3>
        <p>
            A cidade depende dos produtos do campo para abastecer mercados,
            indústrias e toda a população.
        </p>
    </div>

</section>

<section class="curiosidade">
    <h2>Curiosidades do Campo</h2>

    <p id="textoCuriosidade">
        Clique no botão para descobrir uma curiosidade.
    </p>

    <button id="btnCuriosidade">
        Mostrar Curiosidade
    </button>
</section>

<script src="script.js"></script>
</body>
</html>
<section class="cards">

    <div class="card">
        <img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399" alt="Agricultura">
        <h3>🌱 Agricultura</h3>
        <p>
            A agricultura fornece alimentos essenciais para milhões de pessoas e
            é uma das bases da economia brasileira.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854" alt="Tecnologia no Campo">
        <h3>🚜 Tecnologia</h3>
        <p>
            Máquinas modernas, GPS, drones e sensores ajudam os produtores a
            aumentar a produtividade.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1473448912268-2022ce9509d8" alt="Sustentabilidade">
        <h3>🌎 Sustentabilidade</h3>
        <p>
            A preservação da natureza é fundamental para garantir recursos para
            as próximas gerações.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1449824913935-59a10b8d2000" alt="Cidade">
        <h3>🏙 Cidade</h3>
        <p>
            As cidades dependem dos alimentos e matérias-primas produzidos no
            campo para seu desenvolvimento.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1523741543316-beb7fc7023d8" alt="Pecuária">
        <h3>🐄 Pecuária</h3>
        <p>
            A criação de animais fornece carne, leite, couro e diversos produtos
            importantes para a sociedade.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1494526585095-c41746248156" alt="Transporte">
        <h3>🚚 Transporte</h3>
        <p>
            Caminhões, navios e trens ajudam a levar a produção rural para todas
            as regiões do país.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1517048676732-d65bc937f952" alt="Educação">
        <h3>📚 Educação</h3>
        <p>
            A educação ajuda a formar cidadãos conscientes sobre a importância
            do campo e da sustentabilidade.
        </p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c" alt="Inovação">
        <h3>💡 Inovação</h3>
        <p>
            Novas tecnologias estão transformando o agronegócio e tornando a
            produção mais eficiente.
        </p>
    </div>

</section>
<footer>
    <p>Projeto Agrinho 2026</p>
    <p>Feito por João Pedro Vaz</p>
</footer>*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, sans-serif;
    background:#f4f4f4;
    color:#333;
}

.hero{
    height:100vh;
    background:url("https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&w=1600&q=80");
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
}

.overlay{
    background:rgba(0,0,0,0.6);
    color:white;
    text-align:center;
    padding:40px;
    border-radius:15px;
    width:80%;
}

.overlay h1{
    font-size:4rem;
    margin-bottom:15px;
}

.overlay h2{
    font-size:2rem;
    margin-bottom:20px;
}

.overlay p{
    font-size:1.2rem;
    margin-bottom:20px;
}

.botao{
    background:#2e7d32;
    color:white;
    padding:15px 30px;
    text-decoration:none;
    border-radius:10px;
    font-weight:bold;
}

.botao:hover{
    background:#1b5e20;
}

.sobre{
    padding:60px;
    text-align:center;
    background:white;
}

.sobre h2{
    color:green;
    font-size:2.5rem;
    margin-bottom:20px;
}

.sobre p{
    max-width:1000px;
    margin:20px auto;
    font-size:1.2rem;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    padding:50px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    color:green;
    margin-bottom:15px;
}

.curiosidade{
    text-align:center;
    padding:60px;
    background:#e8f5e9;
}

.curiosidade h2{
    color:green;
    margin-bottom:20px;
}

.curiosidade p{
    font-size:1.2rem;
    margin-bottom:20px;
}

.curiosidade button{
    padding:15px 30px;
    border:none;
    background:green;
    color:white;
    border-radius:10px;
    cursor:pointer;
}

.curiosidade button:hover{
    background:darkgreen;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
.card img{
    width:100%;
    height:220px;
    object-fit:cover;
    border-radius:10px;
    margin-bottom:15px;
}

.card{
    overflow:hidden;
}

.card img:hover{
    transform:scale(1.05);
    transition:0.5s;
}const curiosidades = [
    "O Brasil é um dos maiores produtores de alimentos do mundo.",
    "Muitos agricultores utilizam drones para monitorar plantações.",
    "A agricultura sustentável ajuda a preservar o meio ambiente.",
    "O campo produz alimentos que chegam diariamente às cidades.",
    "A tecnologia tem transformado a produção agrícola moderna.",
    "O agronegócio gera milhões de empregos no Brasil."
];

const botao = document.getElementById("btnCuriosidade");
const texto = document.getElementById("textoCuriosidade");

botao.addEventListener("click", () => {
    const numero = Math.floor(Math.random() * curiosidades.length);
    texto.textContent = curiosidades[numero];
});
