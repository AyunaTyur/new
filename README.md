<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyMum</title>
    <style>
        h1 {
            color: #000000;
            font-size: 64px;
            text-align: center;
        }
        p {
            color: #000000;
            font-size: 24px;
            text-align: center;
        }
        .photo-block {
            display: flex; 
            gap: 50px; 
            align-items: flex-start; 
            justify-content: center; 
            flex-wrap: wrap;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 32px; 
            }
            h2 {
                font-size: 24px;
            }
            p {
                font-size: 16px; 
            }
            .photo-block {
                gap: 20px; 
                flex-direction: column; 
                align-items: center; 
            }
            .photo-block img {
                width: 100%; 
                max-width: 100%;
                height: auto;
            }
            .photo-block > div {
                width: 100%; 
                gap: 5px;
            }
            .photo-block p {
                max-width: 100% !important; 
            }
        }
    </style>
</head>
<body>
    <h1>Дорогая мама,</h1>
    <p>Поздравляю тебя с днем рождения❤️</p>
    <br>
    <h2>Хочу сказать тебе</h2>
    <br>

<p style="margin-top: 70px;"></p>

<div class="photo-block">
    <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
        <img src="photo/one.png" alt="a" height="400" width="520">
        <p style="margin: 0; text-align: center; max-width: 520px;">
            Спасибо тебе за твое тепло, заботу и поддержку
        </p>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
        <img src="photo/two.png" alt="b" height="400">
        <p style="margin: 0; text-align: center; max-width: 300px;">
             Спасибо за твою любовь
        </p>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
        <img src="photo/three.JPG" alt="c" height="400">
        <p style="margin: 0; text-align: center; max-width: 300px;">
            Ты самая лучшая на свете
        </p>
    </div>
</div>
<br>
<div class="photo-block">
    <div style="display: flex; flex-direction: column; align-items: center; gap: 30px;">
        <img src="photo/four.JPG" alt="a" height="400" width="520">
        <p style="margin: 0; text-align: center; max-width: 520px;">
            Спасибо за то, что показала нам мир
        </p>
    </div>
    <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
        <img src="photo/six.png" alt="b" height="400">
        <p style="margin: 0; text-align: center; max-width: 300px;">
            Спасибо за то, что воспитала нас
        </p>
    </div>
      <div style="display: flex; flex-direction: column; align-items: center; gap: 10px;">
        <img src="photo/five.png" alt="c" height="400">
        <p style="margin: 0; text-align: center; max-width: 300px;">
            И просто за то, что ты — наша мама
        </p>
    </div>
</div>
    <br>
    <button onclick="alert('Мама, я тебя очень люблю! ❤️')">Нажми на меня!</button>
</body>
</html>
