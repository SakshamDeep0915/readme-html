```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction - Saksham Deep</title>
    
    <style>
        /* General Styling */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1E90FF, #7B68EE);
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            color: white;
            text-align: center;
        }
        
        /* Card Container */
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
        }
        
        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0px 5px 20px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
            transition: 0.3s ease-in-out;
            max-width: 450px;
        }
        
        .card:hover {
            transform: scale(1.05);
        }
        
        h1 {
            color: #F8F8FF;
            font-size: 28px;
        }
        
        p {
            font-size: 18px;
            color: #F0F8FF;
            margin: 10px 0;
        }
        
        .highlight {
            color: #FFD700;
            font-weight: bold;
        }
        
        /* Animated Text */
        .animated-text {
            font-size: 22px;
            font-weight: bold;
            animation: glow 1.5s infinite alternate;
        }
        
        @keyframes glow {
            0% { color: #FFD700; }
            100% { color: #FFF; }
        }
        
        /* Stylish Button */
        .btn {
            background: linear-gradient(90deg, #FFD700, #FF8C00);
            color: white;
            padding: 12px 25px;
            border: none;
            cursor: pointer;
            border-radius: 25px;
            font-size: 18px;
            transition: all 0.3s ease;
            box-shadow: 0px 4px 10px rgba(255, 140, 0, 0.5);
        }
        
        .btn:hover {
            transform: translateY(-3px);
            background: linear-gradient(90deg, #FF8C00, #FFD700);
            box-shadow: 0px 6px 15px rgba(255, 140, 0, 0.7);
        }
        
    </style>
</head>
<body>

    <div class="container">
        <div class="card">
            <h1>Welcome to My Page! 🚀</h1>
            <p class="animated-text">Hi, I'm <span class="highlight">Saksham Deep</span></p>
            <p>📚 Course: <span class="highlight">B.E. Computer Science Engineering</span></p>
            <p>💡 Passion: Web Development & AI</p>
            <p>🎯 Goal: Build impactful software solutions</p>
            <button class="btn">Know More</button>
        </div>
    </div>

</body>
</html>
