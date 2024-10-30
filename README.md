<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="diwalicode-homepage.css">
    <link href="https://fonts.googleapis.com/css2?family=Sacramento&display=swap" rel="stylesheet">
    <title>Best Wishes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #8fdef6;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .title {
            color: white;
            font-family: 'Sacramento', cursive;
            font-size: 30px;
            text-align: center;
            text-shadow: 2px 2px 4px #000000;
        }

        .form-container {
            background: rgb(215, 129, 195);
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(80, 78, 78, 0.1);
            max-width: 300px;
            padding: 30px;
            filter: drop-shadow(1px 1px 20px white);
        }

        input[type="text"] {
            width: 100%;
            margin: 10px 0;
            border: 1px solid #090a09;
            border-radius: 4px;
            padding: 8px;
        }

        .submit {
            background-color: #3eac58;
            color: #080101;
            width: 100%;
            border: none;
            height: 35px;
            cursor: pointer;
            border-radius: 5px;
            text-align: center;
        }

        .submit:hover {
            background-color: #a2d2ac;
        }

        .anchor {
            color: white;
            text-decoration: none;
            text-shadow: 2px 2px 4px rgb(11, 3, 3);
        }

        @media (max-width: 600px) {
            .form-container {
                width: 90%;
                padding: 20px;
            }

            .title {
                font-size: 24px;
            }
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2 class="title">Best Wishes</h2>
        <form action="happy-diwali.html">
            <label for="name" class="name">NAME:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <button class="submit">
                <a href="happy-diwali.html" class="anchor">SUBMIT</a>
            </button>
        </form>
    </div>
</body>
</html>
