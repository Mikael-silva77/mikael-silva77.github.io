<title>Estádios - UEFA Champions League</title>
<style>
    body {
        font-family: 'Arial', sans-serif;
        background-color: #003A5C; 
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0;
        padding: 0;
        text-align: center;
        color: white;
    }
    h1 {
        color: #003366;
        font-size: 3em;
        margin-top: 50px;
        margin-bottom: 40px;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
    }
    .container {
        display: flex;
        flex-wrap: wrap; 
        justify-content: center;
        margin-top: 20px;
        width: 90%;
        max-width: 1200px;
    }
    .stadium-card {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 45%; 
        background-color: #003A5C; 
        padding: 20px;
        border-radius: 15px;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        border: 2px solid #ffffff;
    }
    .stadium-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 12px 30px rgba(0, 0, 0, 0.15);
    }
    .stadium-card h3 {
        font-size: 2em;
        color: #ffffff;
        margin-bottom: 10px;
        font-weight: bold;
    }
    .stadium-card p {
        font-size: 1.2em;
        color: #ffffff; 
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
        <img class="stadium-image" src="/Spain_Catalonia_Barcelona_Nou_Camp_2.jpg" alt="Camp Nou">
    </div>
    <div class="stadium-card">
        <h3>Atlético de Madrid</h3>
        <p>Estádio: Wanda Metropolitano</p>
        <p>Localização: Madrid, Espanha</p>
        <img class="stadium-image" src="/estadio-wanda-metropolitano-m.avif" alt="Wanda Metropolitano">
    </div>
    <div class="stadium-card">
        <h3>Atalanta</h3>
        <p>Estádio: Gewiss Stadium</p>
        <p>Localização: Bérgamo, Itália</p>
        <img class="stadium-image" src="/atalanta.jpg" alt="Gewiss Stadium">
    </div>
    <div class="stadium-card">
        <h3>Arsenal</h3>
        <p>Estádio: Emirates Stadium</p>
        <p>Localização: Londres, Inglaterra</p>
        <img class="stadium-image" src="/estadio arsenal.jpg" alt="Emirates Stadium">
    </div>
    <div class="stadium-card">
        <h3>Bayer Leverkusen</h3>
        <p>Estádio: BayArena</p>
        <p>Localização: Leverkusen, Alemanha</p>
        <img class="stadium-image" src="/estadio bayer leve.jpg" alt="BayArena">
    </div>
    <div class="stadium-card">
        <h3>Internazionale</h3>
        <p>Estádio: San Siro</p>
        <p>Localização: Milão, Itália</p>
        <img class="stadium-image" src="/inter.estadio.jpg" alt="San Siro">
    </div>
    <div class="stadium-card">
        <h3>Aston Villa</h3>
        <p>Estádio: Villa Park</p>
        <p>Localização: Birmingham, Inglaterra</p>
        <img class="stadium-image" src="/aston.jpg" alt="Villa Park">
    </div>
    <div class="stadium-card">
        <h3>Brest</h3>
        <p>Estádio: Stade Francis-Le Ble</p>
        <p>Localização: Brest, França</p>
        <img class="stadium-image" src="/brest.jpg" alt="Stade Francis-Le Ble">
    </div>
    <div class="stadium-card">
        <h3>Monaco</h3>
        <p>Estádio: Stade Louis II</p>
        <p>Localização: Mônaco</p>
        <img class="stadium-image" src="/monaco.jpg" alt="Stade Louis II">
    </div>
</div>
