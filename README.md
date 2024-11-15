<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MT-shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            direction: rtl;
        }
        .toolbar {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        .toolbar h1 {
            margin: 0;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        .section {
            width: 80%;
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.1);
        }
        .section h2 {
            margin-top: 0;
            color: #333;
        }
        .comments-section, .latest-posts-section, .important-items-section {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
    <!-- Toolbar -->
    <div class="toolbar">
        <h1>MT-shop</h1>
    </div>

    <!-- Main Container -->
    <div class="container">
        <!-- Comments Section -->
        <div class="section comments-section">
            <h2>التعليقات</h2>
            <p>شارك برأيك حول منتجاتنا وخدماتنا!</p>
            <textarea placeholder="اكتب تعليقك هنا..." rows="4" style="width: 100%;"></textarea>
            <button style="margin-top: 10px; padding: 10px;">إرسال</button>
        </div>

        <!-- Latest Posts Section -->
        <div class="section latest-posts-section">
            <h2>آخر المشاركات</h2>
            <ul>
                <li>إطلاق مجموعة الشتاء الجديدة</li>
                <li>أفضل نصائح للعناية بالملابس</li>
                <li>كيف تختار ملابسك المناسبة لهذا الموسم</li>
            </ul>
        </div>

        <!-- Important Items Section -->
        <div class="section important-items-section">
            <h2>أهم العناصر</h2>
            <ul>
                <li>جاكيتات شتوية عالية الجودة</li>
                <li>ملابس صيفية بأسعار مخفضة</li>
                <li>أحذية رياضية مريحة</li>
            </ul>
        </div>
    </div>
</body>
</html>
