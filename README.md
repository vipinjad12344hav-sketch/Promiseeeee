# Promiseeeee
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Promise Day Saeee</title>

<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(135deg, #ff758c, #ff7eb3);
        text-align: center;
        color: white;
        overflow: hidden;
    }

    h1 {
        margin-top: 40px;
        font-size: 2.5rem;
    }

    h2 {
        font-weight: normal;
        margin-top: 10px;
    }

    .card {
        background: rgba(255,255,255,0.15);
        margin: 40px auto;
        padding: 25px;
        width: 90%;
        max-width: 420px;
        border-radius: 25px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }

    .card p {
        font-size: 1.1rem;
        line-height: 1.7;
    }

    button {
        margin-top: 15px;
        padding: 12px 28px;
        font-size: 1rem;
        border: none;
        border-radius: 30px;
        background: white;
        color: #ff4d6d;
        cursor: pointer;
        transition: 0.3s;
        font-weight: bold;
    }

    button:hover {
        transform: scale(1.08);
        background: #ffe0ec;
    }

    .heart {
        position: fixed;
        top: -40px;
        font-size: 28px;
        animation: fall linear infinite;
    }

    @keyframes fall {
        0% { transform: translateY(0); opacity: 1; }
        100% { transform: translateY(110vh); opacity: 0; }
    }
</style>
</head>

<body>

<h1>💖 Happy Promise Day 💖</h1>
<h2>For My Saeee 💍💕</h2>

<div class="card">
    <p>
        Saeee ❤️<br><br>
        On this Promise Day,<br>
        I promise to stand beside you<br>
        in every happiness and every problem 💕<br><br>

        I promise to respect you,<br>
        care for you, and choose you<br>
        every single day 💞<br><br>

        No matter what happens,<br>
        my heart will always belong to you 💖
    </p>

    <button onclick="showPromise()">My Promise 🤝</button><br>
    <button onclick="foreverStay()">Will You Forever Stay? 💍</button>
</div>

<script>
function showPromise() {
    alert("Saeee 💖 I promise to love you truly, respect you always, and never give up on us.");
}

function foreverStay() {
    alert("Saeee 🥺💍 Will you forever stay with me and make every Promise Day special? ❤️");
}

// Falling hearts animation
setInterval(() => {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (3 + Math.random() * 3) + "s";
    document.body.appendChild(heart);

    setTimeout(() => {
        heart.remove();
    }, 6000);
}, 300);
</script>

</body>
</html>
