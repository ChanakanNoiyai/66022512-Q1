<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        header, footer {
            background-color: rgb(103, 74, 110);
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        .container {
            display: flex;
            height: 600px;
        }

        .left-page, .right-page {
            width: 15%;
            background-color: #f2f2f2;
            padding: 20px;
            font-family: initial;
        }

        .body {
            width: 65%;
            height: auto;
            flex-grow: 1;
            padding: 20px;
           font-family: initial;
           font-size: larger;
            background-color: #bb7493;
        }
    </style>
    <title>welcome</title>
</head>
<body>

    <header>
        <h1>Front End Quiz 1</h1>
    </header>

    <div class="container">
        <div class="left-page">
        <h1>Left Page</h1>
        <p><a href="https://www.google.com/" target="_blank">Page 1</a></p>
        <p><a href="https://www.google.com/" target="_blank">Page 2</a></p>
        <p><a href="https://www.google.com/" target="_blank">Page 3</a></p>
        <p><a href="https://www.google.com/" target="_blank">Page 4</a></p>
        </div>

        <div class="body">
            <h2>Body Page</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus consequatur reiciendis, porro labore nemo quos autem dolore, natus aliquid ipsa iusto dolorum unde a.
                 Tempore repellat minus expedita animi sapiente.</p>
        </div>

        <div class="right-page">
            <h2>Right Page</h2>
            <picture>
                <image src=https://cdn-icons-png.flaticon.com/512/9131/9131529.png width="90%" height="30%"></image>
            </picture>
        </div>
    </div>

    <footer>
        <p>footer</p>
    </footer>

</body>
</html>
