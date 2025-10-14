# Hello! 👋 I'm Sushan from Nepal

<div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

###

<div align="center">
  <a href="https://www.linkedin.com/in/sushan-shrestha-99714238a/">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo" />
  </a>
  <a href="https://www.youtube.com/">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo" />
  </a>
  <a href="https://twitter.com/">
    <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo" />
  </a>
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=sushan.sushan&"  />
</div>

## 👩‍💻 About Me

- 🎓 I'm currently a student  
- 🤖 Learning AI/ML (Artificial Intelligence & Machine Learning)  
- 🎮 In my free time, I enjoy playing games  
- 💡 Passionate about coding, AI, and emerging technologies  

## 🛠️ Technologies & Tools

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo" />
</div>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Stats Dashboard</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: #e2e8f0;
            min-height: 100vh;
            padding: 2rem;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .container {
            max-width: 1000px;
            width: 100%;
        }
        
        header {
            text-align: center;
            margin-bottom: 2.5rem;
        }
        
        h1 {
            font-size: 2.5rem;
            background: linear-gradient(90deg, #4facfe, #00f2fe);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 0.5rem;
        }
        
        .username {
            color: #94a3b8;
            font-size: 1.2rem;
        }
        
        .dashboard {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
        }
        
        @media (max-width: 768px) {
            .dashboard {
                grid-template-columns: 1fr;
            }
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1rem;
            margin-bottom: 2rem;
        }
        
        .stat-card {
            background: rgba(30, 41, 59, 0.7);
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(79, 172, 254, 0.2);
            transition: transform 0.3s ease;
        }
        
        .stat-card:hover {
            transform: translateY(-5px);
        }
        
        .stat-title {
            font-size: 0.9rem;
            color: #94a3b8;
            margin-bottom: 0.5rem;
        }
        
        .stat-value {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(90deg, #4facfe, #00f2fe);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        .languages-box {
            background: rgba(30, 41, 59, 0.7);
            border-radius: 12px;
            padding: 2rem;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(79, 172, 254, 0.2);
            margin-bottom: 2rem;
        }
        
        .languages-title {
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            text-align: center;
            color: #e2e8f0;
        }
        
        .language {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.2rem;
            padding: 0.8rem;
            background: rgba(15, 23, 42, 0.5);
            border-radius: 8px;
            transition: all 0.3s ease;
        }
        
        .language:hover {
            background: rgba(15, 23, 42, 0.8);
            transform: scale(1.02);
        }
        
        .language-name {
            display: flex;
            align-items: center;
            gap: 0.8rem;
            font-weight: 600;
        }
        
        .language-percentage {
            font-weight: 700;
            color: #4facfe;
        }
        
        .language-icon {
            font-size: 1.5rem;
        }
        
        .cpp-icon {
            color: #00599c;
        }
        
        .python-icon {
            color: #3776ab;
        }
        
        .js-icon {
            color: #f7df1e;
        }
        
        .ts-icon {
            color: #3178c6;
        }
        
        .other-icon {
            color: #94a3b8;
        }
        
        .progress-bar {
            height: 8px;
            background: rgba(15, 23, 42, 0.8);
            border-radius: 4px;
            margin-top: 0.5rem;
            overflow: hidden;
        }
        
        .progress {
            height: 100%;
            border-radius: 4px;
        }
        
        .cpp-progress {
            width: 52%;
            background: linear-gradient(90deg, #00599c, #004482);
        }
        
        .python-progress {
            width: 36%;
            background: linear-gradient(90deg, #3776ab, #2d5d87);
        }
        
        .js-progress {
            width: 7%;
            background: linear-gradient(90deg, #f7df1e, #d6c31a);
        }
        
        .ts-progress {
            width: 4%;
            background: linear-gradient(90deg, #3178c6, #2861a5);
        }
        
        .other-progress {
            width: 1%;
            background: linear-gradient(90deg, #94a3b8, #7c8ba1);
        }
        
        .streak-box {
            background: rgba(30, 41, 59, 0.7);
            border-radius: 12px;
            padding: 2rem;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(79, 172, 254, 0.2);
        }
        
        .streak-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
        }
        
        .streak-title {
            font-size: 1.5rem;
            color: #e2e8f0;
        }
        
        .current-streak {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1.1rem;
            color: #ff6b6b;
        }
        
        .fire-icon {
            font-size: 1.5rem;
        }
        
        .streak-calendar {
            display: grid;
            grid-template-columns: repeat(7, 1fr);
            gap: 0.5rem;
            margin-bottom: 1rem;
        }
        
        .streak-day {
            aspect-ratio: 1;
            background: rgba(15, 23, 42, 0.7);
            border-radius: 4px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.7rem;
            transition: all 0.3s ease;
        }
        
        .streak-day.active {
            background: linear-gradient(135deg, #4facfe, #00f2fe);
            box-shadow: 0 0 8px rgba(79, 172, 254, 0.5);
        }
        
        .streak-day.today {
            border: 2px solid #ff6b6b;
        }
        
        .contribution-info {
            text-align: center;
            color: #94a3b8;
            font-size: 0.9rem;
        }
        
        .footer {
            text-align: center;
            margin-top: 2rem;
            color: #64748b;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>GitHub Statistics</h1>
            <div class="username">SushanShrestha-Outcode</div>
        </header>
        
        <div class="dashboard">
            <div class="left-panel">
                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-title">Total Stars Earned</div>
                        <div class="stat-value">12</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-title">Total Commits</div>
                        <div class="stat-value">187</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-title">Total PRs</div>
                        <div class="stat-value">24</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-title">Total Issues</div>
                        <div class="stat-value">8</div>
                    </div>
                </div>
                
                <div class="languages-box">
                    <h2 class="languages-title">Most Used Languages</h2>
                    
                    <div class="language">
                        <div class="language-name">
                            <i class="language-icon cpp-icon fas fa-cog"></i>
                            <span>C++</span>
                        </div>
                        <div class="language-percentage">52%</div>
                    </div>
                    <div class="progress-bar">
                        <div class="progress cpp-progress"></div>
                    </div>
                    
                    <div class="language">
                        <div class="language-name">
                            <i class="language-icon python-icon fab fa-python"></i>
                            <span>Python</span>
                        </div>
                        <div class="language-percentage">36%</div>
                    </div>
                    <div class="progress-bar">
                        <div class="progress python-progress"></div>
                    </div>
                    
                    <div class="language">
                        <div class="language-name">
                            <i class="language-icon js-icon fab fa-js-square"></i>
                            <span>JavaScript</span>
                        </div>
                        <div class="language-percentage">7%</div>
                    </div>
                    <div class="progress-bar">
                        <div class="progress js-progress"></div>
                    </div>
                    
                    <div class="language">
                        <div class="language-name">
                            <i class="language-icon ts-icon fab fa-js-square"></i>
                            <span>TypeScript</span>
                        </div>
                        <div class="language-percentage">4%</div>
                    </div>
                    <div class="progress-bar">
                        <div class="progress ts-progress"></div>
                    </div>
                    
                    <div class="language">
                        <div class="language-name">
                            <i class="language-icon other-icon fas fa-code"></i>
                            <span>Other</span>
                        </div>
                        <div class="language-percentage">1%</div>
                    </div>
                    <div class="progress-bar">
                        <div class="progress other-progress"></div>
                    </div>
                </div>
            </div>
            
            <div class="right-panel">
                <div class="streak-box">
                    <div class="streak-header">
                        <h2 class="streak-title">GitHub Streak</h2>
                        <div class="current-streak">
                            <span class="fire-icon">🔥</span>
                            <span>42 days</span>
                        </div>
                    </div>
                    
                    <div class="streak-calendar" id="streakCalendar">
                        <!-- Calendar will be generated by JavaScript -->
                    </div>
                    
                    <div class="contribution-info">
                        Longest streak: 68 days | Total contributions: 324
                    </div>
                </div>
                
                <div class="stats-grid" style="margin-top: 2rem;">
                    <div class="stat-card">
                        <div class="stat-title">Repositories</div>
                        <div class="stat-value">14</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-title">Followers</div>
                        <div class="stat-value">28</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-title">Following</div>
                        <div class="stat-value">16</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-title">Contributed to</div>
                        <div class="stat-value">5</div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="footer">
            Last updated: October 2023 | Data from GitHub API
        </div>
    </div>

    <script>
        // Generate streak calendar
        const streakCalendar = document.getElementById('streakCalendar');
        const today = new Date();
        const startDate = new Date();
        startDate.setDate(today.getDate() - 90); // Show last 90 days
        
        for (let i = 0; i < 91; i++) {
            const day = new Date(startDate);
            day.setDate(startDate.getDate() + i);
            
            const dayElement = document.createElement('div');
            dayElement.className = 'streak-day';
            
            // Randomly mark some days as active for demonstration
            if (Math.random() > 0.3) {
                dayElement.classList.add('active');
            }
            
            // Mark today
            if (day.toDateString() === today.toDateString()) {
                dayElement.classList.add('today');
            }
            
            streakCalendar.appendChild(dayElement);
        }
    </script>
</body>
</html>

## 📫 How to reach me

- 📧 Connect with me on [LinkedIn](https://www.linkedin.com/in/sushan-shrestha-99714238a/)  
- 💼 Open to collaborations and learning opportunities  

---

*Thanks for visiting my profile! Have a great day!* 😊
