<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Top Up Game Murah & Resmi | Zeen Market</title>
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-main: linear-gradient(135deg, #f5f7fa 0%, #c9e7ff 100%);
            --container-bg: #fff;
            --brand-logo-bg: #e1f2ff;
            --brand-title: #2196f3;
            --brand-shadow: #c9e7ff55;
            --header-title: #184b8b;
            --header-subtitle: #5e81ac;
            --search-border: #b7dbfa;
            --search-bg: #f1f8fd;
            --search-color: #2196f3;
            --search-focus-bg: #e3f2fd;
            --search-focus-border: #2196f3;
            --category-bg: #e0f2fe;
            --category-color: #2196f3;
            --category-border: #b7dbfa;
            --category-active-bg: linear-gradient(90deg, #38b6ff 20%, #7ee8fa 100%);
            --category-active-color: #fff;
            --category-active-border: #38b6ff;
            --banner-shadow: #b6e5ff88;
            --game-bg: #e3f3ff;
            --game-border: #b7dbfa;
            --game-hover-bg: #fff;
            --game-title: #184b8b;
            --btn-bg: linear-gradient(90deg,#38b6ff 20%, #7ee8fa 100%);
            --btn-color: #fff;
            --btn-hover-bg: linear-gradient(90deg,#2196f3 10%, #7ee8fa 90%);
            --btn-hover-color: #184b8b;
            --scrollbar-bg: #b7dbfa;
            --opsi-btn-bg: linear-gradient(90deg,#38b6ff 20%, #7ee8fa 100%);
            --opsi-btn-color: #fff;
            --opsi-btn-hover-bg: linear-gradient(90deg,#2196f3 10%, #7ee8fa 90%);
            --opsi-btn-hover-color: #184b8b;
        }
        html, body {
            height: 100%;
        }
        body {
            font-family: 'Poppins', Arial, sans-serif;
            background: var(--bg-main);
            margin: 0; min-height: 100vh; padding: 0;
            transition: background 0.3s;
        }
        .container {
            width: 100%;
            max-width: 1100px;
            margin: 38px auto 0 auto;
            padding: 28px 16px 36px;
            border-radius: 26px;
            background: var(--container-bg);
            box-shadow: 0 4px 28px 0 #b6d6ff40;
            transition: background 0.3s;
        }
        .brand-header {
            display: flex;
            align-items: center;
            gap: 16px;
            margin-bottom: 26px;
            flex-wrap: wrap;
            justify-content: flex-start;
        }
        .brand-logo {
            width: 44px; height: 44px;
            border-radius: 10px;
            background: var(--brand-logo-bg);
            display: flex; align-items: center; justify-content: center;
            box-shadow: 0 2px 10px #b6e5ff33;
        }
        .brand-logo img {
            width: 32px; height: 32px;
            display: block;
        }
        .brand-title {
            font-size: 1.35em;
            font-weight: 700;
            letter-spacing: 1.5px;
            color: var(--brand-title);
            text-shadow: 0 2px 12px var(--brand-shadow);
            margin-right: 8px;
        }
        .brand-actions {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-left: auto;
            flex-wrap: wrap;
        }
        .search-box {
            flex: 0 1 220px;
            max-width: 240px;
            min-width: 140px;
            margin-left: 24px;
            position: relative;
        }
        .search-box input {
            padding: 11px 38px 11px 15px;
            font-size: 1em;
            border-radius: 10px;
            border: 1.5px solid var(--search-border);
            background: var(--search-bg);
            color: var(--search-color);
            outline: none;
            transition: border .2s, box-shadow .2s, background 0.3s, color 0.3s;
            width: 100%;
            box-sizing: border-box;
        }
        .search-box input:focus {
            border: 1.5px solid var(--search-focus-border);
            background: var(--search-focus-bg);
        }
        .search-box .icon {
            position: absolute;
            right: 12px; top: 12px;
            color: var(--search-focus-border);
            font-size: 1.2em;
            pointer-events: none;
            transition: color 0.3s;
        }
        .btn-jual-akun, .btn-joki-akun {
            display: inline-block;
            margin-left: 0;
            padding: 9px 20px;
            border-radius: 18px;
            background: var(--opsi-btn-bg);
            color: var(--opsi-btn-color);
            font-size: 1em;
            font-weight: 600;
            border: none;
            box-shadow: 0 2px 8px #b6e5ff44;
            text-decoration: none;
            transition: background 0.19s, box-shadow 0.15s, color 0.12s, transform 0.16s;
        }
        .btn-jual-akun:hover, .btn-jual-akun:focus,
        .btn-joki-akun:hover, .btn-joki-akun:focus {
            background: var(--opsi-btn-hover-bg);
            color: var(--opsi-btn-hover-color);
            box-shadow: 0 4px 14px #38b6ffbb;
            transform: scale(1.07);
        }
        .header-row {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 18px;
        }
        .header-title {
            font-size: 2.1em;
            color: var(--header-title);
            font-weight: 700;
            letter-spacing: 1.5px;
            margin: 0 0 4px 0;
            transition: color 0.3s;
        }
        .header-subtitle {
            color: var(--header-subtitle);
            font-size: 1em;
            font-weight: 500;
            margin-bottom: 10px;
            transition: color 0.3s;
        }
        .category-bar {
            display: flex;
            gap: 10px;
            margin: 0 0 28px 0;
            flex-wrap: wrap;
        }
        .category-btn {
            background: var(--category-bg);
            color: var(--category-color);
            font-weight: 500;
            border-radius: 18px;
            border: 1.5px solid var(--category-border);
            padding: 7px 22px 7px 22px;
            cursor: pointer;
            transition: background 0.18s, border 0.18s, color 0.18s;
            font-size: 1em;
        }
        .category-btn.active,
        .category-btn:hover {
            background: var(--category-active-bg);
            color: var(--category-active-color);
            border: 1.5px solid var(--category-active-border);
        }
        /* Banner */
        .banner-wrapper {
            width: 100%;
            position: relative;
            margin-bottom: 18px;
            overflow: hidden;
            height: 380px;
        }
        .banner-img {
            width: 100%;
            height: 100%;
            border-radius: 16px;
            object-fit: cover;
            min-height: 120px;
            box-shadow: 0 4px 18px var(--banner-shadow);
            position: absolute;
            top: 0; left: 0;
            opacity: 0;
            transition: opacity 0.45s, transform 0.7s;
            transform: translateX(100%);
            z-index: 1;
        }
        .banner-img.active {
            opacity: 1;
            z-index: 2;
            transform: translateX(0);
            transition: opacity 0.45s, transform 0.7s;
        }
        .banner-img.prev {
            opacity: 0;
            z-index: 1;
            transform: translateX(-100%);
            transition: opacity 0.45s, transform 0.7s;
        }
        .banner-dots {
            width: 100%;
            display: flex;
            justify-content: center;
            gap: 8px;
            margin-top: 24px;
            margin-bottom: 18px;
            z-index: 10;
            pointer-events: auto;
            position: static;
        }
        .banner-dot {
            width: 10px;
            height: 10px;
            background: #fff7;
            border: 2px solid #38b6ff;
            border-radius: 50%;
            cursor: pointer;
            transition: background 0.2s, border 0.2s;
        }
        .banner-dot.active {
            background: #38b6ff;
            border-color: #2196f3;
        }
        .game-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
            gap: 26px 18px;
        }
        .game-card {
            background: var(--game-bg);
            border-radius: 13px;
            box-shadow: 0 2px 10px #b6e5ff33;
            padding: 24px 10px 21px;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: box-shadow 0.17s, transform 0.18s, background 0.3s, color 0.3s, border 0.3s;
            cursor: pointer;
            border: 1.7px solid var(--game-border);
            position: relative;
        }
        .game-card:hover, .game-card:focus {
            box-shadow: 0 8px 28px #38b6ff33, 0 1.5px 8px #b6e5ff44;
            border: 1.7px solid #38b6ff;
            transform: translateY(-5px) scale(1.04);
            background: var(--game-hover-bg);
        }
        .game-card img {
            width: 68px;
            height: 68px;
            object-fit: contain;
            margin-bottom: 13px;
            border-radius: 11px;
            background: #f8fbff;
            box-shadow: 0 2px 14px #b6e5ff29;
            border: 1.5px solid var(--game-border);
            transition: border 0.3s, background 0.3s;
        }
        .game-card span {
            color: var(--game-title);
            font-size: 1.09em;
            font-weight: 600;
            margin-bottom: 13px;
            letter-spacing: 0.2px;
            transition: color 0.3s;
        }
        .btn-topup {
            padding: 8px 26px;
            border-radius: 18px;
            background: var(--btn-bg);
            color: var(--btn-color);
            font-size: 1em;
            font-weight: 600;
            border: none;
            box-shadow: 0 2px 8px #b6e5ff44;
            transition: background 0.19s, box-shadow 0.15s, color 0.12s, transform 0.16s;
            cursor: pointer;
        }
        .btn-topup:hover, .btn-topup:focus {
            background: var(--btn-hover-bg);
            color: var(--btn-hover-color);
            box-shadow: 0 4px 14px #38b6ffbb;
            transform: scale(1.07);
        }
        ::-webkit-scrollbar {
            width: 10px;
            background: var(--scrollbar-bg);
        }
        ::-webkit-scrollbar-thumb {
            background: #a0cafc;
            border-radius: 6px;
        }
        /* RESPONSIVE: HP dan PC SAMA (grid, font, padding menyesuaikan, tidak berubah urutan/layout) */
        @media (max-width: 1200px) {
            .container {
                max-width: 100vw;
            }
            .brand-header {
                flex-wrap: wrap;
            }
        }
        @media (max-width: 900px) {
            .container {
                max-width: 100vw;
                padding: 18px 1vw 18px;
            }
            .brand-header {
                flex-wrap: wrap;
                gap: 10px;
            }
            .game-list {
                grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
                gap: 18px 8px;
            }
        }
        @media (max-width: 700px) {
            .container {padding: 10px 0 10px;}
            .brand-header {
                flex-direction: row;
                align-items: center;
                gap: 7px 0;
            }
            .brand-actions {
                flex-direction: row;
                align-items: center;
                gap: 7px 0;
                margin-left: auto;
                width: auto;
            }
            .search-box {
                margin-left: 0;
                min-width: 120px;
                width: 100%;
                max-width: 100%;
            }
            .btn-jual-akun, .btn-joki-akun {
                margin-left: 0;
                margin-top: 0;
                width: auto;
                text-align: center;
            }
            .brand-title {font-size: 1.05em;}
            .header-title { font-size: 1.15em;}
            .banner-wrapper {height: 200px;}
            .banner-dots {margin-top: 10px; margin-bottom: 10px;}
            .header-row {flex-direction: row; align-items: center;}
            .game-list {gap: 15px 7px;}
            .game-card {padding: 14px 2px 16px;}
        }
        @media (max-width: 520px) {
            .container {
                border-radius: 0;
                margin: 0;
                padding: 2vw 0 2vw;
                min-width: 100vw;
                max-width: 100vw;
            }
            .banner-wrapper {height: 120px;}
            .brand-header {gap: 4px;}
            .brand-title {font-size: .97em;}
            .header-title {font-size: 1em;}
            .category-bar {gap: 4px;}
            .game-list {gap: 7px 3px;}
            .game-card {padding: 6px 0 11px;}
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- BRAND HEADER, ZEEN MARKET + SEARCH BOX + JUAL AKUN + JOKI AKUN + LAINNYA -->
        <div class="brand-header">
            <div class="brand-logo">
                <img src="https://img.icons8.com/color/96/shop--v1.png" alt="Zeen Market">
            </div>
            <span class="brand-title">Zeen Market</span>
            <div class="brand-actions">
                <div class="search-box">
                    <input type="text" id="searchInput" placeholder="Cari game...">
                    <span class="icon">&#128269;</span>
                </div>
                <a href="https://wa.me/6282328581304" target="_blank" class="btn-jual-akun">Jual Akun</a>
                <a href="https://wa.me/6282328581304" target="_blank" class="btn-joki-akun">Joki</a>
                <a href="https://wa.me/6282328581304" target="_blank" class="btn-joki-akun">Lainnya</a>
            </div>
        </div>
        <div class="header-row">
            <div>
                <div class="header-title">Top Up Game Resmi, Murah & Cepat</div>
                <div class="header-subtitle">Pilih game kesayanganmu dan lakukan top up dengan aman & mudah!</div>
            </div>
        </div>
        <div class="category-bar" id="categoryBar">
            <button class="category-btn active" data-category="all">Semua</button>
            <button class="category-btn" data-category="populer">Akun Mlbb</button>
            <button class="category-btn" data-category="mlbb">Akun Free Fire</button>
            <button class="category-btn" data-category="ff">Free Fire</button>
        </div>
        <!-- Banner Slider -->
        <div class="banner-wrapper" id="bannerWrapper">
            <img src="baner.png" alt="banner top up" class="banner-img active" id="bannerImg0">
            <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80" alt="banner 2" class="banner-img" id="bannerImg1">
            <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=800&q=80" alt="banner 3" class="banner-img" id="bannerImg2">
        </div>
        <!-- Titik 3 (dots) di bawah gambar/banner -->
        <div class="banner-dots" id="bannerDots"></div>
        <div class="game-list" id="gameList">
            <div class="game-card" data-title="Mobile Legends" data-category="populer mlbb">
                <img src="ml.png" alt="Mobile Legends">
                <span>Mobile Legends</span>
                <button class="btn-topup" onclick="window.location.href='ml.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Free Fire" data-category="populer ff">
                <img src="ff.png" alt="Free Fire">
                <span>Free Fire</span>
                <button class="btn-topup" onclick="window.location.href='topup-ff.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="PUBG Mobile" data-category="populer pubgm">
                <img src="pupg.png" alt="PUBG Mobile">
                <span>PUBG Mobile</span>
                <button class="btn-topup" onclick="window.location.href='topup-pubgm.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Valorant" data-category="valorant">
                <img src="valo.png" alt="Valorant">
                <span>Valorant</span>
                <button class="btn-topup" onclick="window.location.href='topup-valorant.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Genshin Impact" data-category="genshin">
                <img src="gi.png" alt="Genshin Impact">
                <span>Genshin Impact</span>
                <button class="btn-topup" onclick="window.location.href='topup-genshin.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Call of Duty Mobile" data-category="codm">
                <img src="cod.png" alt="Call of Duty Mobile">
                <span>Call of Duty Mobile</span>
                <button class="btn-topup" onclick="window.location.href='topup-codm.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Honkai: Star Rail" data-category="honkai">
                <img src="hsr.png" alt="Honkai: Star Rail">
                <span>Honkai: Star Rail</span>
                <button class="btn-topup" onclick="window.location.href='topup-hsr.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Arena of Valor" data-category="aov">
                <img src="zzz.png" alt="Arena of Valor">
                <span>Zenless Zone Zero</span>
                <button class="btn-topup" onclick="window.location.href='zzz.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Point Blank" data-category="pb">
                <img src="pb.png" alt="Point Blank">
                <span>Point Blank</span>
                <button class="btn-topup" onclick="window.location.href='topup-pb.html'">Top Up</button>
            </div>
            <div class="game-card" data-title="Clash of Clans" data-category="coc">
                <img src="wuwa.png" alt="Clash of Clans">
                <span>Wuthering Waves</span>
                <button class="btn-topup" onclick="window.location.href='topup-coc.html'">Top Up</button>
            </div>
        </div>
    </div>
    <script>
        // Banner Slider Otomatis dengan Animasi Geser
        const bannerImgs = document.querySelectorAll('.banner-img');
        const bannerDotsContainer = document.getElementById('bannerDots');
        let currentBanner = 0;
        let bannerTimer = null;
        const bannerCount = bannerImgs.length;

        // Generate dots
        for(let i=0; i<bannerCount; i++) {
            const dot = document.createElement('div');
            dot.className = 'banner-dot' + (i === 0 ? ' active':'');
            dot.dataset.index = i;
            dot.addEventListener('click', () => showBanner(i, true));
            bannerDotsContainer.appendChild(dot);
        }
        function showBanner(idx, manual=false) {
            if(idx === currentBanner) return;
            bannerImgs[currentBanner].classList.remove('active');
            bannerImgs[currentBanner].classList.remove('prev');
            bannerImgs[idx].classList.add('active');
            bannerImgs[idx].classList.remove('prev');
            // animasi keluar kiri untuk prev
            bannerImgs[currentBanner].classList.add('prev');
            // Dots
            document.querySelectorAll('.banner-dot').forEach((d, i)=>{
                d.classList.toggle('active', i === idx);
            });
            currentBanner = idx;
            if(manual) {
                resetBannerTimer();
            }
        }
        function nextBanner() {
            let next = (currentBanner+1) % bannerCount;
            showBanner(next);
        }
        function resetBannerTimer() {
            if(bannerTimer) clearInterval(bannerTimer);
            bannerTimer = setInterval(nextBanner, 3400);
        }
        // Inisialisasi
        resetBannerTimer();

        // Pastikan animasi geser kembali ke kanan jika kembali ke banner pertama
        bannerImgs.forEach(img => {
            img.addEventListener('transitionend', () => {
                bannerImgs.forEach((im, idx) => {
                    if(idx !== currentBanner) {
                        im.classList.remove('active');
                        im.classList.remove('prev');
                    }
                });
            });
        });

        // Filter kategori
        const categoryBar = document.getElementById('categoryBar');
        const categoryBtns = categoryBar.querySelectorAll('.category-btn');
        const gameList = document.getElementById('gameList');
        const cards = gameList.querySelectorAll('.game-card');
        const bannerWrapper = document.getElementById('bannerWrapper');

        categoryBar.addEventListener('click', function(e){
            if (!e.target.classList.contains('category-btn')) return;
            categoryBtns.forEach(btn=>btn.classList.remove('active'));
            e.target.classList.add('active');
            const cat = e.target.getAttribute('data-category');
            cards.forEach(card=>{
                if(cat === 'all' || card.getAttribute('data-category').includes(cat)){
                    card.style.display = "";
                }else{
                    card.style.display = "none";
                }
            });
            // Banner hanya muncul di "Semua"
            if (bannerWrapper) {
                bannerWrapper.style.display = (cat === 'all') ? '' : 'none';
            }
        });

        // Live search
        const searchInput = document.getElementById('searchInput');
        searchInput.addEventListener('input', function() {
            const filter = searchInput.value.toLowerCase();
            cards.forEach(card => {
                const title = card.getAttribute('data-title').toLowerCase();
                if(title.includes(filter)){
                    card.style.display = "";
                }else{
                    card.style.display = "none";
                }
            });
        });
    </script>
</body>
</html>
