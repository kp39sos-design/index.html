<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover, user-scalable=yes">
    <title>اسرع من نتكم 🔥 | متجر شامل للشحن والخدمات</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Cairo', sans-serif; background: radial-gradient(circle at 10% 20%, #0a0f1e, #03060f); color: #f0f3fa; padding: 1rem; min-height: 100vh; position: relative; }
        body::before { content: ''; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-image: radial-gradient(rgba(255, 200, 100, 0.2) 1.5px, transparent 1.5px); background-size: 45px 45px; pointer-events: none; animation: driftStars 80s linear infinite; z-index: 0; }
        @keyframes driftStars { 0% { background-position: 0 0; } 100% { background-position: 100px 100px; } }
        .container { max-width: 1300px; margin: 0 auto; position: relative; z-index: 2; padding: 0.5rem; }

        /* Premium Glow Effects */
        .premium-text { font-size: 2.8rem; font-weight: 800; background: linear-gradient(135deg, #FFD700, #FFA500, #FFD700); -webkit-background-clip: text; background-clip: text; color: transparent; text-shadow: 0 0 20px rgba(255,215,0,0.5); animation: shimmer 3s infinite; letter-spacing: 4px; }
        @keyframes shimmer { 0% { filter: brightness(1); } 50% { filter: brightness(1.3); } 100% { filter: brightness(1); } }

        .progress-container { position: fixed; top: 0; left: 0; width: 100%; height: 4px; background: rgba(255,180,70,0.2); z-index: 9999; }
        .progress-bar { height: 4px; background: #ffb347; width: 0%; transition: width 0.2s; }
        .scroll-top { position: fixed; bottom: 20px; right: 20px; background: #ffb347; color: #0a0f1e; width: 45px; height: 45px; border-radius: 50%; display: flex; align-items: center; justify-content: center; cursor: pointer; opacity: 0; transition: 0.3s; z-index: 999; border: none; font-size: 1.2rem; }
        .scroll-top.show { opacity: 1; }
        .welcome-message { background: rgba(255,180,70,0.2); border-right: 4px solid #ffb347; border-radius: 1rem; padding: 0.5rem 1rem; margin-bottom: 1rem; text-align: center; font-weight: bold; backdrop-filter: blur(4px); min-height: 65px; }
        .hero { text-align: center; background: rgba(10, 20, 35, 0.65); backdrop-filter: blur(12px); border-radius: 3rem; padding: 1.8rem 1.2rem; margin-bottom: 2rem; border: 1px solid rgba(255, 180, 70, 0.5); box-shadow: 0 20px 35px -12px rgba(0,0,0,0.3); }
        .hero h1 { font-size: 2.3rem; font-weight: 800; background: linear-gradient(125deg, #FFE6B0, #FFB347, #FF7E05); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .brand-name { display: inline-flex; align-items: center; gap: 10px; background: linear-gradient(135deg, #ffb347, #e05a00); padding: 0.4rem 1.4rem; border-radius: 60px; font-weight: 800; margin-top: 0.8rem; color: #0a0f1e; box-shadow: 0 6px 14px rgba(255, 120, 0, 0.4); }
        .countdown { background: rgba(0,0,0,0.5); padding: 0.4rem 1rem; border-radius: 40px; display: inline-flex; gap: 10px; margin: 0.5rem auto 0; font-size: 0.9rem; border: 1px solid #ffb347; }
        .section-switch { display: flex; justify-content: center; gap: 1.2rem; margin: 1.5rem 0 2rem; flex-wrap: wrap; }
        .switch-btn { background: rgba(20, 28, 44, 0.9); border: none; padding: 0.8rem 2rem; border-radius: 60px; font-weight: 800; font-size: 1rem; color: #cbd5f0; cursor: pointer; display: inline-flex; align-items: center; gap: 10px; border: 1px solid #3a4a6e; backdrop-filter: blur(4px); }
        .switch-btn.active { background: linear-gradient(105deg, #FFB347, #FF7E05); color: #0a0f1e; border-color: #FFD966; box-shadow: 0 8px 18px rgba(255, 100, 0, 0.4); }
        .game-tabs, .recharge-tabs, .design-tabs { display: flex; flex-wrap: wrap; justify-content: center; gap: 0.9rem; margin-bottom: 2rem; }
        .tab-btn, .recharge-tab, .design-tab { background: rgba(20, 28, 44, 0.85); border: 1px solid #3e4a6e; padding: 0.7rem 1.6rem; border-radius: 60px; font-weight: 700; font-size: 0.95rem; color: #cbd5f0; cursor: pointer; display: inline-flex; align-items: center; gap: 8px; }
        .tab-btn.active, .recharge-tab.active, .design-tab.active { background: linear-gradient(115deg, #F9A826, #FF7E05); color: #0f0f1a; border-color: #FFC107; box-shadow: 0 5px 12px rgba(255,126,5,0.5); }
        .stats-bar { display: flex; justify-content: center; gap: 1.5rem; margin-bottom: 2rem; flex-wrap: wrap; }
        .stat-card { background: rgba(15, 25, 45, 0.7); backdrop-filter: blur(8px); padding: 0.7rem 1.2rem; border-radius: 2rem; border: 1px solid rgba(255, 180, 70, 0.5); text-align: center; min-width: 120px; }
        .stat-number { font-size: 1.8rem; font-weight: 800; color: #FFC857; }
        .prices-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 1.8rem; margin-bottom: 2rem; }
        .price-card { background: rgba(18, 28, 48, 0.75); backdrop-filter: blur(10px); border-radius: 2rem; padding: 1.4rem; border: 1px solid rgba(255, 190, 70, 0.4); transition: all 0.3s; }
        .price-card:hover { transform: translateY(-8px) scale(1.01); border-color: #FFB347; animation: shake 0.3s ease-in-out; }
        @keyframes shake { 0% { transform: translateX(0); } 25% { transform: translateX(-3px); } 75% { transform: translateX(3px); } 100% { transform: translateX(0); } }
        .price-card.vip-card { background: linear-gradient(135deg, rgba(255, 190, 70, 0.2), rgba(255, 100, 0, 0.15)); border: 2px solid #FFD966; }
        .game-badge { background: linear-gradient(115deg, #FFB34740, #FF7E0540); display: inline-block; padding: 0.2rem 0.8rem; border-radius: 40px; font-size: 0.7rem; font-weight: 700; margin-bottom: 0.7rem; border: 1px solid #ffb34770; }
        .vip-badge { background: linear-gradient(115deg, #FFD966, #FFB347); color: #0a0f1e; border: none; }
        .item-name { font-size: 1.2rem; font-weight: 800; margin: 0.3rem 0; background: linear-gradient(135deg, #f0f3fa, #FFE0A3); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .price-eg { font-size: 1.7rem; font-weight: 800; color: #FFE0A3; margin: 0.6rem 0; }
        .btn-order { background: linear-gradient(105deg, #2d3b5a, #1f2a3e); border: none; width: 100%; padding: 0.7rem; border-radius: 2rem; font-weight: 700; font-family: 'Cairo', sans-serif; font-size: 0.9rem; color: #f0f3fa; cursor: pointer; display: flex; align-items: center; justify-content: center; gap: 0.6rem; margin-top: 0.8rem; border: 1px solid #ffb34780; transition: all 0.25s; }
        .btn-order:hover { background: linear-gradient(105deg, #FF8C1A, #FFB347); color: #0a0f1e; transform: scale(1.02); }
        .btn-order.loading { pointer-events: none; opacity: 0.7; }

        /* تصميم كروت التصميم بدون سعر */
        .design-card { background: rgba(20, 30, 50, 0.8); backdrop-filter: blur(15px); border-radius: 2.5rem; padding: 2rem 1.5rem; border: 1px solid rgba(255, 215, 0, 0.4); transition: all 0.4s ease; text-align: center; position: relative; overflow: hidden; }
        .design-card::before { content: ''; position: absolute; top: -50%; left: -50%; width: 200%; height: 200%; background: radial-gradient(circle, rgba(255,215,0,0.15) 0%, transparent 70%); animation: rotateGlow 10s linear infinite; z-index: 0; }
        @keyframes rotateGlow { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
        .design-card:hover { transform: translateY(-12px) scale(1.03); border-color: #FFD700; box-shadow: 0 20px 40px rgba(255,215,0,0.3); }
        .design-icon { font-size: 4rem; margin-bottom: 1rem; position: relative; z-index: 1; animation: float 3s ease-in-out infinite; }
        @keyframes float { 0% { transform: translateY(0px); } 50% { transform: translateY(-10px); } 100% { transform: translateY(0px); } }
        .design-card .item-name { font-size: 1.5rem; margin: 0.8rem 0; }
        .design-card .amount-desc { color: #cfd8e8; margin-bottom: 1rem; }
        .btn-design { background: linear-gradient(105deg, #FFD700, #FFA500); border: none; padding: 0.8rem 1.5rem; border-radius: 3rem; font-weight: 800; color: #0a0f1e; cursor: pointer; transition: 0.3s; position: relative; z-index: 1; }
        .btn-design:hover { background: linear-gradient(105deg, #FFC107, #FF8C00); transform: scale(1.05); }

        .contact-section { display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; margin: 2rem 0 1.5rem; }
        .contact-card { background: linear-gradient(145deg, rgba(15, 25, 45, 0.9), rgba(10, 18, 32, 0.95)); backdrop-filter: blur(10px); border-radius: 1.8rem; padding: 1.2rem 1.5rem; text-align: center; border: 1px solid #ffb34770; flex: 1; min-width: 210px; }
        .share-btn, .export-btn, .policy-btn { background: #ffb34720; border: 1px solid #ffb347; padding: 0.4rem 1rem; border-radius: 40px; cursor: pointer; display: inline-flex; align-items: center; gap: 8px; margin-top: 0.5rem; }
        .payment-section { background: linear-gradient(145deg, rgba(15, 25, 45, 0.9), rgba(10, 18, 32, 0.95)); backdrop-filter: blur(12px); border-radius: 2rem; padding: 1.6rem; margin: 1rem 0; border: 1px solid #ffb34740; text-align: center; }
        .vodafone-number { background: #00000030; padding: 0.8rem; border-radius: 2rem; margin: 0.8rem auto; display: inline-block; width: 100%; max-width: 360px; border: 1px dashed #ffb347; }
        .copy-btn, .copy-contact { background: #ffb34730; border: 1px solid #ffb347; padding: 0.3rem 1rem; border-radius: 2rem; font-weight: 600; cursor: pointer; }
        .telegram-large-btn { display: inline-flex; align-items: center; gap: 8px; background: #0088cc; padding: 0.7rem 1.5rem; border-radius: 40px; color: white; text-decoration: none; font-weight: bold; }
        .faq-section { background: linear-gradient(145deg, rgba(15, 25, 45, 0.9), rgba(10, 18, 32, 0.95)); border-radius: 2rem; padding: 1.5rem; margin: 1rem 0; border: 1px solid #ffb34740; }
        .faq-item { margin-bottom: 1rem; border-bottom: 1px solid #ffb34730; }
        .faq-question { display: flex; justify-content: space-between; cursor: pointer; padding: 0.7rem 0; font-weight: bold; }
        .faq-answer { display: none; padding-bottom: 0.7rem; color: #ccc; }
        .comments-section { background: linear-gradient(145deg, rgba(15, 25, 45, 0.9), rgba(10, 18, 32, 0.95)); backdrop-filter: blur(12px); border-radius: 2rem; padding: 1.6rem; margin: 2rem 0 0; border: 1px solid #ffb34740; }
        .comment-form input, .comment-form textarea { background: rgba(255,255,255,0.1); border: 1px solid #ffb34760; border-radius: 1rem; padding: 0.7rem 1rem; font-family: 'Cairo', sans-serif; font-size: 0.9rem; color: #f0f3fa; outline: none; width: 100%; margin-bottom: 0.8rem; }
        .rating-stars i { color: #ccc; transition: 0.1s; cursor: pointer; font-size: 1.3rem; }
        .rating-stars i.active { color: #FFB347; }
        .btn-submit { background: linear-gradient(105deg, #FFB347, #FF7E05); border: none; padding: 0.7rem; border-radius: 2rem; font-weight: 800; font-size: 1rem; color: #0a0f1e; cursor: pointer; width: 100%; }
        .comments-list { max-height: 400px; overflow-y: auto; margin-top: 1rem; }
        .comment-item { background: rgba(0,0,0,0.2); border-radius: 1.2rem; padding: 1rem; border-right: 4px solid #FFB347; margin-bottom: 1rem; }
        .delete-comment { background: none; border: none; color: #ff6b6b; cursor: pointer; float: left; }
        .recent-orders { background: rgba(15, 25, 45, 0.7); border-radius: 1.5rem; padding: 1rem; margin: 1rem 0; text-align: center; }
        .recent-orders ul { list-style: none; display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap; margin-top: 0.5rem; }
        .recent-orders li { background: rgba(0,0,0,0.3); padding: 0.3rem 0.8rem; border-radius: 40px; font-size: 0.8rem; }
        .toast-notification { position: fixed; bottom: 30px; left: 50%; transform: translateX(-50%); background: #1e2a3a; color: #FFE0A3; padding: 0.8rem 1.5rem; border-radius: 3rem; z-index: 2000; border-right: 6px solid #FFB347; backdrop-filter: blur(12px); opacity: 0; transition: 0.3s; pointer-events: none; }
        .toast-notification.show { opacity: 1; }
        .modal { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.9); backdrop-filter: blur(5px); z-index: 3000; display: flex; align-items: center; justify-content: center; visibility: hidden; opacity: 0; transition: 0.2s; }
        .modal.show { visibility: visible; opacity: 1; }
        .modal-content { background: #0f172f; border-radius: 2rem; padding: 1.5rem; max-width: 500px; width: 90%; border: 2px solid #ffb347; text-align: center; }
        .hidden-section { display: none; }
        @keyframes zoomIn { from { opacity: 0; transform: scale(0.9); } to { opacity: 1; transform: scale(1); } }
        .modal-enter { animation: zoomIn 0.25s ease; }
        .footer-note { text-align: center; font-size: 0.7rem; margin-top: 1.5rem; color: #8a9bce; }

        .site-owner { font-size: 1.5rem; font-weight: 700; background: linear-gradient(135deg, #FFD700, #FFA500); -webkit-background-clip: text; background-clip: text; color: transparent; margin: 0.5rem 0; }
        @media (max-width: 600px) { .hero h1 { font-size: 1.5rem; } .stat-card { min-width: 100px; } .premium-text { font-size: 2rem; } }
    </style>
</head>
<body>
<div class="progress-container"><div class="progress-bar" id="progressBar"></div></div>
<button class="scroll-top" id="scrollTopBtn"><i class="fas fa-chevron-up"></i></button>
<div class="container">
    <div class="welcome-message" id="welcomeMessage"></div>
    <div class="hero">
        <h1><i class="fas fa-bolt"></i> اسرع من نتكم 🔥</h1>
        <p>شحن PUBG - Mobile Legends - Free Fire - يلا لودو VIP - كروت شحن - فودافون كاش - إنترنت WE</p>
        <div class="brand-name"><i class="fas fa-rocket"></i> اسرع من نتكم 🔥</div>
        <div class="site-owner">﷼𝑅 𝐸 𝐴 𝐿</div>
        <div class="badge-eg"><i class="fas fa-phone-alt"></i> دفع فودافون كاش | تسليم فوري</div>
        <div class="countdown" id="countdownTimer"><i class="fas fa-tags"></i> خصم 10% ينتهي بعد: -- : -- : --</div>
    </div>

    <div class="section-switch">
        <button id="showGamesBtn" class="switch-btn active"><i class="fas fa-gamepad"></i> 🎮 الألعاب</button>
        <button id="showRechargeBtn" class="switch-btn"><i class="fas fa-mobile-alt"></i> 📱 شحن الرصيد والإنترنت</button>
        <button id="showDesignBtn" class="switch-btn"><i class="fas fa-paint-brush"></i> 🎨 خدمات التصميم</button>
    </div>

    <div class="stats-bar">
        <div class="stat-card"><div class="stat-number" id="statOrders">0</div><div class="stat-label"><i class="fas fa-check-circle"></i> طلب مكتمل</div></div>
        <div class="stat-card"><div class="stat-number" id="statCustomers">0</div><div class="stat-label"><i class="fas fa-users"></i> عميل سعيد</div></div>
        <div class="stat-card"><div class="stat-number" id="statDelivery">0</div><div class="stat-label"><i class="fas fa-clock"></i> دقيقة للتسليم</div></div>
        <div class="stat-card"><div class="stat-number" id="statActive">0</div><div class="stat-label"><i class="fas fa-eye"></i> زوار نشطاء</div></div>
        <div class="stat-card"><div class="stat-number" id="statSatisfaction">0%</div><div class="stat-label"><i class="fas fa-smile"></i> نسبة الرضا</div></div>
        <div class="stat-card"><div class="stat-number" id="statTotalSales">0</div><div class="stat-label"><i class="fas fa-chart-line"></i> إجمالي المبيعات (ج.م)</div></div>
        <div class="stat-card"><div class="stat-number" id="statVisitorsToday">0</div><div class="stat-label"><i class="fas fa-calendar-day"></i> زوار اليوم</div></div>
    </div>

    <div id="gamesSection">
        <div class="game-tabs">
            <button class="tab-btn active" data-game="pubg"><i class="fab fa-playstation"></i> PUBG MOBILE</button>
            <button class="tab-btn" data-game="mlbb"><i class="fas fa-skull-crossbones"></i> Mobile Legends</button>
            <button class="tab-btn" data-game="freefire"><i class="fas fa-fire"></i> Free Fire</button>
            <button class="tab-btn" data-game="yallaludo"><i class="fas fa-dice-d6"></i> يلا لودو (VIP)</button>
        </div>
        <div id="pricesContainer" class="prices-grid"></div>
    </div>

    <div id="rechargeSection" class="hidden-section">
        <div class="game-tabs recharge-tabs">
            <button class="recharge-tab active" data-recharge="vodafone"><i class="fas fa-sim-card"></i> فودافون</button>
            <button class="recharge-tab" data-recharge="etisalat"><i class="fas fa-tower-cell"></i> اتصالات</button>
            <button class="recharge-tab" data-recharge="we"><i class="fas fa-wifi"></i> وي</button>
            <button class="recharge-tab" data-recharge="wehome"><i class="fas fa-home"></i> إنترنت WE منزلي</button>
        </div>
        <div id="rechargeContainer" class="prices-grid"></div>
    </div>

    <!-- قسم التصميم الجديد بدون أسعار -->
    <div id="designSection" class="hidden-section">
        <div class="design-tabs">
            <button class="design-tab active" data-design="branding"><i class="fas fa-crown"></i> هوية بصرية</button>
            <button class="design-tab" data-design="social"><i class="fas fa-thumbs-up"></i> سوشيال ميديا</button>
            <button class="design-tab" data-design="video"><i class="fas fa-video"></i> مونتاج</button>
            <button class="design-tab" data-design="motion"><i class="fas fa-film"></i> موشن جرافيك</button>
        </div>
        <div id="designContainer" class="prices-grid"></div>
    </div>

    <div class="recent-orders">
        <i class="fas fa-history"></i> آخر الطلبات المكتملة
        <ul id="recentOrdersList">
            <li>🟢 PUBG - 100 UC</li>
            <li>🟢 Free Fire - 500 جوهرة</li>
            <li>🟢 يلا لودو - رتبة الفارس</li>
        </ul>
    </div>

    <div class="contact-section">
        <div class="contact-card"><i class="fab fa-whatsapp" style="font-size: 2rem; color:#25D366;"></i><h4>خدمة العملاء واتساب</h4><div class="contact-number">01017954664</div><button class="copy-contact" onclick="copyNumberGeneric('01017954664', this)"><i class="far fa-copy"></i> نسخ</button><a href="https://wa.me/201017954664" target="_blank"><i class="fab fa-whatsapp"></i> تواصل الآن</a></div>
        <div class="contact-card"><i class="fab fa-telegram" style="font-size: 2rem; color:#0088cc;"></i><h4>شحن الرصيد والإنترنت</h4><div class="contact-number">@BESO125F</div><button class="copy-contact" onclick="copyNumberGeneric('@BESO125F', this)"><i class="far fa-copy"></i> نسخ المعرف</button><a href="https://t.me/BESO125F" target="_blank"><i class="fab fa-telegram"></i> تواصل تلجرام</a></div>
        <div class="contact-card"><i class="fas fa-share-alt" style="font-size: 2rem; color:#FFB347;"></i><h4>مشاركة الموقع</h4><button class="share-btn" id="shareBtn"><i class="fas fa-share"></i> نسخ الرابط</button><button class="export-btn" id="exportCommentsBtn"><i class="fas fa-download"></i> تصدير التعليقات</button><button class="policy-btn" id="policyBtn"><i class="fas fa-file-contract"></i> سياسة الخصوصية</button></div>
    </div>

    <div class="faq-section">
        <h3 style="text-align:center;"><i class="fas fa-question-circle"></i> الأسئلة الشائعة</h3>
        <div class="faq-item"><div class="faq-question">❓ كم تستغرق عملية الشحن؟ <i class="fas fa-chevron-down"></i></div><div class="faq-answer">عادة من 5 إلى 20 دقيقة بعد تأكيد الدفع. في أوقات الذروة قد تصل إلى 30 دقيقة.</div></div>
        <div class="faq-item"><div class="faq-question">❓ هل يوجد ضمان على الشحن؟ <i class="fas fa-chevron-down"></i></div><div class="faq-answer">نعم، ضمان 100% أو استرداد كامل المبلغ إذا لم يتم الشحن خلال 24 ساعة.</div></div>
        <div class="faq-item"><div class="faq-question">❓ كيف أتواصل في حالة وجود مشكلة؟ <i class="fas fa-chevron-down"></i></div><div class="faq-answer">عبر واتساب على الرقم 01017954664 أو عبر التلجرام @BESO125F.</div></div>
        <div class="faq-item"><div class="faq-question">❓ ما هي طرق الدفع المتاحة؟ <i class="fas fa-chevron-down"></i></div><div class="faq-answer">حالياً فودافون كاش فقط، قريباً إنستا باي وأورانج كاش.</div></div>
    </div>

    <div class="payment-section">
        <i class="fas fa-money-bill-wave" style="font-size: 2rem; color: #FFB347;"></i>
        <h2>طريقة الدفع : فودافون كاش</h2>
        <div class="vodafone-number"><i class="fas fa-mobile-alt"></i> رقم المحفظة: <h3 dir="ltr">01044049390</h3><button class="copy-btn" id="copyNumberBtn"><i class="far fa-copy"></i> نسخ الرقم</button></div>
        <p><i class="fas fa-info-circle"></i> بعد التحويل، أرسل صورة الإيداع + الـ ID على واتساب</p>
        <div class="payment-steps" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 0.6rem; margin-top: 1rem;">
            <div class="step" style="background:#1e2a3a; padding:0.3rem 0.8rem; border-radius: 2rem;"><i class="fas fa-check-circle"></i> افتح فودافون كاش</div>
            <div class="step" style="background:#1e2a3a; padding:0.3rem 0.8rem; border-radius: 2rem;"><i class="fas fa-check-circle"></i> تحويل للأرقام</div>
            <div class="step" style="background:#1e2a3a; padding:0.3rem 0.8rem; border-radius: 2rem;"><i class="fas fa-check-circle"></i> الرقم: 01044049390</div>
            <div class="step" style="background:#1e2a3a; padding:0.3rem 0.8rem; border-radius: 2rem;"><i class="fas fa-check-circle"></i> أرسل التأكيد واستلم الشحن</div>
        </div>
    </div>

    <div class="comments-section">
        <h3 style="text-align:center; margin-bottom:1rem;"><i class="fas fa-comments"></i> آرائكم واقتراحاتكم</h3>
        <div class="comment-form">
            <input type="text" id="commentName" placeholder="الاسم (مطلوب)">
            <input type="email" id="commentEmail" placeholder="البريد الإلكتروني (اختياري)">
            <div style="display: flex; justify-content: space-between; align-items: center;"><span>التقييم:</span><div class="rating-stars" id="ratingStars"><i class="far fa-star" data-rating="1"></i><i class="far fa-star" data-rating="2"></i><i class="far fa-star" data-rating="3"></i><i class="far fa-star" data-rating="4"></i><i class="far fa-star" data-rating="5"></i></div></div>
            <textarea id="commentText" rows="3" placeholder="اكتب تعليقك، اقتراحك، أو شكواك هنا..."></textarea>
            <button class="btn-submit" id="submitComment"><i class="fas fa-paper-plane"></i> إرسال</button>
        </div>
        <div id="commentsList" class="comments-list"></div>
    </div>
    <div class="footer-note"><i class="fas fa-shield-alt"></i> التسليم خلال 5-20 دقيقة بعد تأكيد الدفع | الدعم الفني: 01017954664</div>
</div>

<!-- Modal للسياسة -->
<div id="policyModal" class="modal"><div class="modal-content"><h3>سياسة الخصوصية</h3><p>نحن نلتزم بحماية بياناتك الشخصية. لا نقوم بمشاركة معلوماتك مع أي طرف ثالث. تستخدم بياناتك فقط لإتمام عمليات الشحن والتواصل معك. يمكنك طلب حذف بياناتك في أي وقت عبر واتساب.</p><button id="closePolicyBtn" class="copy-btn" style="margin-top:1rem;">إغلاق</button></div></div>

<script>
    // ======================== بيانات الألعاب ========================
    const pubgItems = [ { name: "1 + 30 UC", desc: "باقة + بونص", priceEGP: 25.99 }, { name: "22 + 60 UC", desc: "باقة + بونص", priceEGP: 46.99 }, { name: "54 + 300 UC", desc: "باقة + بونص", priceEGP: 214.99 }, { name: "98 + 600 UC", desc: "باقة + بونص", priceEGP: 424.99 }, { name: "365 + 1500 UC", desc: "باقة + بونص", priceEGP: 1054.99 }, { name: "960 + 3000 UC", desc: "باقة + بونص", priceEGP: 2104.99 }, { name: "2300 + 6000 UC", desc: "باقة + بونص", priceEGP: 4204.99 }, { name: "4580 + 12000 UC", desc: "باقة + بونص", priceEGP: 8404.99 }, { name: "6860 + 18000 UC", desc: "باقة + بونص", priceEGP: 12604.99 }, { name: "9140 + 24000 UC", desc: "باقة + بونص", priceEGP: 16804.99 }, { name: "11420 + 30000 UC", desc: "باقة + بونص", priceEGP: 21004.99 }, { name: "13700 + 36000 UC", desc: "باقة + بونص", priceEGP: 25204.99 }, { name: "22820 + 60000 UC", desc: "باقة + بونص", priceEGP: 42004.99 } ];
    const mlbbItems = [ { name: "13 + 1 Diamonds", desc: "باقة + بونص", priceEGP: 25 }, { name: "20 + 2 Diamonds", desc: "باقة + بونص", priceEGP: 30 }, { name: "51 + 5 Diamonds", desc: "باقة + بونص", priceEGP: 65 }, { name: "102 + 10 Diamonds", desc: "باقة + بونص", priceEGP: 120 }, { name: "153 + 15 Diamonds", desc: "باقة + بونص", priceEGP: 180 }, { name: "203 + 20 Diamonds", desc: "باقة + بونص", priceEGP: 235 }, { name: "303 + 33 Diamonds", desc: "باقة + بونص", priceEGP: 350 }, { name: "504 + 66 Diamonds", desc: "باقة + بونص", priceEGP: 580 }, { name: "1007 + 156 Diamonds", desc: "باقة + بونص", priceEGP: 1150 }, { name: "2015 + 383 Diamonds", desc: "باقة + بونص", priceEGP: 2300 }, { name: "5035 + 1007 Diamonds", desc: "باقة + بونص", priceEGP: 5730 } ];
    const freefireItems = [ { name: "50 جوهرة", desc: "شحن فوري", priceEGP: 25 }, { name: "100 جوهرة", desc: "شحن فوري", priceEGP: 50 }, { name: "210 جوهرة", desc: "شحن فوري", priceEGP: 100 }, { name: "310 جوهرة", desc: "شحن فوري", priceEGP: 150 }, { name: "520 جوهرة", desc: "شحن فوري", priceEGP: 250 }, { name: "1060 جوهرة", desc: "شحن فوري", priceEGP: 500 }, { name: "2200 جوهرة", desc: "شحن فوري", priceEGP: 1000 } ];
    const yallaNormalItems = [ { name: "830 💎", desc: "شحن عادي", priceEGP: 110, isVip: false }, { name: "2,320 💎", desc: "شحن عادي", priceEGP: 250, isVip: false }, { name: "3,150 💎", desc: "شحن عادي", priceEGP: 360, isVip: false }, { name: "5,150 💎", desc: "شحن عادي", priceEGP: 490, isVip: false }, { name: "7,480 💎", desc: "شحن عادي", priceEGP: 740, isVip: false }, { name: "8,300 💎", desc: "شحن عادي", priceEGP: 850, isVip: false }, { name: "10,300 💎", desc: "شحن عادي", priceEGP: 980, isVip: false }, { name: "13,580 💎", desc: "شحن عادي", priceEGP: 1225, isVip: false }, { name: "16,700 💎", desc: "شحن عادي", priceEGP: 1580, isVip: false }, { name: "18,700 💎", desc: "شحن عادي", priceEGP: 1690, isVip: false }, { name: "21,000 💎", desc: "شحن عادي", priceEGP: 1960, isVip: false }, { name: "27,640 💎", desc: "شحن عادي", priceEGP: 2450, isVip: false }, { name: "32,790 💎", desc: "شحن عادي", priceEGP: 2940, isVip: false }, { name: "37,900 💎", desc: "شحن عادي", priceEGP: 3430, isVip: false }, { name: "43,090 💎", desc: "شحن عادي", priceEGP: 3920, isVip: false }, { name: "55,800 💎", desc: "شحن عادي", priceEGP: 4800, isVip: false }, { name: "69,380 💎", desc: "شحن عادي", priceEGP: 6025, isVip: false }, { name: "74,530 💎", desc: "شحن عادي", priceEGP: 6510, isVip: false }, { name: "111,600 💎", desc: "شحن عادي", priceEGP: 9600, isVip: false }, { name: "168,860 💎", desc: "شحن عادي", priceEGP: 14400, isVip: false }, { name: "223,200 💎", desc: "شحن عادي", priceEGP: 19200, isVip: false }, { name: "283,460 💎", desc: "شحن عادي", priceEGP: 24000, isVip: false } ];
    const yallaVipItems = [ { name: "👑 الفارس", desc: "رتبة VIP", priceEGP: 560, isVip: true }, { name: "👑 اللواء", desc: "رتبة VIP", priceEGP: 1760, isVip: true } ];
    const yallaAccountItems = [ { name: "400 💎", desc: "شحن بالاكونت", priceEGP: 60, isVip: false }, { name: "1,800 💎", desc: "شحن بالاكونت", priceEGP: 190, isVip: false }, { name: "5,000 💎", desc: "شحن بالاكونت", priceEGP: 450, isVip: false }, { name: "6,800 💎", desc: "شحن بالاكونت", priceEGP: 640, isVip: false }, { name: "7,200 💎", desc: "شحن بالاكونت", priceEGP: 700, isVip: false }, { name: "10,000 💎", desc: "شحن بالاكونت", priceEGP: 900, isVip: false }, { name: "16,000 💎", desc: "شحن بالاكونت", priceEGP: 1310, isVip: false }, { name: "21,000 💎", desc: "شحن بالاكونت", priceEGP: 1780, isVip: false }, { name: "26,000 💎", desc: "شحن بالاكونت", priceEGP: 2230, isVip: false }, { name: "32,000 💎", desc: "شحن بالاكونت", priceEGP: 2660, isVip: false }, { name: "42,000 💎", desc: "شحن بالاكونت", priceEGP: 3560, isVip: false }, { name: "48,000 💎", desc: "شحن بالاكونت", priceEGP: 3990, isVip: false }, { name: "53,700 💎", desc: "شحن بالاكونت", priceEGP: 4250, isVip: false }, { name: "69,700 💎", desc: "شحن بالاكونت", priceEGP: 5700, isVip: false }, { name: "74,700 💎", desc: "شحن بالاكونت", priceEGP: 6150, isVip: false }, { name: "85,700 💎", desc: "شحن بالاكونت", priceEGP: 7000, isVip: false }, { name: "107,000 💎", desc: "شحن بالاكونت", priceEGP: 8500, isVip: false }, { name: "161,000 💎", desc: "شحن بالاكونت", priceEGP: 12750, isVip: false }, { name: "217,000 💎", desc: "شحن بالاكونت", priceEGP: 17000, isVip: false }, { name: "324,000 💎", desc: "شحن بالاكونت", priceEGP: 25500, isVip: false } ];

    // ======================== بيانات التصميم (بدون أسعار) ========================
    const designItems = {
        branding: [
            { name: "تصميم شعار احترافي", desc: "شعار فريد يعبّر عن هويتك", icon: "fas fa-crown" },
            { name: "هوية بصرية كاملة", desc: "لوجو + كروت + أوراق رسمية", icon: "fas fa-bookmark" },
            { name: "دليل العلامة التجارية", desc: "ملف PDF مع الألوان والخطوط", icon: "fas fa-book" }
        ],
        social: [
            { name: "تصميم منشورات سوشيال", desc: "فيس بوك، انستجرام، تويتر", icon: "fas fa-thumbs-up" },
            { name: "تصميم ستوري انستجرام", desc: "موشن + ثابت", icon: "fas fa-image" },
            { name: "تصميم غلاف فيس بوك", desc: "غلاف متوافق مع الموبايل", icon: "fas fa-cover-page" }
        ],
        video: [
            { name: "مونتاج فيديو احترافي", desc: "تعديل، ألوان، تأثيرات", icon: "fas fa-video" },
            { name: "مونتاج ريلز / شورت", desc: "فيديوهات عمودية سريعة", icon: "fas fa-mobile-alt" },
            { name: "تحسين جودة فيديو", desc: "HD / 4K مع تصدير عالي", icon: "fas fa-film" }
        ],
        motion: [
            { name: "موشن جرافيك قصير", desc: "حتى 60 ثانية", icon: "fas fa-play-circle" },
            { name: "إنترو / أوترو للقناة", desc: "مقدمة احترافية للفيديوهات", icon: "fas fa-youtube" },
            { name: "إعلان موشن جرافيك", desc: "للإعلانات التجارية", icon: "fas fa-ad" }
        ]
    };
    let currentDesignSub = 'branding';

    function renderDesign(subKey) {
        const items = designItems[subKey] || [];
        const container = document.getElementById('designContainer');
        let html = '';
        items.forEach(item => {
            html += `
                <div class="design-card">
                    <div class="design-icon"><i class="${item.icon}"></i></div>
                    <div class="item-name">${item.name}</div>
                    <div class="amount-desc">${item.desc}</div>
                    <button class="btn-design" onclick="openDesignOrder('${item.name}')">
                        <i class="fab fa-whatsapp"></i> اطلب الخدمة
                    </button>
                </div>
            `;
        });
        container.innerHTML = html || '<div style="text-align:center;color:#ccc;">لا توجد خدمات حالياً</div>';
    }

    function openDesignOrder(serviceName) {
        const phone = '201017954664'; // استخدم رقم الدعم الحالي أو يمكن تغييره
        const message = `مرحباً، أريد خدمة: ${serviceName} من موقع ﷼𝑅 𝐸 𝐴 𝐿`;
        window.open(`https://wa.me/${phone}?text=${encodeURIComponent(message)}`, '_blank');
    }

    // ======================== متغيرات عامة ========================
    let comments = JSON.parse(localStorage.getItem('websiteComments')) || [];
    let ordersCount = 189, customersCount = 143, deliveryTime = 8, activeVisitors = Math.floor(Math.random() * 50) + 20, satisfactionRate = 94;
    let totalSales = 0;
    let visitorsToday = parseInt(localStorage.getItem('visitorsToday')) || 0;
    let lastDate = localStorage.getItem('lastDate');
    const today = new Date().toDateString();
    if (lastDate !== today) { visitorsToday = 0; localStorage.setItem('lastDate', today); }
    visitorsToday++; localStorage.setItem('visitorsToday', visitorsToday);
    document.getElementById('statVisitorsToday').innerText = visitorsToday;

    let currentGame = 'pubg', currentRecharge = 'vodafone';
    const container = document.getElementById('pricesContainer');
    const rechargeContainer = document.getElementById('rechargeContainer');

    // تأثير الكتابة
    const messages = ["🔥 مرحباً بك في أسرع متجر شحن!", "⚡ خصم 10% لفترة محدودة!", "💎 نضمن أقل الأسعار!", "📱 تواصل معنا على واتساب 24 ساعة", "🎉 أكثر من 500 عميل وثقوا بنا!"];
    let msgIndex = 0;
    function typeWriter() {
        const el = document.getElementById('welcomeMessage');
        let fullMsg = messages[msgIndex];
        let i = 0;
        el.innerHTML = '';
        function type() {
            if (i < fullMsg.length) { el.innerHTML += fullMsg.charAt(i); i++; setTimeout(type, 50); }
            else { setTimeout(() => { msgIndex = (msgIndex+1)%messages.length; typeWriter(); }, 3000); }
        }
        type();
    }
    typeWriter();

    function showToast(msg) { const toast = document.createElement('div'); toast.className = 'toast-notification'; toast.innerHTML = `<i class="fas fa-info-circle"></i> ${msg}`; document.body.appendChild(toast); setTimeout(() => toast.classList.add('show'), 10); setTimeout(() => { toast.classList.remove('show'); setTimeout(() => toast.remove(), 500); }, 3000); }
    window.copyNumberGeneric = function(number, btn) { navigator.clipboard.writeText(number).then(() => { btn.innerHTML = '<i class="fas fa-check"></i> تم!'; setTimeout(() => btn.innerHTML = '<i class="far fa-copy"></i> نسخ', 1500); showToast('تم نسخ: '+number); }); };
    function animateNumber(el, start, end, dur) { let startTime = null; const step = (t) => { if (!startTime) startTime = t; const prog = Math.min((t-startTime)/dur,1); el.innerText = Math.floor(prog*(end-start)+start); if(prog<1) requestAnimationFrame(step); }; requestAnimationFrame(step); }
    function updateStats() { animateNumber(document.getElementById('statOrders'),0,ordersCount,1300); animateNumber(document.getElementById('statCustomers'),0,customersCount,1300); animateNumber(document.getElementById('statDelivery'),0,deliveryTime,1300); document.getElementById('statActive').innerText = activeVisitors; document.getElementById('statSatisfaction').innerText = satisfactionRate+'%'; document.getElementById('statTotalSales').innerText = totalSales.toLocaleString(); }

    // نافذة الطلب مع كوبون خصم (للألعاب)
    function openOrderPopup(itemName, price) {
        const discountCode = "WELCOME10";
        const discountedPrice = price * 0.9;
        showToast('⏳ جاري تجهيز الطلب...');
        setTimeout(() => {
            const modal = document.createElement('div'); modal.style.position='fixed'; modal.style.top='0'; modal.style.left='0'; modal.style.width='100%'; modal.style.height='100%'; modal.style.backgroundColor='rgba(0,0,0,0.85)'; modal.style.backdropFilter='blur(8px)'; modal.style.zIndex='1000'; modal.style.display='flex'; modal.style.alignItems='center'; modal.style.justifyContent='center';
            const card = document.createElement('div'); card.className='modal-enter'; card.style.background='linear-gradient(145deg, #0f172f, #0a0f22)'; card.style.borderRadius='2rem'; card.style.maxWidth='420px'; card.style.width='90%'; card.style.padding='1.5rem'; card.style.border='2px solid #ffb347'; card.style.textAlign='center';
            card.innerHTML = `<i class="fas fa-gem" style="font-size:2.5rem; color:#ffb347;"></i><h3>تأكيد الطلب</h3>
                <p><strong>${itemName}</strong><br>السعر: <span style="color:#FFD966; font-size:1.3rem;">${price.toLocaleString('eg-EG',{minimumFractionDigits:2})} جنيه</span></p>
                <div style="background:#00000040; border-radius:1rem; padding:0.5rem;"><i class="fas fa-tag"></i> كود الخصم: <strong>${discountCode}</strong> (10%)<br>بعد الخصم: ${discountedPrice.toLocaleString('eg-EG',{minimumFractionDigits:2})} جنيه</div>
                <div style="margin:0.8rem 0;"><i class="fas fa-phone-alt"></i> الدفع: <strong>01044049390</strong> <button class="modal-copy-payment" style="background:#ffb34720; border:1px solid #ffb347; border-radius:2rem; padding:0.2rem 0.8rem;">نسخ</button></div>
                <div><i class="fab fa-whatsapp"></i> الدعم: <strong>01017954664</strong> <button class="modal-copy-support" style="background:#ffb34720; border:1px solid #ffb347; border-radius:2rem; padding:0.2rem 0.8rem;">نسخ</button></div>
                <button id="copyAllInfoBtn" style="background:#ffb347; color:#0a0f1e; border:none; border-radius:2rem; padding:0.4rem 1rem; margin:0.5rem 0;"><i class="fas fa-copy"></i> نسخ الكل</button>
                <div style="display:flex; gap:0.6rem; justify-content:center; margin-top:1rem;"><button id="closeModalBtn" style="background:#2a3650; border:none; padding:0.5rem 1.2rem; border-radius:2rem;">إغلاق</button><a href="https://wa.me/201044049390?text=طلب%20شحن%20${encodeURIComponent(itemName)}%20بمبلغ%20${price}%20جنيه" target="_blank" style="background:#25D366; color:white; text-decoration:none; padding:0.5rem 1.2rem; border-radius:2rem;"><i class="fab fa-whatsapp"></i> واتساب</a></div>`;
            modal.appendChild(card); document.body.appendChild(modal);
            document.getElementById('closeModalBtn')?.addEventListener('click',()=>modal.remove());
            modal.addEventListener('click',(e)=>{if(e.target===modal) modal.remove();});
            card.querySelector('.modal-copy-payment')?.addEventListener('click',()=>{ navigator.clipboard.writeText('01044049390'); showToast('تم نسخ رقم الدفع'); });
            card.querySelector('.modal-copy-support')?.addEventListener('click',()=>{ navigator.clipboard.writeText('01017954664'); showToast('تم نسخ رقم الدعم'); });
            document.getElementById('copyAllInfoBtn')?.addEventListener('click',()=>{ navigator.clipboard.writeText(`الطلب: ${itemName}\nالمبلغ: ${price} جنيه\nبعد الخصم: ${discountedPrice} جنيه\nرقم فودافون كاش: 01044049390\nالدعم: 01017954664`); showToast('تم نسخ جميع المعلومات'); });
        }, 1000);
    }

    function renderGame(gameKey) {
        let items = [], gameIcon = "", gameName = "";
        if (gameKey === 'pubg') { items = pubgItems; gameIcon = "fab fa-playstation"; gameName = "PUBG MOBILE"; }
        else if (gameKey === 'mlbb') { items = mlbbItems; gameIcon = "fas fa-skull-crossbones"; gameName = "Mobile Legends"; }
        else if (gameKey === 'freefire') { items = freefireItems; gameIcon = "fas fa-fire"; gameName = "Free Fire"; }
        else if (gameKey === 'yallaludo') { items = [...yallaNormalItems, ...yallaVipItems, ...yallaAccountItems]; gameIcon = "fas fa-dice-d6"; gameName = "يلا لودو"; }
        let html = '';
        items.forEach((item, idx) => {
            let formattedPrice = item.priceEGP.toLocaleString('eg-EG', { minimumFractionDigits: 2 });
            const vipClass = item.isVip ? 'vip-card' : '';
            const vipBadge = item.isVip ? '<div class="game-badge vip-badge"><i class="fas fa-crown"></i> VIP مميز</div>' : `<div class="game-badge">${gameName}</div>`;
            html += `<div class="price-card ${vipClass}"><div class="card-icon"><i class="${gameIcon}"></i></div>${vipBadge}<div class="item-name">${item.name}</div><div class="amount-desc">${item.desc}</div><div class="price-eg">${formattedPrice} <span>جنيه مصري</span></div><button class="btn-order" data-item="${item.name} (${gameName} - ${item.desc})" data-price="${item.priceEGP}"><i class="fas fa-shopping-cart"></i> اطلب الآن</button></div>`;
        });
        container.innerHTML = html;
        document.querySelectorAll('#pricesContainer .btn-order').forEach(btn => {
            btn.addEventListener('click', (e) => {
                const original = btn.innerHTML; btn.innerHTML = '<i class="fas fa-spinner fa-pulse"></i> جاري...'; btn.classList.add('loading');
                setTimeout(() => {
                    openOrderPopup(btn.getAttribute('data-item'), parseFloat(btn.getAttribute('data-price')));
                    btn.innerHTML = original; btn.classList.remove('loading');
                    ordersCount++; customersCount++; totalSales += parseFloat(btn.getAttribute('data-price'));
                    document.getElementById('statOrders').innerText = ordersCount; document.getElementById('statCustomers').innerText = customersCount; document.getElementById('statTotalSales').innerText = totalSales.toLocaleString();
                    const recentList = document.getElementById('recentOrdersList'); const newOrder = document.createElement('li'); newOrder.innerHTML = `🟢 ${btn.getAttribute('data-item').substring(0,30)}`; recentList.prepend(newOrder); if(recentList.children.length>5) recentList.removeChild(recentList.lastChild);
                }, 1200);
            });
        });
    }

    function renderRecharge(companyKey) {
        let logo = "", name = "";
        switch(companyKey) {
            case 'vodafone': logo='<div style="background:#e60000; width:50px; height:50px; border-radius:50%; display:flex; align-items:center; justify-content:center; margin:0 auto;"><i class="fas fa-sim-card"></i></div>'; name="فودافون"; break;
            case 'etisalat': logo='<div style="background:#007b3d; width:50px; height:50px; border-radius:50%; display:flex; align-items:center; justify-content:center; margin:0 auto;"><i class="fas fa-tower-cell"></i></div>'; name="اتصالات"; break;
            case 'we': logo='<div style="background:#6f2da8; width:50px; height:50px; border-radius:50%; display:flex; align-items:center; justify-content:center; margin:0 auto;"><i class="fas fa-wifi"></i></div>'; name="وي"; break;
            case 'wehome': logo='<div style="background:#1e88e5; width:50px; height:50px; border-radius:50%; display:flex; align-items:center; justify-content:center; margin:0 auto;"><i class="fas fa-home"></i></div>'; name="إنترنت WE منزلي"; break;
        }
        rechargeContainer.innerHTML = `<div class="price-card" style="grid-column:1/-1; text-align:center;">${logo}<div class="game-badge">${name}</div><div class="item-name">أسعار متغيرة 🔄</div><div class="amount-desc">للحصول على أحدث الأسعار تواصل معنا عبر تلجرام</div><a href="https://t.me/BESO125F" target="_blank" class="telegram-large-btn"><i class="fab fa-telegram"></i> تواصل عبر تلجرام</a><button class="copy-contact" style="margin:0.8rem auto 0;" onclick="copyNumberGeneric('@BESO125F', this)">نسخ المعرف</button></div>`;
    }

    // إدارة التعليقات
    function saveComments() { localStorage.setItem('websiteComments', JSON.stringify(comments)); }
    function renderComments() {
        const div = document.getElementById('commentsList'); if(!div) return;
        if(comments.length===0) { div.innerHTML='<div style="text-align:center;">لا توجد تعليقات بعد</div>'; return; }
        let total=0;
        div.innerHTML = comments.map((c,idx)=>{ total+=c.rating; let stars=''; for(let i=1;i<=5;i++) stars+=`<i class="fas fa-star" style="color:${i<=c.rating?'#FFB347':'#ccc'}; font-size:0.7rem;"></i>`; return `<div class="comment-item"><button class="delete-comment" data-index="${idx}"><i class="fas fa-trash-alt"></i></button><div class="comment-header"><span><i class="fas fa-user-circle"></i> ${escapeHtml(c.name)}</span><div>${stars}</div><span>${c.date}</span></div><div>${escapeHtml(c.text)}</div></div>`; }).join('');
        if(comments.length) { satisfactionRate = Math.round((total/comments.length)*20); document.getElementById('statSatisfaction').innerText = satisfactionRate+'%'; }
        document.querySelectorAll('.delete-comment').forEach(btn=>{ btn.addEventListener('click',()=>{ if(confirm('حذف؟')){ comments.splice(btn.getAttribute('data-index'),1); saveComments(); renderComments(); showToast('تم الحذف'); } }); });
    }
    function escapeHtml(str) { return str.replace(/[&<>]/g, m=>({ '&':'&amp;', '<':'&lt;', '>':'&gt;' }[m])); }
    let currentRating=0;
    function initRatingStars() { document.querySelectorAll('#ratingStars i').forEach(star=>{ star.addEventListener('click',()=>{ currentRating=parseInt(star.getAttribute('data-rating')); document.querySelectorAll('#ratingStars i').forEach(s=>{ if(parseInt(s.getAttribute('data-rating'))<=currentRating) s.classList.add('active'); else s.classList.remove('active'); }); }); }); }
    document.getElementById('submitComment')?.addEventListener('click',()=>{ const name=document.getElementById('commentName').value.trim(); const email=document.getElementById('commentEmail').value.trim(); const text=document.getElementById('commentText').value.trim(); if(!name||!text||currentRating===0){ showToast('يرجى ملء الاسم والنص والتقييم'); return; } comments.unshift({name,email,text,rating:currentRating,date:new Date().toLocaleString('ar-EG')}); saveComments(); renderComments(); document.getElementById('commentName').value=''; document.getElementById('commentEmail').value=''; document.getElementById('commentText').value=''; currentRating=0; document.querySelectorAll('#ratingStars i').forEach(s=>s.classList.remove('active')); showToast('تم إضافة تعليقك'); });

    // تبديل الأقسام (ألعاب، شحن، تصميم)
    const gamesSec=document.getElementById('gamesSection'), rechargeSec=document.getElementById('rechargeSection'), designSec=document.getElementById('designSection');
    document.getElementById('showGamesBtn').addEventListener('click',()=>{ gamesSec.classList.remove('hidden-section'); rechargeSec.classList.add('hidden-section'); designSec.classList.add('hidden-section'); document.getElementById('showGamesBtn').classList.add('active'); document.getElementById('showRechargeBtn').classList.remove('active'); document.getElementById('showDesignBtn').classList.remove('active'); });
    document.getElementById('showRechargeBtn').addEventListener('click',()=>{ gamesSec.classList.add('hidden-section'); rechargeSec.classList.remove('hidden-section'); designSec.classList.add('hidden-section'); document.getElementById('showRechargeBtn').classList.add('active'); document.getElementById('showGamesBtn').classList.remove('active'); document.getElementById('showDesignBtn').classList.remove('active'); });
    document.getElementById('showDesignBtn').addEventListener('click',()=>{ gamesSec.classList.add('hidden-section'); rechargeSec.classList.add('hidden-section'); designSec.classList.remove('hidden-section'); document.getElementById('showDesignBtn').classList.add('active'); document.getElementById('showGamesBtn').classList.remove('active'); document.getElementById('showRechargeBtn').classList.remove('active'); renderDesign(currentDesignSub); });

    document.querySelectorAll('#gamesSection .tab-btn').forEach(btn=>{ btn.addEventListener('click',()=>{ document.querySelectorAll('#gamesSection .tab-btn').forEach(b=>b.classList.remove('active')); btn.classList.add('active'); renderGame(btn.getAttribute('data-game')); }); });
    document.querySelectorAll('#rechargeSection .recharge-tab').forEach(btn=>{ btn.addEventListener('click',()=>{ document.querySelectorAll('#rechargeSection .recharge-tab').forEach(b=>b.classList.remove('active')); btn.classList.add('active'); renderRecharge(btn.getAttribute('data-recharge')); }); });
    // تبديل التصنيفات داخل التصميم
    document.querySelectorAll('#designSection .design-tab').forEach(btn=>{ btn.addEventListener('click',()=>{ document.querySelectorAll('#designSection .design-tab').forEach(b=>b.classList.remove('active')); btn.classList.add('active'); currentDesignSub = btn.getAttribute('data-design'); renderDesign(currentDesignSub); }); });

    document.getElementById('copyNumberBtn')?.addEventListener('click',()=>{ navigator.clipboard.writeText('01044049390'); showToast('تم نسخ رقم فودافون كاش'); });
    document.getElementById('shareBtn')?.addEventListener('click',()=>{ navigator.clipboard.writeText(window.location.href); showToast('تم نسخ رابط الموقع'); });
    document.getElementById('exportCommentsBtn')?.addEventListener('click',()=>{ const dataStr = JSON.stringify(comments,null,2); const blob = new Blob([dataStr],{type:'application/json'}); const url=URL.createObjectURL(blob); const a=document.createElement('a'); a.href=url; a.download='comments.json'; a.click(); URL.revokeObjectURL(url); showToast('تم تصدير التعليقات'); });
    document.getElementById('policyBtn')?.addEventListener('click',()=>{ document.getElementById('policyModal').classList.add('show'); });
    document.getElementById('closePolicyBtn')?.addEventListener('click',()=>{ document.getElementById('policyModal').classList.remove('show'); });

    // الأسئلة الشائعة
    document.querySelectorAll('.faq-question').forEach(q=>{ q.addEventListener('click',()=>{ const ans=q.nextElementSibling; ans.style.display=ans.style.display==='block'?'none':'block'; }); });

    // شريط التقدم
    window.addEventListener('scroll',()=>{ const winScroll=document.body.scrollTop||document.documentElement.scrollTop; const height=document.documentElement.scrollHeight-document.documentElement.clientHeight; const scrolled=(winScroll/height)*100; document.getElementById('progressBar').style.width=scrolled+'%'; if(winScroll>300) document.getElementById('scrollTopBtn').classList.add('show'); else document.getElementById('scrollTopBtn').classList.remove('show'); });
    document.getElementById('scrollTopBtn').addEventListener('click',()=>{ window.scrollTo({top:0,behavior:'smooth'}); });

    // العد التنازلي
    let endTime = localStorage.getItem('countdownEnd'); if(!endTime){ endTime=Date.now()+2*60*60*1000; localStorage.setItem('countdownEnd',endTime); }
    function updateCountdown(){ const remaining=Math.max(0,parseInt(endTime)-Date.now()); if(remaining<=0){ document.getElementById('countdownTimer').innerHTML='<i class="fas fa-tags"></i> العرض انتهى!'; return; } const h=Math.floor(remaining/3600000); const m=Math.floor((remaining%3600000)/60000); const s=Math.floor((remaining%60000)/1000); document.ge