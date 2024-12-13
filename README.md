- 👋 Hi, I’m @Akfikafi789
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Akfikafi789/Akfikafi789 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemandangan Matahari Terbit di Padang Pasir</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #1c1c1c;
        }
        .sunrise {
            width: 100%;
            height: 100%;
            position: relative;
            background: linear-gradient(to top, #ffcc33, #ff9966, #ff6699, #cc66ff, #3399ff);
            animation: moveClouds 10s linear infinite;
        }
        .sun {
            position: absolute;
            bottom: 10%;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, #ffcc33 0%, #ff9933 50%, #ff6600 100%);
            border-radius: 50%;
            box-shadow: 0 0 50px #ff6600;
        }
        .sand {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 20%;
            background: linear-gradient(to top, #d2b48c, #f5deb3);
            animation: moveSand 5s infinite ease-in-out;
        }
        @keyframes moveSand {
            0% {background-position: 0 0;}
            100% {background-position: 100% 100%;}
        }
    </style>
</head>
<body>
    <div class="sunrise">
        <div class="sun"></div>
        <div class="sand"></div>
    </div>
</body>
</html>
