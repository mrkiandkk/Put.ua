<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <title>Untitled</title>
    

  </head>
    
  <body>
  <!DOCTYPE html>

<html lang="uk">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>AI-PULSE | Мега-Каталог ШІ</title>

    

    <script src="https://unpkg.com/lucide@latest"></script>

    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&display=swap" rel="stylesheet">

    <style>

        :root { --primary: #00f2ff; --bg: #030509; --card: rgba(255, 255, 255, 0.03); --accent: #7000ff; }

        body { font-family: 'Plus Jakarta Sans', sans-serif; background: var(--bg); color: white; margin: 0; scroll-behavior: smooth; }

        .container { max-width: 1200px; margin: auto; padding: 20px; }

        

        header { text-align: center; margin-bottom: 30px; padding: 40px 0; }

        h1 { font-size: clamp(2.5rem, 8vw, 4rem); font-weight: 800; margin: 0; background: linear-gradient(to right, #fff, var(--primary)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }

        /* МЕНЮ ФІЛЬТРІВ */

        .filter-container { position: sticky; top: 0; background: var(--bg); z-index: 100; padding: 15px 0; margin-bottom: 30px; border-bottom: 1px solid rgba(255,255,255,0.05); }

        .filter-menu { display: flex; justify-content: center; gap: 8px; flex-wrap: wrap; }

        .filter-btn { 

            background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); 

            color: #94a3b8; padding: 8px 16px; border-radius: 20px; cursor: pointer; font-size: 0.85rem; font-weight: 600; transition: 0.3s;

        }

        .filter-btn.active, .filter-btn:hover { background: var(--primary); color: #000; border-color: var(--primary); }

        /* РЕКЛАМА */

        .ad-services { margin: 20px 0 40px; padding: 25px; background: rgba(255,255,255,0.02); border-radius: 24px; border: 1px dashed var(--primary); }

        .ad-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; }

        .ad-card { background: #000; border: 1px solid rgba(255,255,255,0.05); padding: 15px; border-radius: 15px; text-align: center; }

        .price { font-size: 1.5rem; font-weight: 800; color: var(--primary); margin: 5px 0; }

        .contact-btn { text-decoration: none; background: #fff; color: #000; padding: 8px 15px; border-radius: 10px; font-weight: 800; display: inline-block; font-size: 0.8rem; }

        /* СІТКА КАРТОК */

        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 15px; }

        .card { 

            background: var(--card); border: 1px solid rgba(255,255,255,0.05); 

            padding: 20px; border-radius: 20px; transition: 0.3s; 

            display: flex; flex-direction: column; justify-content: space-between;

        }

        .card.hidden { display: none; }

        .card:hover { transform: translateY(-5px); border-color: var(--primary); background: rgba(255,255,255,0.06); }

        

        .card h3 { margin: 0 0 8px 0; font-size: 1.2rem; color: #fff; }

        .card p { color: #94a3b8; font-size: 0.85rem; line-height: 1.4; margin-bottom: 15px; flex-grow: 1; }

        .btn { text-decoration: none; background: rgba(0, 242, 255, 0.05); color: var(--primary); padding: 10px; border-radius: 10px; text-align: center; font-weight: 700; border: 1px solid var(--primary); font-size: 0.85rem; transition: 0.3s; }

        .btn:hover { background: var(--primary); color: #000; }

        footer { text-align: center; padding: 40px 0; opacity: 0.4; font-size: 0.8rem; }

    </style>

</head>

<body>

<div class="container">

    <header>

        <h1>AI-PULSE</h1>

        <p>Найбільший каталог нейромереж для твоїх цілей</p>

    </header>

    <div class="filter-container">

        <div class="filter-menu">

            <button class="filter-btn active" onclick="filterSelection('all')">Усі ШІ</button>

            <button class="filter-btn" onclick="filterSelection('text')">✍️ Текст</button>

            <button class="filter-btn" onclick="filterSelection('photo')">🖼️ Фото</button>

            <button class="filter-btn" onclick="filterSelection('video')">🎬 Відео</button>

            <button class="filter-btn" onclick="filterSelection('music')">🎵 Музика</button>

            <button class="filter-btn" onclick="filterSelection('study')">📚 Навчання</button>

            <button class="filter-btn" onclick="filterSelection('code')">💻 Код</button>

        </div>

    </div>

    <!-- ДАЛІ ЙДЕ ВСЯ СІТКА КАРТОК (ChatGPT, Claude, Midjourney, Runway, Suno тощо) -->

<script>

    function filterSelection(category) {

        const cards = document.querySelectorAll('.card');

        const btns = document.querySelectorAll('.filter-btn');

        btns.forEach(btn => btn.classList.remove('active'));

        event.target.classList.add('active');

        cards.forEach(card => {

            if (category === 'all' || card.classList.contains(category)) {

                card.classList.remove('hidden');

            } else {

                card.classList.add('hidden');

            }

        });

    }

    lucide.createIcons();

</script>

</body>

</html>
