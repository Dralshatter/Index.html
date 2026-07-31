# Index.html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>د. علياء الشاطر | الأبحاث والمشاريع العلمية</title>
    <!-- استدعاء خط عربي أنيق -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #1e3a8a;
            --primary-light: #3b82f6;
            --accent: #0d9488;
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
            --text-main: #1f2937;
            --text-muted: #6b7280;
            --border: #e5e7eb;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Cairo', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.7;
            padding-bottom: 60px;
        }

        header {
            background: linear-gradient(135deg, var(--primary), #1e293b);
            color: white;
            padding: 50px 20px;
            text-align: center;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
        }

        header h1 {
            font-size: 2.2rem;
            font-weight: 700;
            margin-bottom: 8px;
        }

        header p {
            font-size: 1.1rem;
            color: #93c5fd;
            font-weight: 300;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 25px;
            flex-wrap: wrap;
        }

        nav a {
            color: white;
            text-decoration: none;
            background: rgba(255, 255, 255, 0.1);
            padding: 8px 18px;
            border-radius: 20px;
            font-size: 0.95rem;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        nav a:hover {
            background: rgba(255, 255, 255, 0.25);
            transform: translateY(-2px);
        }

        .container {
            max-width: 850px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .section-title {
            font-size: 1.4rem;
            color: var(--primary);
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 8px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            right: 0;
            width: 50px;
            height: 3px;
            background-color: var(--accent);
            border-radius: 2px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 22px;
            margin-bottom: 20px;
            border: 1px solid var(--border);
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.03);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }

        .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.06);
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 8px;
        }

        .card-title {
            font-size: 1.15rem;
            font-weight: 700;
            color: var(--primary);
        }

        .badge {
            background: #e0f2fe;
            color: #0369a1;
            padding: 3px 10px;
            border-radius: 10px;
            font-size: 0.85rem;
            font-weight: 600;
        }

        .card-meta {
            font-size: 0.88rem;
            color: var(--text-muted);
            margin-bottom: 10px;
        }

        .card-desc {
            font-size: 0.95rem;
            color: #4b5563;
        }

        .contact-links {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
            margin-top: 15px;
        }

        .contact-btn {
            display: inline-flex;
            align-items: center;
            padding: 9px 18px;
            background: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 0.9rem;
            transition: background 0.3s;
        }

        .contact-btn:hover {
            background: var(--primary-light);
        }

        footer {
            text-align: center;
            padding: 25px;
            color: var(--text-muted);
            font-size: 0.88rem;
            border-top: 1px solid var(--border);
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <!-- الهيدر والاسم -->
    <header>
        <h1>د. علياء الشاطر</h1>
        <p>طب وجراحة الفم والأسنان | أبحاث ودراسات سريرية</p>
        <nav>
            <a href="#about">عنّي</a>
            <a href="#research">الأبحاث</a>
            <a href="#projects">المشاريع</a>
            <a href="#contact">التواصل</a>
        </nav>
    </header>

    <div class="container">

        <!-- قسم نبذة -->
        <section id="about" style="margin-bottom: 35px;">
            <h2 class="section-title">نبذة تعريفية</h2>
            <div class="card">
                <p class="card-desc">
                    مهتمة بالبحث العلمي والتصميم والتحليل الإحصائي للدراسات السريرية، مع التركيز على تقديم أبحاث وطرح طبي مبني على الأدلة والبراهين الحقيقية.
                </p>
            </div>
        </section>

        <!-- قسم الأبحاث -->
        <section id="research" style="margin-bottom: 35px;">
            <h2 class="section-title">الأبحاث والدراسات العلمية</h2>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-title">دراسة استقصائية حول الممارسات السريرية</div>
                    <span class="badge">2026</span>
                </div>
                <div class="card-meta">بحث سريري ميداني | تحليل إحصائي متعدد المتغيرات</div>
                <p class="card-desc">
                    دراسة ميدانية تهدف لتقييم الممارسات وتحليل البيانات الديموغرافية المتعددة باستخدام النماذج الإحصائية المتقدمة.
                </p>
            </div>

            <div class="card">
                <div class="card-header">
                    <div class="card-title">عنوان الورقة البحثية الثانية</div>
                    <span class="badge">2025</span>
                </div>
                <div class="card-meta">المجلة العلمية / الملتقى الأكاديمي</div>
                <p class="card-desc">
                    ملخص قصير ومختصر يشرح الهدف الرئيسي من الدراسة والنتيجة الأساسية في سطرين فقط.
                </p>
            </div>
        </section>

        <!-- قسم المشاريع -->
        <section id="projects" style="margin-bottom: 35px;">
            <h2 class="section-title">المشاريع والمبادرات</h2>
            
            <div class="card">
                <div class="card-header">
                    <div class="card-title">التوعية بصحة الفم والأسنان</div>
                    <span class="badge">توعية صحية</span>
                </div>
                <p class="card-desc">
                    إعداد أدوات ومحتوى توعوي مبسط لتعزيز صحة الفم والأسنان لدى الأطفال والمرضى.
                </p>
            </div>
        </section>

        <!-- قسم التواصل -->
        <section id="contact">
            <h2 class="section-title">التواصل</h2>
            <div class="card">
                <p class="card-desc">للتواصل والتعاون الأكاديمي والبحثي:</p>
                <div class="contact-links">
                    <a href="mailto:your-email@gmail.com" class="contact-btn">البريد الإلكتروني</a>
                    <a href="https://linkedin.com" target="_blank" class="contact-btn" style="background:#0077b5;">LinkedIn</a>
                </div>
            </div>
        </section>

    </div>

    <footer>
        © 2026 د. علياء الشاطر - جميع الحقوق محفوظة
    </footer>

</body>
</html>
