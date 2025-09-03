<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profil Önizleme</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .github-profile {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 30px;
            margin: 20px 0;
        }
        .profile-header {
            text-align: center;
            margin-bottom: 30px;
        }
        h1 {
            color: #58a6ff;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        h2 {
            color: #58a6ff;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
            margin: 25px 0 15px 0;
        }
        h3 {
            color: #58a6ff;
            margin: 20px 0 10px 0;
        }
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        .badge {
            background-color: #238636;
            color: white;
            padding: 5px 10px;
            border-radius: 4px;
            font-size: 14px;
            display: inline-block;
        }
        .stats {
            display: flex;
            justify-content: space-around;
            margin: 25px 0;
        }
        .stat-item {
            text-align: center;
            background-color: #1c2128;
            padding: 15px;
            border-radius: 6px;
            flex: 1;
            margin: 0 10px;
        }
        .projects {
            margin: 20px 0;
        }
        .project-list {
            list-style-type: none;
        }
        .project-list li {
            background-color: #1c2128;
            margin: 10px 0;
            padding: 15px;
            border-radius: 6px;
            border-left: 4px solid #58a6ff;
        }
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 30px;
        }
        .contact-link {
            background-color: #238636;
            color: white;
            padding: 10px 15px;
            border-radius: 6px;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        .contact-link:hover {
            background-color: #2ea043;
        }
        @media (max-width: 768px) {
            .stats {
                flex-direction: column;
            }
            .stat-item {
                margin: 10px 0;
            }
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="github-profile">
        <div class="profile-header">
            <h1>Merhaba, Ben Ahmet! 👋</h1>
            <p>Full Stack Developer & Open Source Enthusiast</p>
        </div>

        <h2>🚀 Hakkımda</h2>
        <p>5 yıldır yazılım geliştiriciliği yapıyorum. JavaScript, React, Node.js ve Python üzerine uzmanlaştım. Sürekli öğrenmeye ve kendimi geliştirmeye inanıyorum.</p>

        <h2>💻 Teknoloji Yığınım</h2>
        <div class="badges">
            <span class="badge">JavaScript</span>
            <span class="badge">TypeScript</span>
            <span class="badge">React</span>
            <span class="badge">Node.js</span>
            <span class="badge">Python</span>
            <span class="badge">PostgreSQL</span>
            <span class="badge">MongoDB</span>
            <span class="badge">Docker</span>
            <span class="badge">AWS</span>
        </div>

        <h2>📊 GitHub İstatistiklerim</h2>
        <div class="stats">
            <div class="stat-item">
                <h3>Toplam Katkı</h3>
                <p>1,234</p>
            </div>
            <div class="stat-item">
                <h3>Toplam Repolar</h3>
                <p>47</p>
            </div>
            <div class="stat-item">
                <h3>Takipçiler</h3>
                <p>89</p>
            </div>
        </div>

        <h2>🌟 Öne Çıkan Projeler</h2>
        <div class="projects">
            <ul class="project-list">
                <li>
                    <strong><a href="#" style="color: #58a6ff;">E-Ticaret Platformu</a></strong> - React, Node.js ve MongoDB kullanarak geliştirdiğim tam stack e-ticet uygulaması
                </li>
                <li>
                    <strong><a href="#" style="color: #58a6ff;">Task Management App</a></strong> - TypeScript ve React ile geliştirdiğim görev yönetim uygulaması
                </li>
                <li>
                    <strong><a href="#" style="color: #58a6ff;">AI Blog Yazma Aracı</a></strong> - Python ve OpenAI API kullanarak geliştirdiğim blog yazma asistansı
                </li>
            </ul>
        </div>

        <h2>📫 Bana Ulaşın</h2>
        <div class="contact-links">
            <a href="#" class="contact-link">LinkedIn</a>
            <a href="#" class="contact-link">Twitter</a>
            <a href="#" class="contact-link">Email</a>
            <a href="#" class="contact-link">Kişisel Website</a>
        </div>
    </div>
</body>
</html>
