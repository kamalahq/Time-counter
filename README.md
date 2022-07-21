# Time-counter
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time-Counter</title>
</head>
<style>
    body {
        background-image: url(123.jpg);
        background-position: center;
        background-size: cover;
        height: 95vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .glass {
        width: 600px;
        height: 300px;
        border-radius: 20px;
        box-shadow: 0px 0px 5px 3px rgba(255, 255, 255, 1);
    }

    h1 {
        color: #fff;
        font-size: 45px;
        font-family: cursive;
        text-align: center;
    }

    p {
        color: #fff;
        text-align: center;
        font-size: 50px;
        font-family: cursive;
    }
</style>

<body>
    <div class="glass">
        <h1>TIME COUNTER :</h1>
        <p id="demo"></p>
    </div>

    <script src="counter.js"></script>
</body>

</html>
