<title>Estádios - UEFA Champions League</title>
<style>
    body {
        font-family: 'Arial', sans-serif;
        background-color: #003A5C; /* Azul escuro */
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0;
        padding: 0;
        text-align: center;
        color: white;
    }
    h1 {
        color: #ffffff;
        font-size: 3em;
        margin-top: 50px;
        margin-bottom: 40px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
    }
    .container {
        display: flex;
        flex-wrap: wrap; /* Permite que os cartões fiquem em várias linhas */
        justify-content: center; /* Centraliza os cartões */
        gap: 25px;
        margin-top: 20px;
        width: 90%;
        max-width: 1200px;
    }
    .stadium-card {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 45%; /* Cada cartão ocupa 45% da largura, deixando espaço para 2 por linha */
        background-color: #003A5C; /* Fundo azul escuro para os estádios */
        padding: 20px;
        border-radius: 15px;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        border: 2px solid #ffffff; /* Borda branca para destacar o cartão */
    }
    .stadium-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
    }
    .stadium-card h3 {
        font-size: 2em;
        color: #ffffff; /* Título em branco para contraste */
        margin-bottom: 10px;
        font-weight: bold;
    }
    .stadium-card p {
        font-size: 1.2em;
        color: #ffffff; /* Texto em branco */
        margin: 5px 0;
    }
    .stadium-image {
        width: 100%;
        height: auto;
        border-radius: 12px;
        margin-top: 20px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }
</style>

<h1 id="estadio">Estádios dos Clubes</h1>
<div class="container">
    <div class="stadium-card">
        <h3>Liverpool</h3>
        <p>Estádio: Anfield</p>
        <p>Localização: Liverpool, Inglaterra</p>
        <img class="stadium-image" src="/estadio.liv.jpg">
    </div>
    <div class="stadium-card">
        <h3>Barcelona</h3>
        <p>Estádio: Camp Nou</p>
        <p>Localização: Barcelona, Espanha</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Camp_Nou_2021.jpg" alt="Camp Nou">
    </div>
    <div class="stadium-card">
        <h3>Atlético de Madrid</h3>
        <p>Estádio: Wanda Metropolitano</p>
        <p>Localização: Madrid, Espanha</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/a/a2/Wanda_Metropolitano_2017.jpg" alt="Wanda Metropolitano">
    </div>
    <div class="stadium-card">
        <h3>Atalanta</h3>
        <p>Estádio: Gewiss Stadium</p>
        <p>Localização: Bérgamo, Itália</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/a/ab/Stadio_Gewiss.jpg" alt="Gewiss Stadium">
    </div>
    <div class="stadium-card">
        <h3>Arsenal</h3>
        <p>Estádio: Emirates Stadium</p>
        <p>Localização: Londres, Inglaterra</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/0/09/Emirates_Stadium_in_2011.jpg" alt="Emirates Stadium">
    </div>
    <div class="stadium-card">
        <h3>Bayer Leverkusen</h3>
        <p>Estádio: BayArena</p>
        <p>Localização: Leverkusen, Alemanha</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/e/e3/BayArena_Leverkusen.jpg" alt="BayArena">
    </div>
    <div class="stadium-card">
        <h3>Internazionale</h3>
        <p>Estádio: San Siro</p>
        <p>Localização: Milão, Itália</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/1/18/San_Siro_Milan.jpg" alt="San Siro">
    </div>
    <div class="stadium-card">
        <h3>Aston Villa</h3>
        <p>Estádio: Villa Park</p>
        <p>Localização: Birmingham, Inglaterra</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/3/32/Villa_Park_2015.jpg" alt="Villa Park">
    </div>
    <div class="stadium-card">
        <h3>Brest</h3>
        <p>Estádio: Stade Francis-Le Ble</p>
        <p>Localização: Brest, França</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Stade_Francis-Le_Ble.jpg" alt="Stade Francis-Le Ble">
    </div>
    <div class="stadium-card">
        <h3>Monaco</h3>
        <p>Estádio: Stade Louis II</p>
        <p>Localização: Mônaco</p>
        <img class="stadium-image" src="https://upload.wikimedia.org/wikipedia/commons/e/e6/Stade_Louis_II_2015.jpg" alt="Stade Louis II">
    </div>
</div>