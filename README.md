<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XCX & KYZX - 魔法般的相遇</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #333;
            overflow-x: hidden;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background: white;
            border-radius: 50%;
            animation: twinkle 3s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 1; }
        }

        .container {
            position: relative;
            z-index: 2;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            text-align: center;
            margin-bottom: 50px;
            padding: 40px 20px;
        }

        .main-title {
            font-size: 3.5em;
            color: white;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            font-weight: 300;
            letter-spacing: 3px;
        }

        .subtitle {
            font-size: 1.3em;
            color: rgba(255,255,255,0.9);
            font-style: italic;
            margin-bottom: 10px;
        }

        .names {
            font-size: 2em;
            color: #fff;
            margin-top: 20px;
            letter-spacing: 2px;
        }

        .photo-section {
            background: rgba(255,255,255,0.95);
            border-radius: 20px;
            padding: 40px;
            margin: 40px 0;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
            backdrop-filter: blur(10px);
        }

        .photo-container {
            text-align: center;
            position: relative;
        }

        .main-photo {
            max-width: 100%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }

        .main-photo:hover {
            transform: scale(1.02);
        }

        .photo-caption {
            margin-top: 20px;
            font-size: 1.1em;
            color: #666;
            font-style: italic;
            line-height: 1.6;
        }

        .story-section {
            background: rgba(255,255,255,0.9);
            border-radius: 20px;
            padding: 40px;
            margin: 40px 0;
            box-shadow: 0 15px 35px rgba(0,0,0,0.15);
        }

        .story-title {
            font-size: 2.2em;
            color: #4a5568;
            margin-bottom: 25px;
            text-align: center;
            position: relative;
        }

        .story-title::after {
            content: '';
            display: block;
            width: 100px;
            height: 3px;
            background: linear-gradient(90deg, #667eea, #764ba2);
            margin: 15px auto;
            border-radius: 2px;
        }

        .story-text {
            font-size: 1.2em;
            line-height: 1.8;
            color: #555;
            text-align: center;
            margin-bottom: 30px;
        }

        .magic-elements {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin: 40px 0;
            flex-wrap: wrap;
        }

        .magic-card {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            min-width: 200px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            transform: translateY(0);
            transition: transform 0.3s ease;
        }

        .magic-card:hover {
            transform: translateY(-10px);
        }

        .magic-icon {
            font-size: 3em;
            margin-bottom: 15px;
            display: block;
        }

        .magic-text {
            font-size: 1.1em;
            font-weight: 500;
        }

        .hearts {
            position: absolute;
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-20px) rotate(180deg); }
        }

        .footer {
            text-align: center;
            padding: 40px 20px;
            color: rgba(255,255,255,0.8);
            font-size: 1.1em;
        }

        .date {
            background: rgba(255,255,255,0.2);
            padding: 15px 30px;
            border-radius: 25px;
            display: inline-block;
            margin: 20px 0;
            backdrop-filter: blur(10px);
        }

        @media (max-width: 768px) {
            .main-title {
                font-size: 2.5em;
            }
            
            .photo-section, .story-section {
                padding: 25px;
                margin: 20px 0;
            }
            
            .magic-elements {
                gap: 20px;
            }
            
            .magic-card {
                min-width: 150px;
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    
    <div class="container">
        <header class="header">
            <h1 class="main-title">魔法般的相遇</h1>
            <p class="subtitle">当魔术师遇见了他的观众</p>
            <div class="names">XCX ❤️ KYZX</div>
        </header>

        <section class="photo-section">
            <div class="photo-container">
                <!-- 这里是修正过的地方 -->
                <img src="https://i.postimg.cc/44PwZ65Z/Screenshot-2025-06-12-23-57-07-598-com-miui-gallery-edit.jpg" class="main-photo" alt="KYZX performing magic" />
                <p class="photo-caption">
                    "这一刻，你正在台上施展魔法<br>
                    而我在台下，不知不觉被你深深吸引<br>
                    那时的我们还不知道，这就是我们爱情故事的开始"
                </p>
            </div>
        </section>

        <section class="story-section">
            <h2 class="story-title">我们的故事</h2>
            <p class="story-text">
                在那个特别的夜晚，你站在台上，身着西装，展示着魔术技艺。<br>
                我坐在台下，被你的每一个动作深深吸引。<br>
                当你邀请我配合表演时，我的心跳得好快。<br>
                那一刻，我们的目光相遇，仿佛有魔法在空中飞舞。<br><br>
                你不知道，你施展的最大魔法，就是让我爱上了你。
            </p>

            <div class="magic-elements">
                <div class="magic-card">
                    <span class="magic-icon">🃏</span>
                    <p class="magic-text">神奇的扑克牌<br>变出了奇迹</p>
                </div>
                <div class="magic-card">
                    <span class="magic-icon">✨</span>
                    <p class="magic-text">闪耀的魔法<br>点亮了我的心</p>
                </div>
                <div class="magic-card">
                    <span class="magic-icon">💕</span>
                    <p class="magic-text">最美的魔术<br>是我们的相遇</p>
                </div>
            </div>
        </section>

        <footer class="footer">
            <div class="date">
                纪念我们的第一次相遇
            </div>
            <p>愿我们的爱情像魔法一样，永远充满惊喜与美好 ✨</p>
        </footer>
    </div>

    <script>
        // 创建星星效果
        function createStars() {
            const starsContainer = document.getElementById('stars');
            const numberOfStars = 100;

            for (let i = 0; i < numberOfStars; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                star.style.animationDelay = Math.random() * 3 + 's';
                starsContainer.appendChild(star);
            }
        }

        // 创建浮动爱心
        function createFloatingHearts() {
            setInterval(() => {
                const heart = document.createElement('div');
                heart.innerHTML = '💖';
                heart.className = 'hearts';
                heart.style.left = Math.random() * 100 + '%';
                heart.style.top = '100%';
                heart.style.fontSize = Math.random() * 20 + 15 + 'px';
                heart.style.animationDuration = Math.random() * 3 + 4 + 's';
                document.body.appendChild(heart);

                setTimeout(() => {
                    heart.remove();
                }, 7000);
            }, 3000);
        }

        // 初始化
        window.addEventListener('load', () => {
            createStars();
            createFloatingHearts();
        });

        // 添加平滑滚动效果
        document.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const parallax = document.querySelector('.stars');
            // 确保 parallax 元素存在时再操作
            if (parallax) {
                const speed = scrolled * 0.5;
                parallax.style.transform = `translateY(${speed}px)`;
            }
        });
    </script>
</body>
</html>
