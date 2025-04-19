
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ucapan Selamat Hari Raya Paskah</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-image: url('Bangkit.jpg'); 
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
        }

        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: rgba(0, 0, 0, 0.6); /* Transparan untuk latar belakang */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        }

        h1 {
            font-size: 3em;
            margin-bottom: 20px;
            animation: fadeIn 2s;
        }

        p {
            font-size: 1.5em;
            margin-bottom: 30px;
            animation: fadeIn 2s;
        }

        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
            font-size: 1.2em;
        }

        button:hover {
            background-color: #45a049;
        }

        .hidden {
            display: none;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        #specialMessage {
            margin-top: 20px;
            font-size: 1.2em;
            animation: fadeIn 2s;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Selamat Hari Raya Paskah!</h1>
        <p>Semoga kebangkitan Yesus membawa kedamaian dan kebahagiaan bagi kita semua.</p>
        <button id="showMessageButton">Tampilkan Pesan Spesial</button>
        <div id="specialMessage" class="hidden">
            <h2>Pesan Spesial:</h2>
            <p>Selamat merayakan Paskah! Semoga hari ini dipenuhi dengan cinta, kebahagiaan, dan harapan baru.</p>
            <p>Happy Easter! May this day be filled with love, happiness, and new hope.</p>
            <p>复活节快乐！愿这一天充满爱、幸福和新的希望.</p>
            <p>Sugeng Paskah! Muga-muga dina iki kebak katresnan, rasa seneng lan pangarep-arep anyar.</p>
            <p>부활절 복 많이 받으세요! 오늘이 사랑과 행복, 그리고 새로운 희망으로 가득 차길 바랍니다.

        </div>
    </div>

    <script>
        document.getElementById('showMessageButton').addEventListener('click', function() {
            const messageDiv = document.getElementById('specialMessage');
            if (messageDiv.classList.contains('hidden')) {
                messageDiv.classList.remove('hidden');
                this.textContent = 'Sembunyikan Pesan Spesial';
            } else {
                messageDiv.classList.add('hidden');
                this.textContent = 'Tampilkan Pesan Spesial';
            }
        });
    </script>
</body>
</html>
