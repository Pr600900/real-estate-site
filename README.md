<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>יזמות נדל"ן - דף הבית</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            direction: rtl;
            text-align: center;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            font-size: 28px;
            font-weight: bold;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            animation: fadeInDown 1s ease-in-out;
            position: relative;
        }
        .nav {
            background-color: #34495e;
            padding: 10px;
            text-align: center;
        }
        .nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            transition: color 0.3s;
        }
        .nav a:hover {
            color: #f39c12;
        }
        .main-content {
            padding: 50px;
            max-width: 1000px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1.5s ease-in-out;
        }
        .cta-button {
            background-color: #e74c3c;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 20px;
            border-radius: 8px;
            display: inline-block;
            margin-top: 20px;
            transition: background 0.3s, transform 0.3s;
        }
        .cta-button:hover {
            background-color: #c0392b;
            transform: scale(1.1);
        }
        .projects {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        .project-card {
            width: 300px;
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 3px 3px 15px rgba(0, 0, 0, 0.15);
            background: white;
            transition: transform 0.3s ease-in-out;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 1s ease-in-out forwards;
        }
        .project-card:nth-child(2) {
            animation-delay: 0.5s;
        }
        .project-card:hover {
            transform: scale(1.05);
        }
        .about {
            margin-top: 50px;
            padding: 20px;
            background-color: #ecf0f1;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="header">ברוכים הבאים ליזמות הנדל"ן שלנו</div>
    <div class="nav">
        <a href="index.html">דף הבית</a>
        <a href="projects.html">הפרויקטים</a>
        <a href="about.html">אודות</a>
        <a href="contact.html">צור קשר</a>
    </div>
    <div class="main-content">
        <h1>השקעות ופרויקטים פורצי דרך</h1>
        <p>אנו מובילים את תחום יזמות הנדל"ן, עם פרויקטים חדשניים ושירות מקצועי.</p>
        <a href="#contact" class="cta-button">צור קשר</a>
        
        <div class="about">
            <h2>אודות החברה</h2>
            <p>החברה שלנו מתמחה בייזום ופיתוח פרויקטים נדל"ניים מובילים בישראל. עם ניסיון רב שנים וצוות מומחים, אנו מציעים פתרונות חכמים ומשתלמים בתחום הנדל"ן, תוך דגש על איכות, אמינות וחדשנות.</p>
        </div>
        
        <h2>הפרויקטים שלנו</h2>
        <div class="projects">
            <div class="project-card">
                <h3>פרויקט יוקרתי בירושלים</h3>
                <p>דירות מפוארות עם נוף עוצר נשימה.</p>
            </div>
            <div class="project-card">
                <h3>שכונת מגורים מודרנית</h3>
                <p>קהילה חדשנית עם תשתיות מתקדמות.</p>
            </div>
        </div>
    </div>
</body>
</html>
