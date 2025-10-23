<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Bulan Suci Ramadhan - Zainal Family</title>
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(to right bottom, #4CAF50, #8BC34A); /* Gradasi hijau yang menenangkan */
            color: #fff;
            text-align: center;
            overflow: hidden; 
            position: relative;
        }

        /* Background pattern/overlay */
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('data:image/svg+xml;utf8,<svg width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg"><g fill="%23FFFFFF" opacity="0.1"><path d="M0 0h50v50H0V0zm50 50h50v50H50V50z"/></g></svg>');
            background-size: 20px 20px;
            opacity: 0.15;
            animation: movePattern 20s linear infinite;
        }

        @keyframes movePattern {
            from {
                background-position: 0 0;
            }
            to {
                background-position: 100px 100px;
            }
        }

        .card {
            background: rgba(255, 255, 255, 0.15); /* Transparan */
            backdrop-filter: blur(10px); /* Efek blur pada background */
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
            border: 1px solid rgba(255, 255, 255, 0.18);
            max-width: 500px;
            position: relative;
            z-index: 10;
            animation: fadeIn 1.5s ease-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 4em;
            margin-bottom: 10px;
            color: #FFEB3B; /* Emas cerah */
            text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
            line-height: 1.1;
        }

        h2 {
            font-family: 'Poppins', sans-serif;
            font-size: 1.8em;
            color: #F8F8F8;
            margin-top: 0;
            margin-bottom: 25px;
            font-weight: 600;
        }

        p {
            font-size: 1.1em;
            line-height: 1.7;
            margin-bottom: 20px;
            color: #E0E0E0;
        }

        .highlight {
            font-weight: 600;
            color: #FFEB3B; /* Emas cerah */
        }

        .sender-name {
            font-family: 'Great Vibes', cursive;
            font-size: 2.2em;
            color: #FFEB3B;
            margin-top: 40px;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
            display: block; /* Agar menempati baris baru */
        }

        .salam {
            margin-top: 10px;
            padding-top: 5px;
            font-style: italic;
            color: #E0E0E0;
            font-size: 1em;
        }

        /* Elemen dekoratif islami (sama seperti sebelumnya) */
        .decor-top-left, .decor-bottom-right {
            position: absolute;
            width: 80px;
            height: 80px;
            opacity: 0.3;
        }

        .decor-top-left {
            top: -20px;
            left: -20px;
            transform: rotate(45deg);
        }

        .decor-bottom-right {
            bottom: -20px;
            right: -20px;
            transform: rotate(225deg);
        }
    </style>
</head>
<body>
    <div class="decor-top-left">
        <img src="https://i.imgur.com/rN5xR3c.png" alt="Islamic Decor" style="width:100%; height:auto;">
    </div>
    <div class="decor-bottom-right">
        <img src="https://i.imgur.com/rN5xR3c.png" alt="Islamic Decor" style="width:100%; height:auto;">
    </div>

    <div class="card">
        <h1>Ramadhan Kareem</h1>
        <h2>Selamat Menunaikan Ibadah Puasa</h2>
        <p>
            Dengan kerendahan hati, kami mengucapkan <span class="highlight">Selamat Menunaikan Ibadah Puasa 1446 H</span>.
            Semoga bulan yang penuh berkah ini membawa kedamaian, keberkahan, dan ampunan bagi kita semua.
        </p>
        <p>
            Mari kita tingkatkan ibadah, perbanyak doa, dan pererat tali silaturahmi.
            <span class="highlight">Mohon maaf lahir dan batin.</span>
        </p>
        
        <span class="sender-name">
            Zainal Family
        </span>

        <p class="salam">
            Semoga Allah SWT menerima amal ibadah kita. Aamiin.
        </p>
    </div>
    
</body>
</html>
