//задача1
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Млинці з сиром</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #000000;
        }
        .recipe-card {
            max-width: 750px;
            margin: 40px auto;
            padding: 30px;
            border: 2px solid #b3c6ff;
            text-align: center;
            background-color: #ffffff;
        }
        h1 {
            color: #ff0000;
            font-size: 2.2em;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .subtitle {
            font-style: italic;
            font-size: 1.5em;
            margin-top: 10px;
            margin-bottom: 25px;
            font-weight: bold;
        }
        .ingredients-list {
            list-style-type: none;
            padding: 0;
            margin: 0 auto 30px auto;
            max-width: 600px;
            font-size: 1.15em;
        }
        .ingredients-list li {
            margin-bottom: 6px;
        }
        .bold-text {
            font-weight: bold;
        }
        .strikethrough {
            text-decoration: line-through;
            color: #555;
        }
        .highlight {
            background-color: #ffff00;
            padding: 0 4px;
        }
        .divider {
            height: 4px;
            background-color: #008000;
            margin: 30px auto 20px auto;
            max-width: 650px;
        }
        .footer-note {
            font-style: italic;
            font-size: 1.1em;
            max-width: 600px;
            margin: 0 auto;
            color: #000000;
        }
    </style>
</head>
<body>

<div class="recipe-card">
    <h1>Млинці з сиром</h1>
    <div class="subtitle">Продукти:</div>

    <ul class="ingredients-list">
        <li><span class="bold-text">Борошно</span> – 1 склянка</li>
        <li><span class="bold-text">Сметану домашня</span> – 3 ст.л. (для тіста) <u>плюс сметана для подачі на стіл</u></li>
        <li><span class="bold-text">Вода кип'ячена тепла (H<sub>2</sub>O) або BONAQUA<sup>®</sup></span> – 2 склянки</li>
        <li><span class="bold-text">Олія</span> – <span class="strikethrough">1 ст.л.</span> 2 ст.л. (для тіста) <u>плюс масло для змазування сковороди</u></li>
        <li><span class="bold-text">Яйця</span> – 2 шт.</li>
        <li><span class="bold-text">Сир домашній</span> – <span class="strikethrough">250</span> 300 грам</li>
        <li><span class="bold-text">Масло вершкове</span> – 50 грам</li>
        <li><span class="bold-text">Сіль</span> – щіпка</li>
        <li><span class="bold-text">Цукор</span> – за смаком <span class="highlight">(можна не давати)</span></li>
    </ul>

    <div class="divider"></div>

    <p class="footer-note">
        Успіх смачних млинців залежить від того,<br>
        які використані інгредієнти і що вибрано за основу!
    </p>
</div>

</body>
</html>

/задача2
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Резюме</title>
</head>
<body>

<header>
    <img src="assets/logo.png" alt="Логотип" width="100" height="100">
</header>

<main>

    <h1>Інформація</h1>

    <p>
        Резюме – документ, в якому подаються короткі відомості про навчання,
        трудову діяльність та професійні досягнення особи, яка його складає.
    </p>

    <p>
        Мета резюме – надати працедавцю короткий виклад своєї професійної діяльності
        та зацікавити його своєю кандидатурою.
    </p>

    <p>
        Основна вимога до такого документа – вичерпність потрібних відомостей
        і лаконічність викладу.
    </p>

    <h2>Структура резюме</h2>

    <p>В резюме обов’язково мають бути наступні розділи:</p>

    <ol>
        <li>Прізвище та ім’я особи, яка складає резюме.</li>
        <li>Контактні дані.</li>
        <li>Мета працевлаштування або короткий текст про кандидата.</li>
        <li>Досвід роботи.</li>
        <li>Освіта.</li>
        <li>Ключові компетенції (навички).</li>
    </ol>

    <a href="about.html" target="_blank">
        <img src="assets/resume.jpg" alt="Резюме" width="180">
    </a>

    <p>
        Додатково, в резюме можна включити розділ про сертифікати, ліцензії,
        нагороди, додаткову освіту, волонтерський досвід тощо.
    </p>

    <h2>Оформлення резюме</h2>

    <ul>
        <li>Обсяг резюме не більше двох сторінок.</li>
        <li>Чітка структура документа.</li>
        <li>Використання списків.</li>
        <li>Бажано додавати фото.</li>
        <li>Рекомендований формат PDF.</li>
    </ul>

    <h3>Опис професійної діяльності</h3>

    <p>
        В резюме використовують професійну термінологію та інформаційний стиль.
        Потрібно уникати канцеляризмів та незрозумілих абревіатур.
    </p>

</main>

<footer>
    <p>&copy; 2026</p>
    <p>Мала Поліна Віталіївна, група 145</p>
</footer>

</body>
</html>

/задача4
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Формули</title>
</head>
<body>

<h1>Хімічні та математичні формули</h1>

<ol>
    <li>
        H<sub>2</sub>O
        <em> - Вода</em>
    </li>

    <li>
        H<sub>2</sub>SO<sub>4</sub>
        <em> - Сірчана кислота</em>
    </li>

    <li>
        C<sub>6</sub>H<sub>12</sub>O<sub>6</sub>
        <em> - Глюкоза</em>
    </li>

    <li>
        CaCO<sub>3</sub>
        <em> - Карбонат кальцію</em>
    </li>

    <li>
        CH<sub>4</sub> + 2O<sub>2</sub> →
        CO<sub>2</sub> + 2H<sub>2</sub>O
        <em> - Реакція горіння метану</em>
    </li>

    <li>
        ax<sup>2</sup> + bx + c = 0
        <em> - Квадратне рівняння</em>
    </li>

    <li>
        6,022 × 10<sup>23</sup> моль<sup>-1</sup>
        <em> - Число Авогадро</em>
    </li>
</ol>

</body>
</html>
 
/задача 5
<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>Останні новини</title>
</head>

<body>

<header>
    <h1>Останні новини</h1>

    <nav>
        <a href="#">Головна</a> |
        <a href="#">Новини</a> |
        <a href="#">Контакти</a>
    </nav>

    <hr>
</header>

<main>

<section>

<article>
    <h2>Відкрито новий кампус університету</h2>

    <time datetime="2026-09-01">
        1 вересня 2026
    </time>

    <p>
        Університет відкрив сучасний кампус для студентів.
        Нові лабораторії та навчальні аудиторії обладнані
        сучасною технікою.
    </p>

    <p><strong>Автор: Ірина Коваль</strong></p>
</article>

<hr>

<article>
    <h2>Стартував конкурс студентських проєктів</h2>

    <time datetime="2026-09-05">
        5 вересня 2026
    </time>

    <p>
        Студенти можуть подавати власні проєкти на конкурс.
        Переможці отримають гранти та можливість реалізації своїх ідей.
    </p>

    <p><strong>Автор: Олег Петренко</strong></p>
</article>

<hr>

<article>
    <h2>Результати літньої практики</h2>

    <time datetime="2026-09-10">
        10 вересня 2026
    </time>

    <p>
        Більшість студентів успішно завершили практику
        в ІТ-компаніях та державних установах.
    </p>

    <p><strong>Автор: Марія Шевчук</strong></p>
</article>

</section>

<aside>
    <h3>Популярне</h3>

    <ul>
        <li><a href="#">Новина 1</a></li>
        <li><a href="#">Новина 2</a></li>
        <li><a href="#">Новина 3</a></li>
        <li><a href="#">Новина 4</a></li>
    </ul>
</aside>

</main>

<footer>

<hr>

<p>&copy; 2026 Останні новини</p>

<p>
Мала Поліна Віталіївна,
145,
<a href="mailto:polina@example.com">
polina@example.com
</a>
</p>

</footer>

</body>
</html>
