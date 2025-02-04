<title>Classificação - UEFA Champions League</title>
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
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 20px;
        margin-top: 40px;
        width: 90%;
        max-width: 1200px;
    }
    .team-card {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
        background-color: #0061F2; /* Azul vibrante */
        padding: 20px;
        border-radius: 15px;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        border: 2px solid #003A5C;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .team-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
    }
    .position {
        font-weight: bold;
        font-size: 2em;
        width: 10%;
    }
    .team-name {
        font-size: 1.6em;
        width: 50%;
        font-weight: bold;
    }
    .points {
        font-size: 1.6em;
        width: 20%;
    }
    button {
        background-color: #003A5C;
        color: white;
        border: none;
        padding: 10px 15px;
        cursor: pointer;
        border-radius: 5px;
        font-size: 1.2em;
        transition: background-color 0.3s ease;
    }
    button:hover {
        background-color: #004BB5;
    }
</style>

<h1 id="classificacao">Classificação - UEFA Champions League</h1>
<div class="container">
    <div class="team-card">
        <div class="position">1</div>
        <div class="team-name">Liverpool</div>
        <div class="points">21 pts</div>
        <a href="https://www.liverpoolfc.com" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">2</div>
        <div class="team-name">Barcelona</div>
        <div class="points">18 pts</div>
        <a href="https://www.fcbarcelona.com" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">3</div>
        <div class="team-name">Atlético de Madrid</div>
        <div class="points">15 pts</div>
        <a href="https://www.atleticodemadrid.com" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">4</div>
        <div class="team-name">Atalanta</div>
        <div class="points">14 pts</div>
        <a href="https://www.atalanta.it" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">5</div>
        <div class="team-name">Arsenal</div>
        <div class="points">13 pts</div>
        <a href="https://www.arsenal.com" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">6</div>
        <div class="team-name">Bayer Leverkusen</div>
        <div class="points">13 pts</div>
        <a href="https://www.bayer04.de" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">7</div>
        <div class="team-name">Internazionale</div>
        <div class="points">13 pts</div>
        <a href="https://www.inter.it" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">8</div>
        <div class="team-name">Aston Villa</div>
        <div class="points">13 pts</div>
        <a href="https://www.avfc.co.uk" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">9</div>
        <div class="team-name">Brest</div>
        <div class="points">13 pts</div>
        <a href="https://www.sb29.bzh" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
    <div class="team-card">
        <div class="position">10</div>
        <div class="team-name">Monaco</div>
        <div class="points">13 pts</div>
        <a href="https://www.asmonaco.com" target="_blank">
            <button>Site do Clube</button>
        </a>
    </div>
</div>
