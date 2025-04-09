<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>БетонСтрой — Строительная компания</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>БетонСтрой</h1>
        <nav>
            <ul>
                <li><a href="#about">О нас</a></li>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#projects">Проекты</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>О компании</h2>
            <p>Мы специализируемся на строительстве жилых и коммерческих объектов под ключ.</p>
        </section>

        <section id="services">
            <h2>Наши услуги</h2>
            <ul>
                <li>Капитальное строительство</li>
                <li>Ремонт и отделка</li>
                <li>Фундаменты и кровля</li>
                <li>Проектирование</li>
            </ul>
        </section>

        <section id="projects">
            <h2>Примеры работ</h2>
            <p>Скоро здесь будет фотогалерея наших проектов.</p>
        </section>

        <section id="contact">
            <h2>Связаться с нами</h2>
            <form>
                <label for="name">Имя:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Сообщение:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Отправить</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 БетонСтрой. Все права защищены.</p>
    </footer>
</body>
</html>
