# 📂 1. ГОТОВА ОСНОВА СТОРІНКИ

Створи файл **index.html** і встав код нижче:

```html
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Моє хобі</title>

    <style>
        body {
            font-family: Arial;
            background-color: #f2f2f2;
            margin: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }

        img {
            width: 250px;
            border-radius: 10px;
        }
    </style>
</head>

<body>

<header>
    <h1>Моє хобі</h1>
    <p>Це моя перша веб-сторінка</p>
</header>

<section id="about">
    <h2>Про мене</h2>
    <p>Тут учень описує своє хобі.</p>
</section>

<section id="images">
    <h2>Зображення</h2>
    <img src="https://via.placeholder.com/250" alt="Приклад зображення">
</section>

<section id="media">
    <h2>Мультимедіа</h2>
    <p>Тут буде відео або аудіо</p>
</section>

<section id="links">
    <h2>Корисні посилання</h2>
    <p>Посилання будуть додані учнем</p>
</section>

<footer>
    <p>© 2026 Учнівський проєкт</p>
</footer>

</body>
</html>
```

# 🧭 2. ПОКРОКОВІ ЗАВДАННЯ

---

## 🔧 КРОК 1 (5 хв): Персоналізація

Змініть:

- заголовок `<h1>` (тема вашого хобі)
- текст у розділі "Про мене"

---

## 🔗 КРОК 2 (10 хв): Додайте посилання

У секції **"Корисні посилання"** додайте:

- 2 зовнішні посилання (YouTube, Wikipedia тощо)
- 1 внутрішнє посилання (перехід до розділу "Зображення")

📌 Вимоги:
- використовувати `<a href="">`
- одне посилання має відкриватися в новій вкладці (`target="_blank"`)

---

## 🖼️ КРОК 3 (10 хв): Додайте зображення

- замініть placeholder-зображення
- додайте ще 1–2 зображення по темі

📌 Вимоги:
- мінімум 2 зображення
- обов’язково `alt`
- хоча б одне зображення змініть по розміру

---

## 🎥 КРОК 4 (10 хв): Додайте мультимедіа

У секцію **"Мультимедіа"** додайте:

### Варіант 1 (YouTube):
```html
<iframe width="300" height="200"
src="https://www.youtube.com/embed/dQw4w9WgXcQ"
allowfullscreen>
</iframe>

АБО

## Варіант 2 (аудіо)

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
