<!DOCTYPE html>
<html lang="uk">
<head>
    <img src="https://cdn.pixabay.com/photo/2018/02/01/06/45/travel-3122702_640.jpg" width="700" height="700"
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Подорожі</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            text-align: center;
            padding: 50px;
            background-image: url('header-image.jpg'); /* Вставте URL вашого зображення */
            background-size: cover;
            color: white;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
        }
        .destinations {
            display: flex;
            justify-content: space-around;
            margin: 50px 0;
        }
        .destination {
            width: 30%;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            text-align: center;
        }
        .destination img {
            width: 100%;
            height: auto;
        }
        .destination h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .destination button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-bottom: 15px;
        }
        .destination button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <header>
        <h1>Подорожі</h1>
    </header>

    <section class="destinations">
        <div class="destination">
            <img src="https://cdn.pixabay.com/photo/2023/03/17/02/42/architecture-7857832_640.jpghttps://cdn.pixabay.com/photo/2023/03/17/02/42/architecture-7857832_640.jpg">
            <h2>Визначне Місце 1</h2>
            <button>Купити білет</button>
        </div>
        <div class="destination">
            <img src="https://cdn.pixabay.com/photo/2021/11/28/15/30/cathedral-6830526_640.jpghttps://cdn.pixabay.com/photo/2021/11/28/15/30/cathedral-6830526_640.jpg">
            <h2>Визначне Місце 2</h2>
            <button>Купити білет</button>
        </div>
        <div class="destination">
            <img src="https://cdn.pixabay.com/photo/2021/11/29/17/32/city-6833167_640.jpg">
            <h2>Визначне Місце 3</h2>
            <button>Купити білет</button>
        </div>
    </section>

</body>
</html>
