# Nano-Scan-
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nano Scan - الأشعة المنزلية</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            font-family: 'Tajawal', sans-serif;
            direction: rtl;
            text-align: right;
        }
        .hero {
            background: url('https://source.unsplash.com/1600x900/?medical,scan') no-repeat center;
            background-size: cover;
            height: 60vh;
            display: flex;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        .service-card {
            transition: 0.3s;
        }
        .service-card:hover {
            transform: scale(1.05);
        }
        .logo {
            display: block;
            margin: 20px auto;
            width: 150px;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Nano Scan</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#services">الخدمات</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">عنّا</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">اتصل بنا</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <img src="nano.jpg" alt="Nano Scan Logo" class="logo">

    <header class="hero text-center">
        <div class="container">
            <h1>الأشعة المنزلية بسهولة وأمان</h1>
            <p>خدمات التصوير الطبي في منزلك، أينما كنت!</p>
            <a href="#contact" class="btn btn-primary">احجز الآن</a>
        </div>
    </header>

    <section id="services" class="container py-5">
        <h2 class="text-center mb-4">خدماتنا</h2>
        <div class="row text-center">
            <div class="col-md-3">
                <div class="card service-card p-3 shadow-sm">
                    <img src="xray.jpg" class="card-img-top" alt="الأشعة السينية">
                    <h3>الأشعة السينية</h3>
                    <p>الأشعة السينية تستخدم للكشف عن الكسور، مشاكل العظام، وأمراض الصدر. نقدم لك تصويرًا دقيقًا دون الحاجة لمغادرة المنزل.</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card service-card p-3 shadow-sm">
                    <img src="ultrasound.jpg" class="card-img-top" alt="الموجات فوق الصوتية">
                    <h3>الموجات فوق الصوتية</h3>
                    <p>الموجات فوق الصوتية تساعد في تشخيص حالات البطن، الحوض، الحمل، وأعضاء الجسم الأخرى بدقة عالية ومن منزلك.</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card service-card p-3 shadow-sm">
                    <img src="echo.jpg" class="card-img-top" alt="إيكو على القلب">
                    <h3>إيكو على القلب</h3>
                    <p>الإيكو يوفر فحصًا دقيقًا للقلب وصماماته لتشخيص أي مشاكل محتملة، مع تقارير طبية متخصصة.</p>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card service-card p-3 shadow-sm">
                    <img src="test.jpg" class="card-img-top" alt="تحاليل منزلية">
                    <h3>تحاليل منزلية</h3>
                    <p>نقدم خدمة التحاليل الطبية في المنزل، مما يسهل عليك إجراء الفحوصات دون الحاجة لزيارة المختبرات.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="bg-light py-5">
        <div class="container text-center">
            <h2>من نحن؟</h2>
            <p>نحن فريق طبي متخصص في تقديم خدمات الأشعة المنزلية باستخدام أحدث التقنيات لضمان راحتكم وسلامتكم.</p>
        </div>
    </section>

    <section id="contact" class="container py-5 text-center">
        <h2>اتصل بنا</h2>
        <p>تواصل معنا لحجز موعدك الآن!</p>
        <div class="d-flex justify-content-center gap-3 flex-wrap">
            <a href="https://wa.me/201040523540" class="btn btn-success">📩 تواصل عبر واتساب</a>
            <a href="tel:+201040523540" class="btn btn-primary">📞 اتصال هاتفي</a>
            <a href="https://www.facebook.com/NanoScanMedical" class="btn btn-info">📘 تواصل عبر فيسبوك</a>
        </div>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <p>جميع الحقوق محفوظة &copy; 2025 Nano Scan</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
