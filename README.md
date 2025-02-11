<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>蔡际钟是我儿子</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .text {
            font-size: 3rem;
            text-align: center;
            animation: glow 1s infinite alternate, scroll 60s linear;
        }
        @keyframes glow {
            0% {
                text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #ff00de, 0 0 40px #ff00de, 0 0 50px #ff00de, 0 0 60px #ff00de, 0 0 70px #ff00de;
            }
            100% {
                text-shadow: 0 0 20px #fff, 0 0 30px #ff4da6, 0 0 40px #ff4da6, 0 0 50px #ff4da6, 0 0 60px #ff4da6, 0 0 70px #ff4da6, 0 0 80px #ff4da6;
            }
        }
        @keyframes scroll {
            0% {
                transform: translateY(100%);
            }
            100% {
                transform: translateY(-100%);
            }
        }
    </style>
</head>
<body>
    <div class="text">蔡际钟是我儿子</div>
    <script>
        // 阻止用户在一分钟内退出
        setTimeout(function() {
            window.onbeforeunload = null;
        }, 60000);
        window.onbeforeunload = function() {
            return "请等待一分钟后再退出。";
        };
    </script>
</body>
</html>
# -
