<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Чернявский Роман Евгеньевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №2. «HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2022 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Среда разработки html (HyperText Markup Language)</b> — это язык разметки, который используется для создания веб-страниц. HTML определяет структуру содержимого веб-страницы, такие как заголовки, параграфы, списки, ссылки и изображения. HTML состоит из набора тегов, которые определяют различные элементы страницы и их отображение в браузере.</p>
<p><b>JavaScript</b> — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили. Является реализацией спецификации ECMAScript. JavaScript обычно используется как встраиваемый язык для программного доступа к объектам приложений.</p>
<p><b>CSS</b> — формальный язык декодирования и описания внешнего вида документа, написанного с использованием языка разметки. Также может применяться к любым XML-документам, например, к SVG или XUL.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>Необходимо использовать весь необходимый функционал для выполнения соответствующих заданий из лабораторной работы.</p>

<p></p>



<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовался материалом из интернета и того, что мы проходили на лекции</p>

<h2 align = "center">Файл "Лабораторная работа №2.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 1 часть"</title>
        <link rel="stylesheet" type="text/css" href="style.css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }

        ol {
            list-style-type:decimal;
        }
        
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <header>Задание 1</header>
        <p style="font-family: 'calibri'; font-size: 16px">Это заголовок</p>
        <p style="font-family: 'calibri'; font-size: 13px">Это заголовок</p>
        <p style="font-family: 'Times New Roman'; font-size: 13,5px; font-weight: bold;">Это заголовок</p>
        <p style="font-family: 'calibri'; font-size: 13,5px; font-style: italic;">Это заголовок</p>
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;">Это <span style="font-family: 'Times New Roman'; font-size: 13,5px; font-weight: bold;">абзац.</span></p>
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;">Это ещё <span style="font-family: 'Times New Roman'; font-size: 13,5px; font-style:italic;">абзац.</span></p>
        <h1 style="font-family: 'calibri'; font-size: 16px; font-style: italic; font-weight: lighter;">Это заголовок h1</h1>
        <header>Задание 2</header>
        <p style="font-family: 'calibri'; font-size: 16px;">Что такое CMS</p>
        
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;"><span style="font-weight: bold;">CMS</span> - «система управления контентом» <span style="font-weight: bold;">(движок)</span> – написанная PHP-программистами основа для сайта, с помощью которой вы сможете управлять сайтом (добавлять контент, менять пункты меню и т.п.) не зная HTML и CSS.</p>
        
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;">Однако, для того чтобы сделать сайт с помощью <span style="font-weight: bold;">CMS</span> <span style="font-style: italic;">потребуются услуги</span> и программиста, и дизайнера, и верстальщика. И капиталовложения.</p>
        
        <p style="font-family: 'calibri'; font-size: 16px;">Какие бывают cms</p>
        
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;">Бывают различные системы управления контентом: для интернет-магазинов, для блогов, для форумов и т.д.</p>
        
        <p style="font-family: 'calibri'; font-size: 16px;">Примеры cms</p>
        
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;"><span style="font-style: italic;">Примеры популярных CMS</span>: Joomla, WordPress (для блогов), PhpBB (для форумов).</p>
        
        <p style="font-family: 'Times New Roman'; font-size: 13,5px;"><span style="font-weight: bold;">CMS-ки</span> бывают <span style="font-style: italic;">платные</span> и <span style="font-style: italic;">бесплатные.</span></p>
        <header>Задание 3</header>
        <p style="font-family: 'calibri'; font-size: 19px; font-weight: lighter;">Списки</p>
        <h2 style="font-family: 'calibri'; font-size: 17px; font-weight: lighter;">Список цветов:</h2>
        <ul style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
            <li>Красный</li>
            <li>Желтый</li>
            <li>Зеленый</li>
            <li>Синий</li>
        </ul>
        <h2 style="font-family: 'calibri'; font-size: 17px; font-weight: lighter;">Список студентов:</h2>
        <ol style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
            <li>Иванов</li>
            <li>Петров</li>
            <li>Сидоров</li>
            <li>Николаев</li>
        </ol>
        <h2 style="font-family: 'calibri'; font-size: 17px; font-weight: lighter;">Список студентов:</h2>
        <ol style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
            <li>Иванов
                <ul style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
                    <li>Возраст - 23 года</li>
                    <li>Курс - 3</li>
                </ul>
            </li>
            <li>Петров
                <ul style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
                    <li>Возраст - 19 лет</li>
                    <li>Курс - 2</li>
                </ul>
            </li>
            <li>Сидоров
                <ul style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
                    <li>Возраст - 18 лет</li>
                    <li>Курс - 1</li>
                </ul>
            </li>
        </ol>
        <header>Задание 4</header>
        <h3 style="font-family: 'calibri'; font-size: 18px; font-weight: bold;">Что нужно знать, чтобы делать сайты</h3>
        <ol style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
            <li style="font-weight: bold;">HTML</li>
            <li style="font-style: italic;">CSS</li>
            <li>PHP</li>
            <li>SQL</li>
            <li>JavaScript</li>
            <li>jQuery</li>
            <li>Flash</li>
            <li>SEO</li>
        </ol>
        <h4 style="font-family: 'calibri'; font-size: 13px; font-weight: lighter;">PHP и JavaScript</h4>
        <p style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">Языки программирования PHP и JavaScript позволяют сделать сайт динамичным, то есть реагирующим на действия пользователя. Например, можно сделать красивую выпадающую менюшку или слайдер.</p>
        <h4 style="font-family: 'calibri'; font-size: 13px; font-weight: lighter;">Виды скриптов</h4>
        <p style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">Для этого пишутся скрипты (англ. script - «сценарий») - программы, позволяющие реагировать на действия пользователя. Скрипты бывают двух видов:</p>
        <ul style="font-family: 'Times New Roman', Times, serif; font-size: 13,5px;">
            <li>те, которые выполняются на сервере, а результат их выполнения приходит в браузер к пользователю уже в готовом виде. Это скрипты, написанные на языке PHP. На нем пишутся CMS-ки – системы управления контентом.</li>
            <li>те, которые выполняются прямо в браузере пользователя. Это скрипты, написанные на языке JavaScript. Они чаще всего используются для, того чтобы сделать страницу более удобной и красивой.</li>
        </ul>
        <header>Задание 5</header>
        <a href="Задание 7.html">Страница 2</a>
        <a href="Задание 11.html">Страница 3</a>
        <header>Задание 6</header>
        <div class="image-container">
            <img src="мопс.jpg" alt="мопс" width="400" height="400">
        </div>
    </body>
