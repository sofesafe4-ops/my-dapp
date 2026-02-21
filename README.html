<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>البحث الشامل</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        :root {
            --bg: #0f0f0f;
            --card: #1e1e1e;
            --text: #e0e0e0;
            --primary: #3b82f6;
            --google: #4285F4;
            --duck: #de5833;
            --hittv: #e50914;
            --cinemana: #f5c518;
        }
        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .header {
            text-align: center;
            margin-bottom: 20px;
        }
        .search-box {
            width: 100%;
            max-width: 400px;
            position: relative;
            margin-bottom: 20px;
        }
        input {
            width: 100%;
            padding: 15px;
            border-radius: 12px;
            border: 1px solid #333;
            background: #252525;
            color: white;
            font-size: 16px;
            box-sizing: border-box;
            outline: none;
            transition: 0.3s;
        }
        input:focus {
            border-color: var(--primary);
            box-shadow: 0 0 10px rgba(59, 130, 246, 0.3);
        }
        .engines-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            width: 100%;
            max-width: 400px;
        }
        .engine-card {
            background: var(--card);
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            cursor: pointer;
            transition: transform 0.1s;
            border: 1px solid #333;
            text-decoration: none;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 80px;
        }
        .engine-card:active {
            transform: scale(0.95);
            background: #333;
        }
        .icon { font-size: 24px; margin-bottom: 5px; }
        .name { font-size: 14px; font-weight: bold; }
        
        /* ألوان الأزرار */
        .btn-google { border-bottom: 3px solid var(--google); }
        .btn-duck { border-bottom: 3px solid var(--duck); }
        .btn-hittv { border-bottom: 3px solid var(--hittv); }
        .btn-cinemana { border-bottom: 3px solid var(--cinemana); }

        .status {
            margin-top: 20px;
            font-size: 12px;
            color: #666;
        }
    </style>
</head>
<body>

    <div class="header">
        <h2>🔍 محرك البحث الموحد</h2>
        <p style="font-size: 12px; color: #888;">ابحث مرة واحدة في كل المواقع</p>
    </div>

    <div class="search-box">
        <input type="text" id="query" placeholder="اكتب اسم الفيلم أو المسلسل..." onkeypress="handleEnter(event)">
    </div>

    <div class="engines-grid">
        <!-- Google -->
        <a href="#" onclick="search('google')" class="engine-card btn-google">
            <span class="icon">🌐</span>
            <span class="name">Google</span>
        </a>
        
        <!-- DuckDuckGo -->
        <a href="#" onclick="search('duck')" class="engine-card btn-duck">
            <span class="icon">🦆</span>
            <span class="name">DuckDuckGo</span>
        </a>

        <!-- Hittv -->
        <a href="#" onclick="search('hittv')" class="engine-card btn-hittv">
            <span class="icon">🎬</span>
            <span class="name">Hittv</span>
        </a>

        <!-- Cinemana -->
        <a href="#" onclick="search('cinemana')" class="engine-card btn-cinemana">
            <span class="icon">🍿</span>
            <span class="name">Cinemana</span>
        </a>
    </div>

    <div class="status" id="statusMsg">جاهز للبحث...</div>

    <script>
        const tg = window.Telegram.WebApp;
        tg.expand();
        tg.ready();

        // دالة التعامل مع زر Enter
        function handleEnter(e) {
            if (e.key === 'Enter') {
                // عند الضغط على انتر، نبحث في جوجل افتراضياً أو نفتح القائمة
                search('google');
            }
        }

        // دالة البحث الرئيسية
        function search(engine) {
            const query = document.getElementById('query').value.trim();
            const status = document.getElementById('statusMsg');

            if (!query) {
                status.innerText = "⚠️ يرجى كتابة اسم الفيلم أولاً";
                status.style.color = "#e50914";
                return;
            }

            status.innerText = "جاري التوجيه...";
            status.style.color = "#666";

            let url = '';
            const encodedQuery = encodeURIComponent(query);

            switch(engine) {
                case 'google':
                    // بحث عام في جوجل
                    url = `https://www.google.com/search?q=${encodedQuery}+film`;
                    break;
                case 'duck':
                    // بحث خاص في دوك دوك جو
                    url = `https://duckduckgo.com/?q=${encodedQuery}+film`;
                    break;
                case 'hittv':
                    // رابط بحث هيت تي في (قد يتغير الرابط حسب تحديث الموقع)
                    // ملاحظة: بعض مواقع الأفلام تغلق البحث المباشر، هذا الرابط افتراضي
                    url = `https://hittv.to/search/${encodedQuery}`; 
                    break;
                case 'cinemana':
                    // رابط بحث سينمانا
                    url = `https://cinemana.co/search/${encodedQuery}`;
                    break;
            }

            // فتح الرابط في متصفح تليجرام الداخلي أو الخارجي
            tg.openLink(url);
        }
    </script>
</body>
</html>
