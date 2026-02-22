<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>NAHID V2 AI</title>
    <!-- Firebase SDK -->
    <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.6.1/firebase-database-compat.js"></script>

    <style>
        body, html { margin: 0; padding: 0; height: 100%; overflow: hidden; background: #000; font-family: 'Arial', sans-serif; }
        #bg-frame { width: 100%; height: 100%; border: none; position: absolute; top: 0; left: 0; z-index: 1; }
        #hack-container {
            position: fixed; top: 45%; left: 50%; 
            transform: translate(-50%, -50%);
            z-index: 1000; width: 130px; 
            background: rgba(0, 0, 0, 0.95); 
            border-radius: 25px; 
            display: flex; flex-direction: column; align-items: center; justify-content: center;
            color: #fff; text-align: center; border: 2px solid #fff;
            animation: rgb-shikimiki 2s linear infinite;
            padding: 10px; 
            cursor: move; touch-action: none;
        }
        @keyframes rgb-shikimiki {
            0% { border-color: #ff0000; box-shadow: 0 0 10px #ff0000; }
            33% { border-color: #00ff00; box-shadow: 0 0 10px #00ff00; }
            66% { border-color: #0000ff; box-shadow: 0 0 10px #0000ff; }
            100% { border-color: #ff0000; box-shadow: 0 0 10px #ff0000; }
        }
        .ai-title { font-size: 11px; font-weight: 900; color: #fff; margin-bottom: 5px; text-transform: uppercase; text-shadow: 0 0 4px #fff; }
        .tg-link { font-size: 9px; font-weight: bold; color: #00d4ff; text-decoration: none; margin-top: 5px; border-top: 1px solid #444; width: 95%; padding-top: 5px; }
        #login-content { width: 100%; display: flex; flex-direction: column; align-items: center; }
        #login-content input {
            width: 85%; padding: 5px; border-radius: 8px; border: 1px solid #fff;
            background: #111; color: #fff; text-align: center; font-size: 10px; margin-bottom: 5px; outline: none;
        }
        #login-content button {
            width: 90%; background: #ffcc00; border: none; padding: 6px; border-radius: 12px;
            font-weight: bold; cursor: pointer; color: #000; font-size: 10px;
        }
        #signal-content { display: none; width: 100%; flex-direction: column; align-items: center; }
        .timer { font-size: 11px; font-weight: bold; color: #00ff00; margin-bottom: 2px; }
        .prediction { font-size: 22px; font-weight: 900; letter-spacing: 1px; margin: 2px 0; }
        .period { font-size: 9px; color: #ddd; font-weight: bold; }
        .big-text { color: #00ff00; text-shadow: 0 0 10px #00ff00; }
        .small-text { color: #ff0055; text-shadow: 0 0 10px #ff0055; }
    </style>
</head>
<body>

    <iframe id="bg-frame" src="https://www.tigro333.com/#/register?invitationCode=15887353739"></iframe>

    <div id="hack-container">
        <div class="ai-title">NAHID V2 AI</div>

        <div id="login-content">
            <input type="password" id="passInput" placeholder="Password">
            <button onclick="unlock()">LOGIN</button>
        </div>

        <div id="signal-content">
            <div id="timer" class="timer">--:--</div>
            <div id="prediction" class="prediction">WAIT</div>
            <div id="period" class="period">PERIOD : ---</div>
        </div>

        <a href="https://t.me/boomshotgroup" target="_blank" class="tg-link">JOIN TELEGRAM</a>
    </div>

    <script>
        // --- Firebase Configuration ---
        const firebaseConfig = {
            apiKey: "AIzaSyCeWRsDw7O1fpoqqsJdVCk2m7Z5Iq5k8XM",
            authDomain: "admin-2-9ea22.firebaseapp.com",
            databaseURL: "https://admin-2-9ea22-default-rtdb.firebaseio.com",
            projectId: "admin-2-9ea22",
            storageBucket: "admin-2-9ea22.firebasestorage.app",
            messagingSenderId: "725128733136",
            appId: "1:725128733136:web:51c77c79671ded0c4a59d5",
            measurementId: "G-R85159RV81"
        };
        firebase.initializeApp(firebaseConfig);
        const database = firebase.database();

        let dbPassword = ""; // অ্যাডমিন প্যানেল থেকে আসবে

        // ডাটাবেস থেকে পাসওয়ার্ড রিয়েলটাইমে আপডেট রাখা
        database.ref("settings/password").on("value", (snapshot) => {
            dbPassword = snapshot.val();
        });

        function unlock() {
            const passInput = document.getElementById('passInput').value;
            if(passInput === dbPassword) {
                document.getElementById('login-content').style.display = 'none';
                document.getElementById('signal-content').style.display = 'flex';
                startLogic();
            } else {
                alert("Incorrect Password!");
                window.location.href = "https://t.me/Owner_Nahid_Vai";
            }
        }

        // --- Draggable Logic ---
        const box = document.getElementById("hack-container");
        let active = false, currentX, currentY, initialX, initialY, xOffset = 0, yOffset = 0;
        box.addEventListener("touchstart", dragStart); box.addEventListener("mousedown", dragStart);
        document.addEventListener("touchend", dragEnd); document.addEventListener("mouseup", dragEnd);
        document.addEventListener("touchmove", drag); document.addEventListener("mousemove", drag);
        function dragStart(e) {
            initialX = (e.type === "touchstart" ? e.touches[0].clientX : e.clientX) - xOffset;
            initialY = (e.type === "touchstart" ? e.touches[0].clientY : e.clientY) - yOffset;
            if (e.target === box || box.contains(e.target)) active = true;
        }
        function dragEnd() { active = false; }
        function drag(e) {
            if (active) {
                e.preventDefault();
                currentX = (e.type === "touchmove" ? e.touches[0].clientX : e.clientX) - initialX;
                currentY = (e.type === "touchmove" ? e.touches[0].clientY : e.clientY) - initialY;
                xOffset = currentX; yOffset = currentY;
                box.style.transform = `translate(${currentX}px, ${currentY}px)`;
            }
        }

        // --- Prediction Logic ---
        let nextPrediction = "WAIT";
        let nextPeriodText = "---";

        function analyzeMarket(history) {
            let patterns = history.map(item => parseInt(item.number) <= 4 ? 'S' : 'B');
            let bigCount = patterns.slice(0, 5).filter(x => x === 'B').length;
            return bigCount >= 3 ? "BIG" : "SMALL";
        }

        function startLogic() {
            const API = "https://draw.ar-lottery01.com/WinGo/WinGo_30S/GetHistoryIssuePage.json?t=";
            let lastCalculatedPeriod = "";
            setInterval(async () => {
                try {
                    const r = await fetch(API + Date.now());
                    const d = await r.json();
                    const list = d.data.list;
                    const nextP = (BigInt(list[0].issueNumber) + 1n).toString().slice(-3);
                    if(lastCalculatedPeriod !== nextP) {
                        lastCalculatedPeriod = nextP;
                        nextPeriodText = "PERIOD : " + nextP;
                        nextPrediction = analyzeMarket(list);
                    }
                } catch(e){}
            }, 1000);

            setInterval(() => {
                let now = new Date();
                let s = 30 - (now.getSeconds() % 30);
                const predDiv = document.getElementById('prediction');
                if (s >= 29 || predDiv.innerText === "WAIT") {
                    predDiv.innerText = nextPrediction;
                    predDiv.className = "prediction " + (nextPrediction === "BIG" ? "big-text" : "small-text");
                    document.getElementById('period').innerText = nextPeriodText;
                }
                document.getElementById('timer').innerText = "00:" + (s < 10 ? "0"+s : s);
            }, 1000);
        }
    </script>
</body>
</html>
