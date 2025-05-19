# openscore
OpenScore - Бесплатные партитуры киномузыки
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Film Music Scores - Бесплатные партитуры киномузыки</title>
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Film Music Scores</h1>
            <p>Бесплатная библиотека партитур киномузыки</p>
            <nav>
                <ul>
                    <li><a href="index.html">Главная</a></li>
                    <li><a href="upload.html">Загрузить</a></li>
                    <li><a href="donate.html">Поддержать</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section class="search">
            <h2>Поиск партитур</h2>
            <form action="/search" method="get">
                <input type="text" name="query" placeholder="Название фильма, композитора или произведения">
                <button type="submit">Искать</button>
            </form>
        </section>

        <section class="featured">
            <h2>Популярные партитуры</h2>
            <div class="scores-grid">
                <div class="score-card">
                    <img src="https://via.placeholder.com/150" alt="Обложка">
                    <h3>Интерстеллар</h3>
                    <p>Ханс Циммер</p>
                    <a href="#" class="btn">Скачать</a>
                </div>
                <div class="score-card">
                    <img src="https://via.placeholder.com/150" alt="Обложка">
                    <h3>Властелин Колец</h3>
                    <p>Говард Шор</p>
                    <a href="#" class="btn">Скачать</a>
                </div>
                <div class="score-card">
                    <img src="https://via.placeholder.com/150" alt="Обложка">
                    <h3>Гарри Поттер</h3>
                    <p>Джон Уильямс</p>
                    <a href="#" class="btn">Скачать</a>
                </div>
            </div>
        </section>

        <section class="about">
            <h2>О проекте</h2>
            <p>Film Music Scores - это некоммерческий проект, созданный для сохранения и распространения партитур киномузыки. Наш сайт работает по принципу общественного достояния, аналогично IMSLP.org, но специализируется исключительно на музыке из фильмов.</p>
            <p>Все партитуры доступны бесплатно для образовательных и исследовательских целей.</p>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2023 Film Music Scores. Все права защищены.</p>
            <p>Этот сайт использует файлы cookie для улучшения работы.</p>
        </div>
    </footer>

    <script src="scripts/main.js"></script>
</body>
</html>