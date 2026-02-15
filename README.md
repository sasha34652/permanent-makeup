<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Перманентный макияж</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root {
    --main: #b47b7b;
    --light: #faf7f6;
    --dark: #333;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background: var(--light);
    color: var(--dark);
    line-height: 1.6;
}

/* ===== HEADER ===== */
header {
    background: linear-gradient(135deg, #cfa5a5, #e6cfcf);
    color: #fff;
    padding: 70px 20px;
    text-align: center;
}

header h1 {
    font-size: 42px;
    margin-bottom: 15px;
}

header p {
    font-size: 18px;
}

/* ===== SECTIONS ===== */
section {
    padding: 60px 20px;
    max-width: 1100px;
    margin: auto;
}

h2 {
    text-align: center;
    font-size: 34px;
    margin-bottom: 35px;
}

.center {
    max-width: 800px;
    margin: auto;
    text-align: center;
    font-size: 16px;
}

/* ===== CARDS ===== */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 25px;
}

.card {
    background: #fff;
    padding: 25px;
    border-radius: 14px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.06);
}

.card h3 {
    color: var(--main);
    margin-bottom: 15px;
    font-size: 22px;
}

.card p, .card li {
    font-size: 15px;
}

/* ===== CTA ===== */
.cta {
    background: var(--main);
    color: #fff;
    text-align: center;
    padding: 70px 20px;
}

.cta h2 {
    margin-bottom: 20px;
}

.cta a {
    display: inline-block;
    background: #fff;
    color: var(--main);
    padding: 15px 35px;
    border-radius: 30px;
    font-weight: bold;
    text-decoration: none;
    font-size: 16px;
}

/* ===== FOOTER ===== */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 25px;
    font-size: 14px;
}

/* =========================
   📱 MOBILE ADAPTATION
   ========================= */
@media (max-width: 768px) {

    header {
        padding: 55px 15px;
    }

    header h1 {
        font-size: 32px;
    }

    header p {
        font-size: 16px;
    }

    section {
        padding: 45px 15px;
    }

    h2 {
        font-size: 26px;
        margin-bottom: 25px;
    }

    .center {
        font-size: 15px;
    }

    .card {
        padding: 20px;
    }

    .card h3 {
        font-size: 20px;
    }

    .cta {
        padding: 60px 15px;
    }

    .cta a {
        width: 100%;
        max-width: 320px;
    }
}

/* 📱 EXTRA SMALL PHONES */
@media (max-width: 420px) {

    header h1 {
        font-size: 26px;
    }

    h2 {
        font-size: 22px;
    }

    .card p, .card li {
        font-size: 14px;
    }
}
</style>
</head>

<body>

<header>
    <h1>Перманентный макияж</h1>
    <p>Красота без лишних усилий каждый день</p>
</header>

<section>
    <h2>Что такое перманентный макияж</h2>
    <p class="center">
        Перманентный макияж — это косметологическая процедура, при которой
        пигмент вводится в верхние слои кожи. Результат сохраняется от
        <strong>1 до 3 лет</strong>.
    </p>
</section>

<section>
    <h2>Наши услуги</h2>
    <div class="grid">
        <div class="card">
            <h3>Брови</h3>
            <p>
                Пудровое напыление<br>
                Волосковая техника<br>
                Комбинированная техника
            </p>
        </div>

        <div class="card">
            <h3>Губы</h3>
            <p>
                Акварельная техника<br>
                Полное заполнение<br>
                Коррекция асимметрии
            </p>
        </div>

        <div class="card">
            <h3>Веки</h3>
            <p>
                Межресничное заполнение<br>
                Стрелки<br>
                Мягкая растушёвка
            </p>
        </div>
    </div>
</section>

<section>
    <h2>Почему выбирают нас</h2>
    <div class="grid">
        <div class="card">
            <ul>
                <li>Сертифицированный мастер</li>
                <li>Безопасные пигменты</li>
                <li>Стерильность</li>
                <li>Коррекция включена</li>
            </ul>
        </div>
    </div>
</section>

<section class="cta">
    <h2>Запишитесь на процедуру</h2>
    <p>
        📞 +7 (___) ___-__-__<br>
        📍 Ваш город<br>
        📅 По записи
    </p>
    <a href="#">Записаться</a>
</section>

<footer>
    © 2026 Перманентный макияж
</footer>

</body>
</html>
