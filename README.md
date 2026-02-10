# LOML
LOML
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>This is only for My Love❤️</title>

<style>
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: linear-gradient(#ffb6c1, #ffe4e1);
    text-align: center;
    color: #b30059;
}

.container {
    padding: 20px;
}

h1 {
    font-size: 28px;
}

.message {
    background: white;
    padding: 15px;
    margin: 15px 0;
    border-radius: 15px;
    box-shadow: 0 0 10px pink;
}

button {
    background: #ff4d88;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 25px;
    font-size: 16px;
    cursor: pointer;
    margin: 10px;
}

button:hover {
    background: #e6005c;
}

#surprise {
    font-size: 18px;
    margin-top: 15px;
}
</style>
</head>

<body>

<div class="container">

<h1>For You</h1>

<p>Helluu Snehuuu🧿🫶  
I have made this only for you…</p>

<div class="message">
শুভ সকাল Bbuu<3😘🎀
</div>

<button onclick="showSurprise()">🎁 Click for Surprise</button>

<button onclick="showLove()">💌 Another Message</button>

<p id="surprise"></p>

</div>

<script>
let count = 0;

function showSurprise() {
    document.getElementById("surprise").innerHTML =
    "Maii hi hu surprise apke life me😼🎀💌";
}

function showLove() {

    const messages = [
        "I Love You🧿❤️",
    ];

    document.getElementById("surprise").innerHTML =
    messages[count];

    count = (count + 1) % messages.length;
}
</script>

</body>
</html>
