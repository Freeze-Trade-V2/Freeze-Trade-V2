<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Freeze-Trade-V2</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto+Mono&display=swap" rel="stylesheet">

<style>
/* ======= RESET & BODY ======= */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto Mono', monospace;
    background: linear-gradient(135deg, #0f172a, #1e293b);
    color: white;
    min-height: 100vh;
    overflow-x: hidden;
}

/* ======= TITRE ======= */
h1 {
    text-align: center;
    font-family: 'Orbitron', sans-serif;
    font-size: 3rem;
    margin-top: 30px;
    color: #22c55e;
    text-shadow: 0 0 15px #22c55e, 0 0 30px #16a34a;
}

/* ======= MAIN LAYOUT ======= */
.main {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 40px;
    margin: 50px 20px;
    flex-wrap: wrap;
}

/* ======= IMAGE BOX ======= */
.img-box {
    position: relative;
}

.img-box img {
    width: 300px;
    border-radius: 15px;
    box-shadow: 0 0 30px #22c55e;
    transition: transform 0.3s ease;
}

.img-box img:hover {
    transform: scale(1.05) rotate(-2deg);
}

/* ======= SCRIPT BOX ======= */
.script-box {
    background: #020617;
    padding: 25px;
    border-radius: 20px;
    width: 400px;
    box-shadow: 0 0 40px #22c55e;
    text-align: center;
    transition: transform 0.3s ease;
}

.script-box:hover {
    transform: scale(1.02);
}

.script-box h2 {
    font-family: 'Orbitron', sans-serif;
    font-size: 1.8rem;
    color: #22c55e;
    margin-bottom: 15px;
    text-shadow: 0 0 10px #22c55e;
}

textarea {
    width: 100%;
    height: 180px;
    border-radius: 12px;
    border: none;
    padding: 15px;
    background: #020617;
    color: #22c55e;
    font-family: 'Roboto Mono', monospace;
    font-size: 14px;
    resize: none;
    box-shadow: inset 0 0 15px #16a34a;
}

/* ======= BOUTON ======= */
button {
    margin-top: 15px;
    padding: 15px 25px;
    background: linear-gradient(135deg, #22c55e, #16a34a);
    border: none;
    border-radius: 12px;
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    color: white;
    transition: all 0.3s ease;
    box-shadow: 0 0 15px #22c55e;
}

button:hover {
    transform: scale(1.05);
    background: linear-gradient(135deg, #16a34a, #22c55e);
    box-shadow: 0 0 25px #22c55e;
}

/* ======= DECOR FLOATING ======= */
.brainrot {
    position: absolute;
    width: 60px;
    opacity: 0.8;
    animation: float 6s infinite ease-in-out;
}

@keyframes float {
    0% { transform: translateY(0px) rotate(0deg); }
    50% { transform: translateY(-25px) rotate(10deg); }
    100% { transform: translateY(0px) rotate(0deg); }
}

/* ======= RESPONSIVE ======= */
@media (max-width: 900px) {
    .main {
        flex-direction: column;
        align-items: center;
    }
}
</style>
</head>

<body>

<h1>FREEZE - TRADE - V2</h1>

<!-- DECORATION FLOTTANTE -->
<img class="brainrot" src="https://via.placeholder.com/60?text=🧠" style="top:5%; left:5%;">
<img class="brainrot" src="https://via.placeholder.com/60?text=🧠" style="top:80%; left:10%;">
<img class="brainrot" src="https://via.placeholder.com/60?text=🧠" style="top:25%; right:15%;">
<img class="brainrot" src="https://via.placeholder.com/60?text=🧠" style="top:70%; right:5%;">

<div class="main">

    <div class="img-box">
        <img src="https://via.placeholder.com/300x200.png?text=Roblox+Game">
    </div>

    <div class="script-box">
        <h2>🔥 FREE TRADE SCRIPT 🔥</h2>
        <textarea id="script" readonly>
loadstring(game:HttpGet("https://pastebin.com/raw/XXRrP5uD"))()
        </textarea>
        <button onclick="copyScript()">📋 Copier le Script</button>
    </div>

    <div class="img-box">
        <img src="https://via.placeholder.com/300x200.png?text=Oberan+Road+Style">
    </div>

</div>

<script>
function copyScript() {
    const text = document.getElementById("script").value;
    navigator.clipboard.writeText(text)
        .then(() => { alert("Script copié !"); })
        .catch(() => { alert("Impossible de copier !"); });
}
</script>

</body>
</html>
