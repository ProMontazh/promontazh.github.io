<!DOCTYPE html>
<html lang="ua">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Встановлення охоронної сигналізації та відеоспостереження. Професійний монтаж систем безпеки.">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
    <title>ProМонтаж – Професійне встановлення систем безпеки | монтаж відеоспостереження Харків | монтаж установка домофона Харків | установка сигналізації Харків | монтаж системи контролю доступу Харків</title>
    <style>
        body {
            font-family: 'Open Sans', sans-serif; /* Применяем Open Sans для всего текста */
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            
        }

        /* Для мобільних пристроїв */
        @media (max-width: 768px) {}
    header {
    background: linear-gradient(to right, #222222, #dadada); /* Градиентный фон */
    color: white;
    padding: 6px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative; /* Для абсолютного позиционирования герба */
        }

        /* Стили для герба Украины */
        .ukraine-emblem {
            position: absolute;
            top: 15px; /* Отступ от верхнего края */
            right: 15px; /* Отступ от правого края */
            width: 75px; /* Размер изображения */
            height: auto;
            z-index: 1000; /* Поверх остальных элементов */
            opacity: 0.0; /* Полупрозрачность */
        }

        .ukraine-emblem img {
            width: 100%;
            height: auto;
        }


        /* Анімація для плавної появи тексту */
        @keyframes fadeInText {
            20% {
                opacity: 0;
                transform: translateY(15%); /* Легке зміщення вгору для ефекту */
            }
            100% {
                opacity: 1;
                transform: translateY(0); /* Повертаємо на місце */
            }
        }

        /* Застосування анімації до назви компанії */
        .company-name {
            font-size: 2.4rem;
            margin: 0;
            opacity: 0; /* Спочатку невидимий */
            animation: fadeInText 3s ease-in-out forwards; /* Плавна поява протягом 3 секунд */
        }

        /* Анімація для появи телефонів справа наліво */
        @keyframes slideInFromRight {
            20% {
                opacity: 1;
                transform: translateX(5%); /* Починаємо справа за межами екрана */
            }
            100% {
                opacity: 1;
                transform: translateX(0); /* Телефони переміщуються на своє місце */
            }
        }

        /* Застосування анімації до телефонів з затримкою */
        .company-phone {
            font-size: 1.0rem; /* Зменшено розмір шрифту */
            margin-top: 5px;
            color: #f44336; /* Червоний колір */
            font-weight: bold; /* Жирний шрифт */
            opacity: 0; /* Спочатку невидимий */
            animation: slideInFromRight 2s ease-in-out forwards; /* Анімація появи справа наліво */
            animation-delay: 5.5s; /* Затримка 6 секунди */
        }

        .company-phone a {
            color: #f44336; /* Червоний колір для посилань */
            text-decoration: none;
        }

        .company-description {
            font-size: 0.9rem; /* Зменшено розмір шрифту */
            margin-top: 10px;
            color: white; /* Білий колір тексту */
        }

        .red {
            color: #f44336;
        }

        .black {
            color: black;
        }

        .hero {
            background-color: rgba(0, 0, 0, 0.05); /* Полупрозрачный черный фон */
            background-image: url('fon.jpg'); /* Фонове зображення */
            background-size: cover; /* Розмір фону */
            background-position: center; /* Центрування фону */
            height: 33vh; /* Висота 33% від висоти вікна */
            text-align: center;
            color: rgb(29, 29, 29);
            position: relative;
            animation: fadeIn 2s ease-in-out;
            padding: 20px; /* Відступи всередині секції */
        }

        @media (max-width: 768px) {
            .hero {
                background-image: url('631smal.jpg'); /* Фонове зображення для мобільної версії */
                background-size: cover;
                background-position: center; /* Центрування фону */
                height: 33vh; /* Висота 33% від висоти вікна */
                padding: 20px; /* Відступи всередині секції */
            }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .hero h2 {
    font-size: 1.6rem;
    margin: 40px 0 10px; /* Уменьшаем верхний отступ */
    animation: slideDown 1s ease-in-out;
    position: relative;
    top: -10px; /* Поднимаем заголовок выше */
    display: inline-block;
    padding: 10px 20px; /* Внутренние отступы для текста */
    background-color: rgba(255, 255, 255, 0.2); /* Полупрозрачный белый фон */
    backdrop-filter: blur(10px); /* Размытие фона */
    border-radius: 10px; /* Скругленные углы */
    animation: slideDown 1s ease-in-out;
        }
         @keyframes slideDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        .hero p {
            font-size: 0.9rem;
            font-family: 'Open Sans', sans-serif; /* Новый шрифт */
            font-weight: bold; /* Делаем текст жирным */
            margin-top: 10px; /* Убираем отступ сверху */
            animation: slideUp 1.5s ease-in-out;
        }

        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        .btn {
            background-color: #f44336;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2rem;
            margin-top: 20px;
            animation: pulse 4s infinite;
            text-decoration: none; /* Убираем подчеркивание для ссылок */
            display: inline-block; /* Для того, чтобы стили кнопки применялись к ссылке */
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .btn:hover {
            background-color: #d32f2f;
        }

        .services, .about, .contact {
            padding: 60px 20px;
            text-align: center;
            background-color: white; /* Білий фон для секцій */
        }

        footer {
            background: linear-gradient(to left, #222222, #dadada); /* Градиентный фон */
            color: white;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .messenger-icons {
            margin-top: 20px;
        }

        .messenger-icons img {
            width: 40px;
            margin: 0 10px;
            transition: transform 0.3s;
        }

        .messenger-icons img:hover {
            transform: scale(1.2);
        }
         /* Эффект увеличения заголовков при наведении */
         .service-item h3 {
            cursor: pointer;
            transition: transform 0.3s ease-in-out;
        }

        .service-item h3:hover {
            transform: scale(1.1);
        }
        
        /* Описание услуг изначально скрыто */
        .service-item p {
            display: none;
            margin-top: 10px;
        }

        /* Когда добавляется класс .active, описание становится видимым */
        .service-item.active p {
            display: block;
        }
        /* Анимация появления слева */
@keyframes slideInFromLeft {
    0% {
        opacity: 0;
        transform: translateX(-5%); /* Начинаем за пределами экрана слева */
    }
    100% {
        opacity: 1;
        transform: translateX(0); /* Элемент возвращается на свое место */
    }
}

/* Применение анимации с разной задержкой для каждого элемента */
.service-item {
    opacity: 0; /* Изначально элементы невидимы */
    animation: slideInFromLeft 1s ease-in-out forwards; /* Анимация появления */
}

.service-item:nth-child(1) {
    animation-delay: 0.0s; /* Задержка для первого элемента */
}

.service-item:nth-child(2) {
    animation-delay: 1.2s; /* Задержка для второго элемента */
}

.service-item:nth-child(3) {
    animation-delay: 2.6s; /* Задержка для третьего элемента */
}

.service-item:nth-child(4) {
    animation-delay: 4.0s; /* Задержка для четвертого элемента */
}
   </style>
</head>
<body>

<header>
    <div>
        <h1 class="company-name"><span class="red">Pro</span><span class="black">Монтаж</span></h1>
        <p class="company-description">Професійний монтаж охоронних систем м. Харків</p>
        <p class="company-phone">
            <a href="tel:+380935016040">093-501-60-40</a>,
            <a href="tel:+380662904960">066-290-49-60</a>
        </p>
    </div>
    <!-- Герб Украины -->
    <div class="ukraine-emblem">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/95/Lesser_Coat_of_Arms_of_Ukraine.svg" alt="Герб України">
    </div>
</header>

<section class="hero">
    <h2>Захисти свій дім та бізнес разом з <span class="red">Pro</span><span class="black">Монтаж</span></h2>
    <p>Надійні рішення для вашої безпеки від провідних виробників</p>
    <a href="https://t.me/+380935016040" class="btn" target="_blank">Отримати консультацію</a>
</section>

<section class="services">
    <h2>Встановлюємо</h2>
    
    <div class="service-item">
        <h3>Відеоспостереження</h3>
        <p>Сучасні системи відеоспостереження з можливістю віддаленого доступу.</p>
    </div>
    <div class="service-item"> 
        <h3>Системи контролю доступу</h3>
        <p>Наші системи дозволяють обмежити доступ сторонніх осіб до ваших приміщень.</p>
    </div><div class="service-item">
        <h3>Охоронну сигналізацію</h3>
        <p>Комплексні системи охорони, захистят від несанкціонованого проникнення.</p>
    </div>
    
</section>

<section class="about">
    <h2>Про компанію <span class="red">Pro</span><span class="black">Монтаж</span></h2>
    <p>Наша компанія займається професійним встановленням систем безпеки. Ми пропонуємо індивідуальні рішення для бізнесу і приватних клієнтів, гарантуючи високу якість та надійність.</p>
</section>

<section class="contact">
    <h2>Наші контакти:</h2>
    <p class="company-phone">
        <a href="tel:+380935016040">т. (093) 501-60-40</a>, 
        <a href="tel:+380662904960">т. (066) 290-49-60</a>
    </p>
    <div class="messenger-icons">
        <a href="https://wa.me/380935016040"><img src="whatsapp-icon.png" alt="WhatsApp"></a>
        <a href="https://t.me/+380935016040"><img src="telegram-icon.png" alt="Telegram"></a>
        <a href="viber://add?number=+380935016040"><img src="viber-icon.png" alt="Viber"></a>
    </div>
    <a href="mailto:promontazh.kharkiv@ukr.net?subject=Запит%20на%20послугу&body=" class="btn">promontazh.kharkiv@ukr.net</a>
    </div>
</section>

<footer>
    <p>&copy; 2024 <span class="red">Pro</span><span class="black">Монтаж.</span> Всі права захищені.</p>
</footer>
<script>
    // Получаем все элементы заголовков услуг
    const serviceHeaders = document.querySelectorAll('.service-item h3');

    // Добавляем событие клика на каждый заголовок
    serviceHeaders.forEach(header => {
        header.addEventListener('click', () => {
            const serviceItem = header.parentElement;

            // Переключаем класс active для отображения/скрытия описания
            serviceItem.classList.toggle('active');
        });
    });
</script>
</body>
</html>
