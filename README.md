<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Arsya</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
        }
        header {
            background: #294281;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            padding: 20px;
        }
        .sidebar, .main-content {
            width: 100%;
            padding: 15px;
        }
        .sidebar {
            background: #f4f4f4;
        }
        .image-section img {
            width: 100%;
            height: auto;
            margin-top: 10px;
        }
        footer {
            background: #294281;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        @media (min-width: 768px) {
            .container {
                flex-wrap: nowrap;
            }
            .sidebar {
                width: 25%;
            }
            .main-content {
                width: 75%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Hi, Sayang!</h1>
    </header>
    <div class="container">
        <aside class="sidebar">
            <h2>I miss you</h2>
            <p>I’m so sorry you’re feeling unwell. I know it’s tough, but please remember that this is just a temporary setback, and brighter, healthier days are ahead. Dont forget to take time to rest and take care of your body. I wish I could be there to hug you and hold your hand- but i'll be just a call away, sayang. Hang in there, and take it one moment at a time. You've got this! 💙</p>
        </aside>
        <section class="main-content">
            <h2>Hello</h2>
            <p>I want to go to Jogja</p>
            <div class="image-section">
                <img src="Downloads/arsyapicture1.jpeg" alt="Our second lowkey date" width="300" height="400">
                <img src="Downloads/arsyapicture2.jpeg" alt="Our first lowkey date">
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; From Katiana Alya hehe</p>
    </footer>
</body>
</html>