</html>

```

<h2 align = "center">Файл "Задание 7-10.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 2 часть"</title>
        <link rel="stylesheet" type="text/css" href="style2.css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }

        ol {
            list-style-type:decimal;
        }

        table {
            font-family: Arial, sans-serif;
            border-collapse: collapse;
            width: 100%;
        }

        th, td {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }

        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        
        </style>
    </head>

    <body style="background-color:burlywood;">
        <header>Что такое HTML?</header>
        <p>HTML (HyperText Markup Language) - это основной язык разметки веб-страниц. Он используется для структурирования содержимого веб-страниц.</p>
        <h3 class="center">Где используется html?</h3>
        <p>HTML (HyperText Markup Language) используется для создания веб-страниц. Он определяет структуру и содержимое веб-страницы, включая текст, изображения, видео, ссылки и другие элементы. HTML-страницы могут быть отображены в веб-браузерах, таких как Google Chrome, Mozilla Firefox, Safari и Internet Explorer.</p>
        <h3 class="center">Актуален ли он в наши дни?</h3>
        <p>Актуален, как никогда!</p>
        <h2 class="center">Что можно делать с помощью HTML?</h2>
        <h5>Можно создавать страницы с:</h5>
        <ul>
            <li>абзацами</li>
            <li>списками</li>
            <li>изображениями</li>
        </ul>
        <h5>Добавлять:</h5>
        <ol>
            <li>видео</li>
            <li>музыку</li>
            <li>геолокацию</li>
        </ol>
        <img src="html.jpg" alt="html">

        <a href="Лабораторная работа 2.html">Вернуться на страницу 1</a>
        <a href="Задание 11.html">Посмотреть на карты</a>

        <video width="" height="240" controls>
            <source src="HTML ЗА 5 МИНУТ _ БАЗА HTML.mp4" type="video/mp4">
        </video>

        <form action="/submit_form.php" method="post">
            <div>
              <label for="name">Имя:</label>
              <input type="text" id="name" name="name">
            </div>
            <div>
              <label for="email">Email:</label>
              <input type="email" id="email" name="email">
            </div>
            <div>
              <label for="message">Сообщение:</label>
              <textarea id="message" name="message"></textarea>
            </div>
            <div>
              <input type="submit" value="Отправить">
            </div>
        </form>

        <table>
        <tr>
            <th>Название</th>
            <th>Цена</th>
            <th>Описание</th>
        </tr>
        <tr>
            <td>Молоко</td>
            <td>100</td>
            <td>Поставщик - "Поронайский Молоко Завод"</td>
        </tr>
        <tr>
            <td>Йогурт</td>
            <td>200</td>
            <td>Поставщик - "Поронайский Молоко Завод"</td>
        </tr>
        <tr>
            <td>Хлеб</td>
            <td>50</td>
            <td>Поставщик - "Пекарня им. Куцова"</td>
        </tr>
        </table>
    </body>
</html>

```

