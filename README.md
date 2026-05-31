<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NIGHTMARE | Community Rules</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,600;14..32,700;14..32,800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: radial-gradient(circle at 20% 30%, #0a0a0f, #030305);
            font-family: 'Inter', sans-serif;
            padding: 40px 20px;
            color: #e0e0e0;
        }

        /* Основной контейнер */
        .rules-container {
            max-width: 1200px;
            margin: 0 auto;
        }

        /* ХЕДЕР с заголовком */
        .header {
            text-align: center;
            margin-bottom: 60px;
            position: relative;
        }

        .glitch {
            font-size: 4rem;
            font-weight: 800;
            text-transform: uppercase;
            background: linear-gradient(135deg, #ff3a3a, #9b1d1d, #2a0050);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: 6px;
            text-shadow: 0 0 15px rgba(255, 0, 0, 0.5);
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { opacity: 0.9; text-shadow: 0 0 5px red; }
            100% { opacity: 1; text-shadow: 0 0 25px #ff4444; }
        }

        .sub {
            font-size: 0.85rem;
            letter-spacing: 3px;
            color: #8a8a9c;
            margin-top: 10px;
            border-top: 1px solid rgba(255, 50, 50, 0.4);
            display: inline-block;
            padding-top: 12px;
        }

        /* Сетка карточек */
        .rules-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
            gap: 28px;
            margin-bottom: 50px;
        }

        /* Карточка правила */
        .rule-card {
            background: rgba(15, 15, 22, 0.75);
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 70, 70, 0.25);
            border-radius: 28px;
            padding: 28px 30px;
            transition: all 0.3s ease;
            box-shadow: 0 12px 28px -10px rgba(0, 0, 0, 0.6);
        }

        .rule-card:hover {
            border-color: #ff3a3a;
            box-shadow: 0 20px 35px -12px rgba(255, 0, 0, 0.25);
            transform: translateY(-3px);
            background: rgba(20, 20, 30, 0.85);
        }

        .card-header {
            display: flex;
            align-items: center;
            gap: 14px;
            margin-bottom: 20px;
            border-bottom: 1px solid rgba(255, 70, 70, 0.4);
            padding-bottom: 12px;
        }

        .card-icon {
            font-size: 2rem;
            filter: drop-shadow(0 0 4px #ff4444);
        }

        .card-title {
            font-size: 1.5rem;
            font-weight: 700;
            letter-spacing: -0.3px;
            background: linear-gradient(135deg, #ffffff, #ff8888);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        .rule-list {
            list-style: none;
            padding-left: 8px;
        }

        .rule-list li {
            margin-bottom: 14px;
            padding-left: 24px;
            position: relative;
            line-height: 1.45;
            font-size: 0.95rem;
            color: #cdcddd;
        }

        .rule-list li::before {
            content: "▸";
            position: absolute;
            left: 0;
            color: #ff5e5e;
            font-weight: bold;
            text-shadow: 0 0 4px red;
        }

        .badge {
            display: inline-block;
            background: rgba(255, 50, 50, 0.25);
            border-left: 3px solid #ff3a3a;
            padding: 2px 10px;
            font-family: 'JetBrains Mono', monospace;
            font-size: 0.75rem;
            font-weight: 500;
            color: #ffaaaa;
            margin-top: 4px;
        }

        .warning-card {
            border-left: 4px solid #ff0000;
            background: linear-gradient(95deg, rgba(30, 10, 10, 0.7), rgba(15, 15, 22, 0.7));
            backdrop-filter: blur(8px);
        }

        .footer-note {
            text-align: center;
            margin-top: 50px;
            padding: 24px;
            background: rgba(0, 0, 0, 0.55);
            border-radius: 60px;
            font-size: 0.8rem;
            color: #8f8fa8;
            border: 1px solid rgba(255, 80, 80, 0.2);
            font-family: 'JetBrains Mono', monospace;
        }

        hr {
            border-color: #ff3a3a30;
            margin: 10px 0;
        }

        @media (max-width: 700px) {
            .rules-grid {
                grid-template-columns: 1fr;
            }
            .glitch {
                font-size: 2rem;
                letter-spacing: 2px;
            }
            .rule-card {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
<div class="rules-container">
    <div class="header">
        <div class="glitch">◄ ◄ COMMUNITY RULES NIGHTMARE ► 🛡️</div>
        <div class="sub">• CODEX OF DARKNESS •</div>
    </div>

    <div class="rules-grid">
        
        <!-- I. ПРАВИЛА СООБЩЕСТВА -->
        <div class="rule-card">
            <div class="card-header">
                <span class="card-icon">⚔️</span>
                <span class="card-title">I. ПРАВИЛА СООБЩЕСТВА</span>
            </div>
            <ul class="rule-list">
                <li><strong>1.1 Этикет:</strong> ПРОВОКАЦИИ / ТОКСИЧНОСТЬ / ОСКОРБЛЕНИЯ — <span style="color:#ff7777">ЗАПРЕЩЕНЫ</span>.</li>
                <li><strong>1.2 Контент:</strong> NSFW, шок-контент, оскорбление политических взглядов, призывы к суициду — <span style="color:#ff7777">ЗАПРЕЩЕНЫ</span>.</li>
                <li><strong>1.3 Порядок:</strong> Спам, флуд, бессмысленные сообщения запрещены.</li>
                <li><strong>1.4 Пинги:</strong> Не упоминайте (пинг) администрацию без веской причины.</li>
                <li><strong>1.5 Профиль:</strong> Реклама, оскорбления или 18+ контент в профиле запрещены.</li>
                <li><strong>1.6 Безопасность:</strong> Деанон (личные данные) или скам-ссылки = мгновенный бан.</li>
                <li><strong>1.7 Реклама:</strong> Сторонние проекты / серверы запрещены без согласования.</li>
                <li><strong>⛔ 1.8 Выдача за персонал:</strong> Запрещено выдавать себя за администрацию, подделывать никнеймы / аватарки.</li>
            </ul>
            <div class="badge">⛔ Абсолютный запрет</div>
        </div>

        <!-- II. ТЕХНИЧЕСКИЙ РЕГЛАМЕНТ & ЛИЦЕНЗИЯ -->
        <div class="rule-card warning-card">
            <div class="card-header">
                <span class="card-icon">💀</span>
                <span class="card-title">II. ТЕХНИЧЕСКИЙ РЕГЛАМЕНТ</span>
            </div>
            <ul class="rule-list">
                <li><strong>2.1 ЗАПРЕТ НА ПО:</strong> Категорически запрещено ХРАНЕНИЕ/НАЛИЧИЕ на ПК:
                    <br>🔻 Снифферы: <em>Wireshark, Mitmproxy, Requestly, Fiddler</em>
                    <br>🔻 Декомпиляторы: <em>dnSpy, ILSpy, dotPeek, OllyDbg, IDA Pro</em>
                    <br><span style="color:#ff9b6e">Попытки перехвата запросов = перманентный бан</span>
                </li>
                <li><strong>2.2 Наказание за софт:</strong> Наличие файлов или следов программ = попытка взлома. Ключ аннулируется без возврата средств.</li>
                <li><strong>2.3 Лицензия:</strong> Один ключ — один пользователь. Передача/перепродажа строго запрещена.</li>
                <li><strong>2.4 Обход бана:</strong> Попытки обхода через мультиаккаунты ведут к бану всех профилей.</li>
            </ul>
            <div class="badge">⚠️ Мгновенная блокировка при нарушении</div>
        </div>
    </div>

    <!-- Доп. блок безопасности -->
    <div class="footer-note">
        ⚡ NIGHTMARE SECURE CORE ⚡<br>
        Любая попытка декомпиляции, сниффинга или обратной разработки приведёт к перманентному аннулированию лицензии.
        <br> <span style="color:#ff6666">〘 Ваши действия логируются 〙</span>
    </div>
</div>
</body>
</html>
