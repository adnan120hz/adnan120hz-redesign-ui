<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Adnan.120hz - Apple Security Research</title>  
    <style>  
        body {  
            margin: 0;  
            padding: 0;  
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;  
            color: #f5f5f7;  
            background-color: #050505;  
            /* Background: Banyak iPhone 14/17 Pro Max (SVG Pattern) */  
            background-image:   
                /* Overlay gelap agar teks tetap terang */  
                radial-gradient(circle at 50% 0%, rgba(30, 30, 40, 0.9), rgba(0, 0, 0, 0.95)),  
                /* Pola Grid iPhone */  
                url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='400' viewBox='0 0 400 400'%3E%3Cg transform='translate(50, 50) rotate(15)'%3E%3Crect x='0' y='0' width='80' height='160' rx='25' fill='none' stroke='rgba(255, 255, 255, 0.04)' stroke-width='4'/%3E%3Crect x='8' y='8' width='64' height='144' rx='20' fill='rgba(255, 255, 255, 0.02)'/%3E%3Crect x='25' y='25' width='30' height='10' rx='5' fill='rgba(255, 255, 255, 0.05)'/%3E%3C/g%3E%3Cg transform='translate(280, 200) rotate(-25)'%3E%3Crect x='0' y='0' width='80' height='160' rx='25' fill='none' stroke='rgba(255, 255, 255, 0.04)' stroke-width='4'/%3E%3Crect x='8' y='8' width='64' height='144' rx='20' fill='rgba(255, 255, 255, 0.02)'/%3E%3Crect x='25' y='25' width='30' height='10' rx='5' fill='rgba(255, 255, 255, 0.05)'/%3E%3C/g%3E%3Cg transform='translate(100, 320) rotate(5)'%3E%3Crect x='0' y='0' width='80' height='160' rx='25' fill='none' stroke='rgba(255, 255, 255, 0.04)' stroke-width='4'/%3E%3Crect x='8' y='8' width='64' height='144' rx='20' fill='rgba(255, 255, 255, 0.02)'/%3E%3Crect x='25' y='25' width='30' height='10' rx='5' fill='rgba(255, 255, 255, 0.05)'/%3E%3C/g%3E%3Cg transform='translate(300, 50) rotate(-10)'%3E%3Crect x='0' y='0' width='80' height='160' rx='25' fill='none' stroke='rgba(255, 255, 255, 0.04)' stroke-width='4'/%3E%3Crect x='8' y='8' width='64' height='144' rx='20' fill='rgba(255, 255, 255, 0.02)'/%3E%3Crect x='25' y='25' width='30' height='10' rx='5' fill='rgba(255, 255, 255, 0.05)'/%3E%3C/g%3E%3C/svg%3E");  
            background-size: 400px 400px;  
            display: flex;  
            flex-direction: column;  
            align-items: center;  
            min-height: 100vh;  
        }  
  
```
    .container {
        width: 90%;
        max-width: 800px;
        padding: 40px 0;
        text-align: center;
        z-index: 10;
    }

    header {
        margin-bottom: 50px;
    }

    .apple-logo {
        width: 80px;
        height: 80px;
        margin: 0 auto 20px auto;
        font-size: 60px;
        line-height: 80px;
        color: #fff;
        text-shadow: 0 0 30px rgba(255, 255, 255, 0.6);
    }

    h1 {
        font-size: 2.8rem;
        font-weight: 600;
        letter-spacing: -0.02em;
        margin: 0 0 10px 0;
        background: linear-gradient(180deg, #fff, #86868b);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    p.subtitle {
        font-size: 1.1rem;
        color: #a1a1a6;
        margin-bottom: 0;
        text-transform: uppercase;
        letter-spacing: 2px;
    }

    /* Glassy Cards */
    .card-list {
        display: flex;
        flex-direction: column;
        gap: 15px;
    }

    .card {
        display: block;
        background: rgba(255, 255, 255, 0.08);
        border: 1px solid rgba(255, 255, 255, 0.15);
        border-radius: 18px;
        padding: 24px;
        text-decoration: none;
        color: #f5f5f7;
        transition: all 0.3s ease;
        position: relative;
        overflow: hidden;
        backdrop-filter: blur(15px) saturate(180%);
        -webkit-backdrop-filter: blur(15px) saturate(180%);
        box-shadow: 0 4px 24px rgba(0,0,0,0.3);
    }

    .card:hover {
        background: rgba(255, 255, 255, 0.15);
        border-color: rgba(255, 255, 255, 0.4);
        transform: translateY(-3px) scale(1.01);
        box-shadow: 0 12px 40px rgba(0,0,0,0.5);
    }

    .card h3 {
        margin: 0;
        font-size: 1.3rem;
        font-weight: 600;
        text-align: left;
    }

    .card p {
        margin: 8px 0 0;
        font-size: 0.9rem;
        color: #a1a1a6;
        text-align: left;
    }

    .card .arrow {
        position: absolute;
        right: 25px;
        top: 50%;
        transform: translateY(-50%);
        font-size: 1.5rem;
        color: #2997ff;
        font-weight: 300;
    }

    /* Glowing Effect for Background */
    .glow {
        position: fixed;
        top: -20%;
        left: 50%;
        transform: translateX(-50%);
        width: 600px;
        height: 600px;
        background: radial-gradient(circle, rgba(41, 151, 255, 0.15) 0%, transparent 70%);
        border-radius: 50%;
        z-index: -1;
        pointer-events: none;
    }

    footer {
        margin-top: 50px;
        font-size: 0.8rem;
        color: #48484a;
        padding-bottom: 40px;
    }
</style>

```
</head>  
<body>  
  
```
<div class="glow"></div>

<div class="container">
    <header>
        <div class="apple-logo">🍎</div>
        <h1>Welcome to Adnan.120hz</h1>
        <p class="subtitle">Apple Security Research</p>
    </header>

    <div class="card-list">
        <!-- Table 1 -->
        <a href="https://discord.gg/YdNwz7uAR" class="card">
            <h3>Join WorkPlot Discord community</h3>
            <p>Connect with the team and fellow developers.</p>
            <span class="arrow">›</span>
        </a>

        <!-- Table 2 -->
        <a href="https://t.me/adnan120hz" class="card">
            <h3>Join Telegram Adnan.120hz Group</h3>
            <p>Get direct updates from Adnan.</p>
            <span class="arrow">›</span>
        </a>

        <!-- Table 3 -->
        <a href="https://t.me/workplotios" class="card">
            <h3>Join WorkPlot Telegram Group!</h3>
            <p>The main hub for project discussions.</p>
            <span class="arrow">›</span>
        </a>

        <!-- Table 4 -->
        <a href="https://github.com/gievano/WorkPlot" class="card">
            <h3>Github WorkPlot Link!</h3>
            <p>View our source code and releases.</p>
            <span class="arrow">›</span>
        </a>

        <!-- Table 5 -->
        <a href="https://rebuildmisaka.tiiny.site/IMG_1097.jpeg" class="card">
            <h3>Donate to Rebuild Misaka 27!</h3>
            <p>Support the project by viewing the donation QR.</p>
            <span class="arrow">›</span>
        </a>
    </div>

    <footer>
        © 2026 Adnan.120hz. All rights reserved.
    </footer>
</div>

```
</body>  
</html>  