<h2 align = "center">Файл "Задание 11-18.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css" href="style2.css">
        <link rel="stylesheet" href="https://unpkg.com/leaflet@1.8.0/dist/leaflet.css" />
        <script src="https://unpkg.com/leaflet@1.8.0/dist/leaflet.js"></script>
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }

        ol {
            list-style-type:decimal;
        }

        </style>
    </head>

    <body style="background-color:burlywood;">
        <div id="map"></div>
        <nav>
            <ul>
                <li><a href="Лабораторная работа 2.html">Первая часть</a></li>
                <li><a href="Задание 7.html">Вторая часть</a></li>
                <li><a href="#music">Аудио</a></li>
                <li><a href="#buy">Заказать товар</a></li>
                <li><a href="#video">Обзор</a></li>
            </ul>
        </nav>
        <script>
        var map = L.map('map').setView([51.505, -0.09], 13);

        L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
        }).addTo(map);

        var marker = L.marker([51.505, -0.09]).addTo(map);

        marker.bindPopup('Это Вестминстер, Лондон').openPopup();
        </script>

        <audio controls id="music">
            <source src="95 bpm.wav" type="audio/mpeg">
            Ваш браузер не поддерживает аудио-тег.
        </audio>

        <form id="buy">
            <label for="product">Сувенир:</label>
            <select id="product">
              <option value="apple">Значок</option>
              <option value="orange">Магнитик</option>
              <option value="banana">Флаг</option>
            </select>
        
            <label for="quantity">Количество:</label>
            <input type="number" id="quantity" min="1" value="1">
        
            <input type="submit" value="Заказать">
        </form>

        <iframe src="https://www.youtube.com/watch?v=N_1SLOLF0fI" width="100%" height="300" id="video"></iframe>


        <form>
            <label for="name">Имя:</label>
            <input type="text" id="name">
          
            <label for="email">Email:</label>
            <input type="email" id="email">
          
            <input type="submit" value="Отправить">
        </form>

        <script>
            const form = document.querySelector('form');

            form.addEventListener('submit', (event) => {
                event.preventDefault();

                const name = document.querySelector('#name').value;
                const email = document.querySelector('#email').value;

                if (name === '') {
                alert('Пожалуйста, введите ваше имя.');
                return;
            }

            if (!validateEmail(email)) {
                alert('Пожалуйста, введите корректный email.');
                return;
            }

            console.log(`Имя: ${name}`);
            console.log(`Email: ${email}`);
        });


        function validateEmail(email) {
            const re = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
            return re.test(String(email).toLowerCase());
        }
        </script>

        
    </body>
</html>

```

<h2 align = "center">Файл "Бургер+canvas.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css" href="style2.css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }

        .burger-menu {
            position: fixed;
            top: 20px;
            right: 20px;
            width: 50px;
            height: 50px;
            z-index: 999;
            cursor: pointer;
            display: none;
        }

        @media screen and (max-width: 768px) {
            .burger-menu {
                display: block;
            }
        }

        .burger-line {
            width: 100%;
            height: 5px;
            background-color: #000;
            margin: 5px 0;
            transition: all 0.3s ease-in-out;
        }

        .burger-menu.active .burger-line:nth-child(1) {
            transform: rotate(-45deg) translate(-9px, 6px);
        }

        .burger-menu.active .burger-line:nth-child(2) {
            opacity: 0;
        }

        .burger-menu.active .burger-line:nth-child(3) {
            transform: rotate(45deg) translate(-8px, -6px);
        }        
        
        </style>
    </head>

    <body style="background-color:burlywood;">
        <button class="burger-menu">
            <span class="burger-line">1</span>
            <span class="burger-line">2</span>
            <span class="burger-line">3</span>
          </button>
        
          <script>
            const burgerMenu = document.querySelector('.burger-menu');
        
            burgerMenu.addEventListener('click', () => {
              burgerMenu.classList.toggle('active');
            });
        </script>

        <canvas id="my-canvas" width="500" height="500"></canvas>

        <script>
            const canvas = document.getElementById('my-canvas');
            const ctx = canvas.getContext('2d');

            // Рисуем прямоугольник
            ctx.fillStyle = 'red';
            ctx.fillRect(50, 50, 100, 100);

            // Рисуем круг
            ctx.beginPath();
            ctx.arc(250, 250, 50, 0, 2 * Math.PI);
            ctx.fillStyle = 'blue';
            ctx.fill();

            // Рисуем линию
            ctx.beginPath();
            ctx.moveTo(100, 100);
            ctx.lineTo(400, 400);
            ctx.strokeStyle = 'green';
            ctx.lineWidth = 5;
            ctx.stroke();
        </script>
        
    </body>
</html>
```

