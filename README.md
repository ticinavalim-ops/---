# ---
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тепло Сід — Виробництво подушок</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #c62828;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #b71c1c;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #ff5252;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .product {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            width: 250px;
            padding: 15px;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        button {
            background-color: #c62828;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff5252;
        }
    </style>
</head>
<body>
    <header>
        <h1>Тепло Сід</h1>
        <p>Компанія з виробництва подушок</p>
    </header>

    <nav>
        <a href="#home">Головна</a>
        <a href="#order">Онлайн замовлення</a>
        <a href="#workers">Кабінет працівників</a>
        <a href="#shareholders">Кабінет акціонерів</a>
        <a href="#director">Генеральний директор</a>
    </nav>

    <section id="home">
        <h2>Про компанію</h2>
        <p>Компанія <b>Тепло Сід</b> створена учнями Волочиського промислово-аграрного професійного ліцею. Ми спеціалізуємося на виготовленні подушок для дому, підвалів та інших потреб. Наша місія — дарувати комфорт і тепло кожному!</p>
        <div class="products">
            <div class="product">
                <img src="/mnt/data/chern2-600x600.png" alt="Чорна подушка">
                <h3>Подушка чорна</h3>
                <p>Міцна, стильна та зручна.</p>
                <button>Замовити</button>
            </div>
            <div class="product">
                <img src="/mnt/data/images.jfif" alt="Сіра подушка">
                <h3>Подушка сіра</h3>
                <p>Комфортна класика для будь-якого простору.</p>
                <button>Замовити</button>
            </div>
            <div class="product">
                <img src="/mnt/data/podushki-page-2.png" alt="Рожеві та червоні подушки">
                <h3>Подушки кольорові</h3>
                <p>Яскраві кольори для вашого настрою!</p>
                <button>Замовити</button>
            </div>
        </div>
    </section>

    <section id="order">
        <h2>Онлайн замовлення</h2>
        <p>Зробіть замовлення просто зараз, заповнивши коротку форму.</p>
        <form>
            <input type="text" placeholder="Ваше ім’я" required><br><br>
            <input type="tel" placeholder="Номер телефону" required><br><br>
            <input type="text" placeholder="Адреса доставки" required><br><br>
            <button type="submit">Відправити замовлення</button>
        </form>
    </section>

    <section id="workers">
        <h2>Кабінет працівників</h2>
        <p>Вхід до внутрішньої системи для працівників компанії Тепло Сід.</p>
        <button>Увійти</button>
    </section>

    <section id="shareholders">
        <h2>Кабінет акціонерів</h2>
        <p>Доступ до звітності, фінансів та рішень компанії для акціонерів.</p>
        <button>Увійти</button>
    </section>

    <section id="director">
        <h2>Генеральний директор</h2>
        <p><b>Риньгач Вадим Вікторович</b> — генеральний директор компанії «Тепло Сід». Завдяки його керівництву компанія стабільно розвивається та створює якісну продукцію.</p>
    </section>

    <footer>
        <p>© 2025 Тепло Сід. Усі права захищено. <br> Контакти: Instagram — <a href="https://www.instagram.com/teplo_sid" style="color: #ff5252;">@teplo_sid</a></p>
    </footer>
</body>
</html>
