## HTML (index.html)

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourmet | Ресторан высокой кухни</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            padding: 30px 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: 300;
            letter-spacing: 3px;
            color: #222;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #666;
            font-weight: 300;
            margin-bottom: 40px;
        }
        
        .main-image {
            width: 100%;
            height: 70vh;
            object-fit: cover;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .description {
            text-align: center;
            max-width: 800px;
            margin: 0 auto 40px;
            font-size: 1.1rem;
            line-height: 1.8;
            color: #555;
        }
        
        .contact-btn {
            display: block;
            width: 200px;
            margin: 0 auto;
            padding: 15px 0;
            text-align: center;
            background-color: #222;
            color: white;
            text-decoration: none;
            font-size: 1rem;
            border-radius: 4px;
            transition: all 0.3s ease;
        }
        
        .contact-btn:hover {
            background-color: #444;
            transform: translateY(-2px);
        }
        
        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            color: #999;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">GOURMET</div>
            <div class="tagline">Искусство вкуса в каждом блюде</div>
        </header>
        
        <main>
            <img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4" alt="Интерьер ресторана" class="main-image">
            
            <div class="description">
                <p>Добро пожаловать в наш ресторан, где каждое блюдо - это произведение искусства. Мы используем только самые свежие ингредиенты и традиционные рецепты с современным подходом.</p>
            </div>
            
            <a href="https://wa.me/79991234567" class="contact-btn">Связаться с нами</a>
        </main>
        
        <footer>
            <p>© 2023 Gourmet Restaurant. Все права защищены.</p>
        </footer>
    </div>
</body>
</html>