<h2 align = "center">Файл "галерея.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css" href="style2.css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }

        ol {
            list-style-type:decimal;
        }
        
        </style>
    </head>

    <body style="background-color:burlywood;">
        <div class="gallery">
            <figure>
              <a href="мопс.jpg">
                <img src="мопс.jpg" alt="Собакен">
              </a>
            </figure>
            <figure>
              <a href="html.jpg">
                <img src="html.jpg" alt="Изображение 2">
              </a>
            </figure>
            <figure>
                <a href="3.jpg">
                  <img src="3.jpg" alt="Изображение 3">
                </a>
              </figure>
        </div>
    </body>
</html>
```

<h2 align = "center">Файл "соц. сети.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css" href="style2.css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        } 
        
        .social-icons {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .social-icons li {
            display: inline;
            margin: 0 10px;
        }
        .social-icons a {
            text-decoration: none;
            color: #000;
        }
        </style>
    </head>

    <body style="background-color:burlywood;">
        <ul class="social-icons">
            <li><a href="https://vk.com/minxr_fvce"><img src="vk.png" alt="vk" width="200"></a></li>
            <li><a href="https://t.me/minxrfvce"><img src="tg.png" alt="telegram" width="100"></a></li>
        </ul>
    </body>
</html>
```

<h2 align = "center">Файл "Регистрация пользователей.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css" href="style2.css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }   
        
        </style>
    </head>

    <body style="background-color:burlywood;">
        <form>
            <label for="username">Имя пользователя:</label>
            <input type="text" id="username">
          
            <label for="email">Email:</label>
            <input type="email" id="email">
          
            <label for="password">Пароль:</label>
            <input type="password" id="password">
          
            <label for="confirm-password">Подтвердите пароль:</label>
            <input type="password" id="confirm-password">
          
            <input type="submit" value="Зарегистрироваться">
        </form>

        <script>
            const form = document.querySelector('form');

            form.addEventListener('submit', (event) => {
                event.preventDefault();

                const username = document.querySelector('#username').value;
                const email = document.querySelector('#email').value;
                const password = document.querySelector('#password').value;
                const confirmPassword = document.querySelector('#confirm-password').value;

                if (!username || !email || !password || !confirmPassword) {
                alert('Пожалуйста, заполните все поля.');
                return;
            }

            if (!validateEmail(email)) {
                alert('Пожалуйста, введите корректный email.');
                return;
            }

            if (password !== confirmPassword) {
                alert('Пароли не совпадают.');
                return;
            }

            if (password.length < 8) {
                alert('Пароль должен быть не менее 8 символов.');
                return;
            }

            const strongPasswordRegex = /^(?=.*[a-z])(?=.*[A-Z])(?=.*[0-9])(?=.*[!@#\$%\^&\*])(?=.{8,})/;
            if (!strongPasswordRegex.test(password)) {
                alert('Пароль должен содержать строчную букву, прописную букву, цифру и специальный символ.');
                return;
            }

            console.log(`Имя пользователя: ${username}`);
            console.log(`Email: ${email}`);
            console.log(`Пароль: ${password}`);
            });

            function validateEmail(email) {
                const re = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
                return re.test(String(email).toLowerCase());
            }
        </script>
        
    </body>
</html>
```

<h2 align = "center">Файл "Адаптивная страница.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }  
        
        @media screen and (max-width: 480px) {
            img {
                width: 100%;
            }
        }   

        @media screen and (min-width: 481px) and (max-width: 768px) {
            img {
                width: 50%;
            }
        }

        @media screen and (min-width: 769px) and (max-width: 1024px) {
            img {
                width: 33.33%;
            }
        }

        @media screen and (min-width: 1025px) {
            img {
                width: 25%;
            }
        }
        
        </style>
    </head>

    <body style="background-color:burlywood;">
        <div class="image-container">
            <img src="мопс.jpg" alt="мопс">
        </div>
    </body>
</html>
```

<h2 align = "center">Файл "слайдер.html"</h2>
```
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Slider</title>
    <style>
        .slider {
            max-width: 100%;
            margin: 0 auto;
            position: relative;
        }
        .slider__wrapper {
            overflow: hidden;
        }
        .slider__container {
            display: flex;
            font-size: 7rem;
            will-change: transform;
            transition: transform 0.5s cubic-bezier(0.7, -0.22, 1, -0.24);
        }

        .slider__item {
            flex-shrink: 0;
            flex-grow: 1;
            flex-basis: 100%;
            max-width: 100%;
            height: 300px;
            justify-content: center;
            align-items: center;
            color: white;
            width: 250px;
            border-radius: 10px;
            background: #198754;
        }
        .slider__item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .slider__btn {
            position: absolute;
            top: 50%;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            width: 40px;
            height: 40px;
            text-align: center;
            border: none;
            background: rgba(119, 119, 119, 0.39);
            transform: translateY(-50%);
            cursor: pointer;
        }
        .slider__btn_prev {
            left: 0;
        }
        .slider__btn_next {
            right: 0;
        }
        .slider__btn_hidden {
            display: none;
        }
    </style>
</head>
<body>
<div class="slider" style="width: 500px">
    <div class="slider__wrapper">
        <div class="slider__container" id="slider">
            <div class="slider__item">
                <img src="мопс.jpg" alt="мопс 1">
            </div>
            <div class="slider__item">
                <img src="мопс.jpg" alt="мопс 2">
            </div>
            <div class="slider__item">
                <img src="мопс.jpg" alt="мопс 3">
            </div>
            <div class="slider__item">
                <img src="мопс.jpg" alt="мопс 4">
            </div>
        </div>
    </div>
    <button class="slider__btn slider__btn_prev"><</button>
    <button class="slider__btn slider__btn_next"> ></button>
</div>

<script>
    class Slider {
        constructor(nameSliderItems, btnPrev, btnNext, idSlider) {
            this.slides = document.getElementsByClassName(nameSliderItems);
            this.index = 0;
            this.width = 0;
            this.widthAll = 0;
            this.slider = document.getElementById(idSlider);
            this.btnPrev = document.getElementsByClassName(btnPrev)[0];
            this.btnNext = document.getElementsByClassName(btnNext)[0];
            this.btnPrev.addEventListener('click', this.prev.bind(this));
            this.btnNext.addEventListener('click', this.next.bind(this));
            for (let i = 0; i < this.slides.length; i++) {
                this.widthAll += this.slides[i].offsetWidth;
            }

            this.changeBtn();
        }
        show (index) {
            if (index > this.slides.length - 1) {
                console.log(index )
                this.index = 1;
                this.width = 0;
            }

            if (index < 1) {
                this.index = this.slides.length - 1
            }

            let i = 0;
            for (i; i < this.slides.length; i++) {
                this.slides[i].className = this.slides[i].className.replace(' slider__item_active ', '');
            }

            this.slides[this.index].className = this.slides[this.index].className.replace('', ' slider__item_active ');
        }

        next () {
            this.show(this.index += 1);
            this.width += this.slides[this.index].offsetWidth;
            this.changePosition()
        }

        prev () {
            this.show(this.index -= 1);
            this.width -= this.slides[this.index].offsetWidth;
            this.changePosition()
        }

        changeBtn () {
            if (this.width + this.slides[this.index].offsetWidth >= this.widthAll) {
                this.btnNext.className =  this.btnNext.className.replace('', ' slider__btn_hidden ');
            } else {
                this.btnNext.className =  this.btnNext.className.replace(' slider__btn_hidden ', '');
            }

            if (this.width === 0) {
                this.btnPrev.className =  this.btnPrev.className.replace('', ' slider__btn_hidden ');
            } else {
                this.btnPrev.className =  this.btnPrev.className.replace(' slider__btn_hidden ', '');
            }
        }

        changePosition () {
            this.changeBtn();
            this.slider.setAttribute('style', `transform: translate3d(${-this.width}px, 0px, 0px)`);
        }
     }

    let slider = new Slider('slider__item', 'slider__btn_prev', 'slider__btn_next', 'slider');
    slider.show(0);
</script>
</body>
</html>
```

<h2 align = "center">Файл "табличное представление.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css">
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }
        
        body {
            font-family: 'Open Sans', sans-serif;
        }

        h1 {
            font-weight: 700;
        }

        p {
            font-weight: 400;
        }
        
        </style>
    </head>

    <body style="background-color:burlywood;">
        <table id="my-table">
            <thead>
              <tr>
                <th data-column="имя">Имя</th>
                <th data-column="возраст">Возраст</th>
                <th data-column="город">Город</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td data-column="имя">Джон</td>
                <td data-column="возраст">30</td>
                <td data-column="город">Нью-Йорк</td>
              </tr>
              <tr>
                <td data-column="имя">Мария</td>
                <td data-column="возраст">25</td>
                <td data-column="город">Париж</td>
              </tr>
              <tr>
                <td data-column="имя">Боб</td>
                <td data-column="возраст">40</td>
                <td data-column="город">Лондон</td>
              </tr>
            </tbody>
        </table>

        <script>
            const table = document.getElementById('my-table');
            // Добавление сортировки
            table.querySelectorAll('th').forEach(header => {
            header.addEventListener('click', () => {
                const column = header.getAttribute('data-column');
                const order = header.getAttribute('data-order');

            // Очистка предыдущей сортировки
            table.querySelectorAll('th').forEach(th => {
                th.removeAttribute('data-order');
            });

            // Установка новой сортировки
            if (order === 'asc') {
                header.setAttribute('data-order', 'desc');
            } else {
                header.setAttribute('data-order', 'asc');
            }

            // Сортировка данных
            const rows = Array.from(table.querySelectorAll('tbody tr'));
            rows.sort((a, b) => {
                const aValue = a.querySelector(`td[data-column="${column}"]`).textContent;
                const bValue = b.querySelector(`td[data-column="${column}"]`).textContent;

                if (order === 'asc') {
                    return aValue.localeCompare(bValue);
                } else {
                    return bValue.localeCompare(aValue);
                }
            });

            // Отображение отсортированных данных
            table.querySelector('tbody').innerHTML = rows.map(row => row.outerHTML).join('');
            });
        });

        // Добавление фильтрации
        const filters = document.querySelectorAll('.filter-input');

        filters.forEach(filter => {
            filter.addEventListener('input', () => {
            const column = filter.getAttribute('data-column');
            const value = filter.value.toLowerCase();

            // Фильтрация данных
            const rows = Array.from(table.querySelectorAll('tbody tr'));
            rows.forEach(row => {
            const cellValue = row.querySelector(`td[data-column="${column}"]`).textContent.toLowerCase();

            if (cellValue.includes(value)) {
                row.style.display = '';
            } else {
                row.style.display = 'none';
            }
            });
        });
        });
        </script>
        
        <h1>ВАУ, ЭТО ЖЕ ЗАГОЛОВОК С ВЕБ-ШРИФТОМ</h1>
        <p>Вау, это же текст с веб-шрифтом</p>
    </body>
</html>
```

<h2 align = "center">Файл "Drag and Drop.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаборатоная работа №2 - 3 часть"</title>
        <link rel="stylesheet" type="text/css">
        <style>        
        .center {
            text-align: center;
        }

        .right {
            text-align: right;
        }

        .image-container {
            display: flex;
        }
        .image-container img {
            width: 50%;
        }     

        #drop-zone {
            width: 200px;
            height: 200px;
            border: 1px dashed #ccc;
            padding: 20px;
        }

        .dragging {
            background-color: #ccc;
        }
        
        </style>
    </head>

    <body style="background-color:burlywood;">    
        <div id="item1" draggable="true" class="center">Элемент 1</div>
        <div id="item2" draggable="true" class="center">Элемент 2</div>
        <div id="item3" draggable="true" class="center">Элемент 3</div>
        <div id="item4" draggable="true" class="center" class="image-container"><img src="мопс.jpg" alt="мопс" width="100" height="100"></div>
        <div id="drop-zone" class="center">Зона сброса</div>
        
        <script>
            const items = document.querySelectorAll('[draggable="true"]');
            const dropZone = document.getElementById('drop-zone');

            // Добавление обработчиков событий для перетаскивания
            items.forEach(item => {
                item.addEventListener('dragstart', dragStart);
                item.addEventListener('dragend', dragEnd);
            });

            // Обработчик события начала перетаскивания
            function dragStart(e) {
                e.dataTransfer.setData('text/plain', e.target.id);
                e.target.classList.add('dragging');
            }

            // Обработчик события окончания перетаскивания
            function dragEnd(e) {
                e.target.classList.remove('dragging');
            }

            // Добавление обработчика событий для перетаскивания в зону сброса
            dropZone.addEventListener('dragover', dragOver);
            dropZone.addEventListener('drop', drop);

            // Обработчик события перетаскивания над зоной сброса
            function dragOver(e) {
                e.preventDefault();
            }

            // Обработчик события сброса в зону сброса
            function drop(e) {
                e.preventDefault();
                const id = e.dataTransfer.getData('text/plain');
                const item = document.getElementById(id);
                dropZone.appendChild(item);
            }
        </script>

    </body>
</html>
```

<h2 align = "center">Файл "style.css"</h2>

```
a:link {
    color:brown;
    background-color: transparent;
    text-decoration: none;
}

a:hover {
    color: red;
    background-color: transparent;
    text-decoration: none;
}

a:visited {
    color:darkred;
    background-color: transparent;
    text-decoration: none;
}

a:active {
    color:crimson;
    background-color: transparent;
    text-decoration: none;
}

img {
    position: center;
    left: 50%;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

nav {
    background-color: #dabebe;
    color: #fff;
    text-align: center;
    padding: 5px 0;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}
```

<h2 align = "center">Файл "style2.css"</h2>

```
a:link {
    color:brown;
    background-color: transparent;
    text-decoration: none;
}

a:hover {
    color: red;
    background-color: transparent;
    text-decoration: none;
}

a:visited {
    color:darkred;
    background-color: transparent;
    text-decoration: none;
}

a:active {
    color:crimson;
    background-color: transparent;
    text-decoration: none;
}

img {
    position: absolute;
    top: 125%;
    left: 50%;
    transform: translate(-50%, -50%);
}

body {
    font-family:'Courier New', Courier, monospace;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

nav {
    background-color: #dabebe;
    color: #fff;
    text-align: center;
    padding: 5px 0;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}

footer {
    background-color: #af9f9f;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

video {
    position: absolute;
    top: 170%;
    left: 50%;
    transform: translate(-50%, -50%);
}

form {
    position: absolute;
    top: 200%;
    left: 50%;
    transform: translate(-50%, -50%);
}

table {
    position: absolute;
    top: 230%;
    left: 50%;
    transform: translate(-50%, -50%);
}

#map {
    height: 500px;
    width: 100%;
}

nav {
    background-color: #333;
    color: white;
    padding: 10px;
}
  
nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    align-items: center;
}

nav li {
    margin: 0 20px;
}
  
nav a {
    text-decoration: none;
    color: white;
}
  
nav a:hover {
    color: #ddd;
}
  
@media screen and (max-width: 768px) {
    nav ul {
      flex-direction: column;
    }
  
    nav li {
      margin: 10px 0;
    }
  }

  .gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
  }
  
  .gallery figure {
    width: 200px;
    height: 200px;
    overflow: hidden;
  }
  
  .gallery figure a {
    display: block;
    width: 50%;
    height: 50%;
  }
  
  .gallery figure img {
    object-fit: contain;
    transition: transform 0.2s ease-in-out;
  }
  
  .gallery figure:hover img {
    transform: scale(1.2);
  }
  
  @media screen and (max-width: 768px) {
    .gallery figure {
      width: 100px;
      height: 100px;
    }
  }

  form {
    display:flex;
    flex-direction: column;
    gap: 10px;
    top: 150px; 
    position: relative;
  }
  
  form label {
    margin-bottom: 5px;
  }
  
  form select,
  form input {
    width: 200px;
    padding: 5px;
  }

  iframe {
    top: 150px;  
    position: relative;
  }
```

<h1 align = "center">Результат</h1>

<p>Мы получили несколько файлов, которые имеют решения поставленных задач</p>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я попробовал различный функционал, который можно добавить на свой веб-сайт, а также я закрепил полученные мной знания.</p>
