<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 200px;
        }
        
        h1 {
            font-size: 48px;
            margin-bottom: 30px;
        }
        
        .github-logo {
            width: 200px;
            margin-bottom: 50px;
        }
        
        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 24px;
            background-color: #fff;
            color: #000;
            border-radius: 5px;
            margin: 10px;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        
        .button:hover {
            background-color: #333;
            color: #fff;
        }
        
        .animated {
            animation-duration: 2s;
            animation-fill-mode: both;
        }
        
        .fadeInDown {
            animation-name: fadeInDown;
        }
        
        .bounceIn {
            animation-name: bounceIn;
        }
        
        @keyframes fadeInDown {
            0% {
                opacity: 0;
                transform: translateY(-100%);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes bounceIn {
            0% {
                opacity: 0;
                transform: scale(0.1);
            }
            60% {
                opacity: 1;
                transform: scale(1.2);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }
    </style>
</head>
<body>
    <h1 class="animated fadeInDown">Welcome to My GitHub Profile</h1>
    <img class="github-logo animated bounceIn" src="https://github.githubassets.com/images/modules/logos_page/Octocat.png" alt="GitHub Logo">
    <a class="button" href="https://github.com">Go to my GitHub</a>
</body>
</html>
