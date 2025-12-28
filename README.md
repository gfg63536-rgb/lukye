<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بوابة حذيفة للمقالات | Huzaifa Articles</title>
    <style>
        :root {
            --main-color: #0056b3;
            --text-color: #333;
            --bg-color: #f0f2f5;
            --ad-bg: #e2e2e2;
        }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: var(--bg-color); margin: 0; color: var(--text-color); }
        
        header { background: white; border-bottom: 3px solid var(--main-color); padding: 15px 0; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .logo { font-size: 28px; font-weight: bold; color: var(--main-color); text-decoration: none; }

        .container { max-width: 1100px; margin: 20px auto; display: grid; grid-template-columns: 3fr 1fr; gap: 20px; padding: 0 15px; }

        /* أماكن الإعلانات */
        .ad-box { background: var(--ad-bg); border: 1px dashed #999; text-align: center; padding: 10px; margin-bottom: 20px; color: #666; font-size: 14px; }
        .top-ad { max-width: 970px; margin: 20px auto; min-height: 90px; }

        /* تصميم المقالات */
        .article-card { background: white; margin-bottom: 20px; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        .article-img { width: 100%; height: 200px; background: #ddd; display: flex; align-items: center; justify-content: center; color: #999; }
        .article-body { padding: 20px; }
        .article-body h2 { margin-top: 0; color: var(--main-color); }
        .read-more { display: inline-block; background: var(--main-color); color: white; padding: 8px 15px; border-radius: 5px; text-decoration: none; margin-top: 10px; }

        /* القائمة الجانبية */
        .sidebar-box { background: white; padding: 15px; border-radius: 8px; margin-bottom: 20px; }
        .sidebar-box h3 { border-right: 4px solid var(--main-color); padding-right: 10px; margin-top: 0; }

        @media (max-width: 768px) { .container { grid-template-columns: 1fr; } }
    </style>
</head>
<body>

<header>
    <a href="#" class="logo">مدونة حذيفة الإخبارية</a>
</header>

<div class="ad-box top-ad">إعلان علوي (يظهر للجميع عند الدخول)</div>

<div class="container">
    <main>
        <article class="article-card">
            <div class="article-img">صورة المقال هنا</div>
            <div class="article-body">
                <h2>أفضل 5 طرق للربح من الإنترنت في 2025</h2>
                <p>في هذا المقال سنتعرف على كيفية بناء مصدر دخل حقيقي من خلال التدوين ووضع الإعلانات...</p>
                <a href="#" class="read-more">إقرأ المزيد</a>
            </div>
        </article>

        <div class="ad-box">إعلان وسط المحتوى (لزيادة عدد النقرات)</div>

        <article class="article-card">
            <div class="article-img">صورة المقال هنا</div>
            <div class="article-body">
                <h2>كيف تختار تخصص موقعك (النيش) لجذب المعلنين</h2>
                <p>اختيار التخصص الصحيح هو السر وراء القبول السريع في جوجل أدسنس وبرامج الإعلانات الأخرى...</p>
                <a href="#" class="read-more">إقرأ المزيد</a>
            </div>
        </article>
    </main>

    <aside>
        <div class="sidebar-box">
            <h3>عن الكاتب</h3>
            <p>موقع حذيفة المتخصص في تقديم أفضل المقالات التقنية والربحية.</p>
        </div>

        <div class="ad-box" style="height: 300px;">إعلان جانبي ثابت</div>

        <div class="sidebar-box">
            <h3>أقسام الموقع</h3>
            <ul>
                <li>تقنية</li>
                <li>ربح من الإنترنت</li>
                <li>ريادة أعمال</li>
            </ul>
        </div>
    </aside>
</div>

<footer style="text-align: center; padding: 20px; background: #333; color: white;">
    <p>جميع الحقوق محفوظة لموقع حذيفة &copy; 2025</p>
</footer>

</body>
</html>

