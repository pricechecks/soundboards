<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instant Sound Buttons</title>
    <style>
        :root {
            --bg-color: #121214;
            --card-bg: #1a1a1e;
            --text-color: #ffffff;
            --text-muted: #a0a0a5;
            --search-bg: #26262b;
            --button-shadow: rgba(0, 0, 0, 0.4);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            max-width: 1200px;
            text-align: center;
            margin-bottom: 30px;
        }

        h1 {
            font-size: 2.5rem;
            font-weight: 800;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #ff416c, #ff4b2b);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .search-container {
            width: 100%;
            max-width: 500px;
            margin: 0 auto;
        }

        #search-bar {
            width: 100%;
            padding: 14px 20px;
            border-radius: 25px;
            border: none;
            background-color: var(--search-bg);
            color: var(--text-color);
            font-size: 1rem;
            outline: none;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
        }

        #search-bar:focus {
            box-shadow: 0 4px 15px rgba(255, 65, 108, 0.4);
            background-color: #2e2e35;
        }

        .soundboard-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
            gap: 20px;
            width: 100%;
            max-width: 1200px;
            padding: 10px;
        }

        .sound-card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 15px 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .sound-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }

        /* The MyInstants Circular Button style */
        .instant-btn {
            width: 75px;
            height: 75px;
            border-radius: 50%;
            border: none;
            cursor: pointer;
            position: relative;
            box-shadow: 0 8px 0 var(--shadow-color), 0 8px 10px var(--button-shadow);
            transition: all 0.1s ease;
            margin-bottom: 15px;
            outline: none;
        }

        .instant-btn:active {
            transform: translateY(6px);
            box-shadow: 0 2px 0 var(--shadow-color), 0 2px 5px var(--button-shadow);
        }

        .sound-title {
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--text-color);
            line-height: 1.3;
            word-break: break-word;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
            height: 2.6rem;
        }

        /* Color Variations for the buttons */
        .btn-red { background: #ff416c; --shadow-color: #bd1a3c; }
        .btn-blue { background: #00b4db; --shadow-color: #007791; }
        .btn-green { background: #11998e; --shadow-color: #0b665f; }
        .btn-yellow { background: #f1c40f; --shadow-color: #b7950b; }
        .btn-purple { background: #8e44ad; --shadow-color: #623078; }
        .btn-orange { background: #e67e22; --shadow-color: #b35c16; }
    </style>
</head>
<body>

    <header>
        <h1>Instant Buttons</h1>
        <div class="search-container">
            <input type="text" id="search-bar" placeholder="Search sounds..." onkeyup="filterSounds()">
        </div>
    </header>

    <main class="soundboard-grid" id="soundboard">
        <!-- Sound Card Template -->
        <!-- Replace the audio URLs with your own school-accessible MP3 links -->
        <div class="sound-card">
            <button class="instant-btn btn-red" onclick="playSound('audio-airhorn')"></button>
            <div class="sound-title">Airhorn</div>
            <audio id="audio-airhorn" src="https://soundjay.com" preload="auto"></audio>
        </div>

        <div class="sound-card">
            <button class="instant-btn btn-blue" onclick="playSound('audio-buzzer')"></button>
            <div class="sound-title">Wrong Buzzer</div>
            <audio id="audio-buzzer" src="https://soundjay.com" preload="auto"></audio>
        </div>

        <div class="sound-card">
            <button class="instant-btn btn-green" onclick="playSound('audio-bell')"></button>
            <div class="sound-title">Service Bell</div>
            <audio id="audio-bell" src="https://soundjay.com" preload="auto"></audio>
        </div>

        <div class="sound-card">
            <button class="instant-btn btn-yellow" onclick="playSound('audio-chime')"></button>
            <div class="sound-title">Success Chime</div>
            <audio id="audio-chime" src="https://soundjay.com" preload="auto"></audio>
        </div>

        <div class="sound-card">
            <button class="instant-btn btn-purple" onclick="playSound('audio-click')"></button>
            <div class="sound-title">Camera Click</div>
            <audio id="audio-click" src="https://soundjay.com" preload="auto"></audio>
        </div>

        <div class="sound-card">
            <button class="instant-btn btn-orange" onclick="playSound('audio-pop')"></button>
            <div class="sound-title">Bubble Pop</div>
            <audio id="audio-pop" src="https://soundjay.com" preload="auto"></audio>
        </div>
    </main>

    <script>
        // Function to play sound and reset it if clicked repeatedly
        function playSound(audioId) {
            const sound = document.getElementById(audioId);
            if (sound) {
                sound.currentTime = 0;
                sound.play();
            }
        }

        // Search filtering mechanism
        function filterSounds() {
            const input = document.getElementById('search-bar').value.toLowerCase();
            const cards = document.getElementsByClassName('sound-card');

            for (let i = 0; i < cards.length; i++) {
                const title = cards[i].getElementsByClassName('sound-title')[0].innerText.toLowerCase();
                if (title.includes(input)) {
                    cards[i].style.display = "flex";
                } else {
                    cards[i].style.display = "none";
                }
            }
        }
    </script>
</body>
</html>
