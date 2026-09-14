# Riva-coffee
⁠Digital menu for my coffee shop
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riva Coffee - Menu</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #1a1a1a;
            color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&w=1000&q=80');
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 40px 20px;
            border-bottom: 3px solid #d4af37;
        }
        header h1 {
            margin: 0;
            font-size: 2.2rem;
            color: #d4af37;
        }
        header p {
            margin: 10px 0 0;
            color: #ccc;
            font-size: 1rem;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            padding: 0 15px;
        }
        .category {
            margin-bottom: 30px;
        }
        .category h2 {
            border-bottom: 2px solid #d4af37;
            padding-bottom: 5px;
            color: #d4af37;
            font-size: 1.4rem;
        }
        .item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #2a2a2a;
            padding: 15px;
            margin: 10px 0;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }
        .item-info {
            flex-grow: 1;
        }
        .item-name {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 5px;
        }
        .item-desc {
            font-size: 0.85rem;
            color: #aaa;
        }
        .item-price {
            font-size: 1.1rem;
            font-weight: bold;
            color: #d4af37;
            margin-right: 15px;
        }
        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 0.8rem;
            border-top: 1px solid #333;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Riva Coffee</h1>
        <p>تشكيلة فاخرة من أجود أنواع القهوة والمشروبات</p>
    </header>

    <div class="container">
        <!-- قسم القهوة الساخنة -->
        <div class="category">
            <h2>القهوة الساخنة (Espresso Bar)</h2>
            
            <div class="item">
                <div class="item-info">
                    <div class="item-name">إسبريسو (Espresso)</div>
                    <div class="item-desc">شوت مركز وغني بنكهة أصلية</div>
                </div>
                <div class="item-price">3,000 د.ع</div>
            </div>

            <div class="item">
                <div class="item-info">
                    <div class="item-name">كابتشينو (Cappuccino)</div>
                    <div class="item-desc">إسبريسو مع حليب مبخر ورغوة غنية</div>
                </div>
                <div class="item-price">4,500 د.ع</div>
            </div>

            <div class="item">
                <div class="item-info">
                    <div class="item-name">لاتيه (Caffe Latte)</div>
                    <div class="item-desc">إسبريسو ناعم مع طبقات حليب كريمية</div>
                </div>
                <div class="item-price">5,000 د.ع</div>
            </div>
        </div>

        <!-- قسم القهوة المقطرة -->
        <div class="category">
            <h2>القهوة المقطرة (V60 & Pour Over)</h2>
            
            <div class="item">
                <div class="item-info">
                    <div class="item-name">في 60 (V60)</div>
                    <div class="item-desc">قهوة مختصة محضرة بالتقطير اليدوي بنكهات نقية</div>
                </div>
                <div class="item-price">6,000 د.ع</div>
            </div>
        </div>

        <!-- قسم المشروبات الباردة -->
        <div class="category">
            <h2>المشروبات الباردة (Cold Drinks)</h2>
            
            <div class="item">
                <div class="item-info">
                    <div class="item-name">آيس سبانش لاتيه (Iced Spanish Latte)</div>
                    <div class="item-desc">إسبريسو، حليب مكثف محلى وثلج</div>
                </div>
                <div class="item-price">6,000 د.ع</div>
            </div>

            <div class="item">
                <div class="item-info">
                    <div class="item-name">آيس أمريكانو (Iced Americano)</div>
                    <div class="item-desc">إسبريسو خفيف مع الماء المثلج</div>
                </div>
                <div class="item-price">4,000 د.ع</div>
            </div>
        </div>
    </div>

    <footer>
        <p>جميع الحقوق محفوظة © Riva Coffee 2026</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Riva Coffee - Menu</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0f172a;
            color: #f8fafc;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.8)), url('https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&w=1000&q=80');
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 40px 20px;
            border-bottom: 3px solid #38bdf8;
        }
        header h1 {
            margin: 0;
            font-size: 2.2rem;
            color: #38bdf8;
        }
        header p {
            margin: 10px 0 0;
            color: #94a3b8;
            font-size: 1rem;
        }
        .container {
            max-width: 600px;
            margin: 20px auto;
            padding: 0 15px;
        }
        .category {
            margin-bottom: 30px;
        }
        .category h2 {
            border-bottom: 2px solid #38bdf8;
            padding-bottom: 5px;
            color: #38bdf8;
            font-size: 1.4rem;
        }
        .item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #1e293b;
            padding: 15px;
            margin: 10px 0;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
            border-right: 4px solid #38bdf8;
        }
        .item-info {
            flex-grow: 1;
        }
        .item-name {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 5px;
            color: #f1f5f9;
        }
        .item-desc {
            font-size: 0.85rem;
            color: #94a3b8;
        }
        .item-price {
            font-size: 1.1rem;
            font-weight: bold;
            color: #38bdf8;
            margin-right: 15px;
        }
        footer {
            text-align: center;
            padding: 20px;
            color: #64748b;
            font-size: 0.8rem;
            border-top: 1px solid #1e293b;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Riva Coffee</h1>
        <p>تشكيلة فاخرة من أجود أنواع القهوة والمشروبات</p>
    </header>

    <div class="container">
        <!-- قسم القهوة الساخنة -->
        <div class="category">
            <h2>القهوة الساخنة (Espresso Bar)</h2>
            
            <div class="item">
                <div class="item-info">
                    <div class="item-name">إسبريسو (Espresso)</div>
                    <div class="item-desc">شوت مركز وغني بنكهة أصلية</div>
                </div>
                <div class="item-price">3,000 د.ع</div>
            </div>

            <div class="item">
                <div class="item-info">
                    <div class="item-name">كابتشينو (Cappuccino)</div>
                    <div class="item-desc">إسبريسو مع حليب مبخر ورغوة غنية</div>
                </div>
                <div class="item-price">4,500 د.ع</div>
            </div>

            <div class="item">
                <div class="item-info">
                    <div class="item-name">لاتيه (Caffe Latte)</div>
                    <div class="item-desc">إسبريسو ناعم مع طبقات حليب كريمية</div>
                </div>
                <div class="item-price">5,000 د.ع</div>
            </div>
        </div>

        <!-- قسم القهوة المقطرة -->
        <div class="category">
            <h2>القهوة المقطرة (V60 & Pour Over)</h2>
            
            <div class="item">
                <div class="item-info">
                    <div class="item-name">في 60 (V60)</div>
                    <div class="item-desc">قهوة مختصة محضرة بالتقطير اليدوي بنكهات نقية</div>
                </div>
                <div class="item-price">6,000 د.ع</div>
            </div>
        </div>

        <!-- قسم المشروبات الباردة -->
        <div class="category">
            <h2>المشروبات الباردة (Cold Drinks)</h2>
            
            <div class="item">
                <div class="item-info">
                    <div class="item-name">آيس سبانش لاتيه (Iced Spanish Latte)</div>
                    <div class="item-desc">إسبريسو، حليب مكثف محلى وثلج</div>
                </div>
                <div class="item-price">6,000 د.ع</div>
            </div>

            <div class="item">
                <div class="item-info">
                    <div class="item-name">آيس أمريكانو (Iced Americano)</div>
                    <div class="item-desc">إسبريسو خفيف مع الماء المثلج</div>
                </div>
                <div class="item-price">4,000 د.ع</div>
            </div>
        </div>
    </div>

    <footer>
        <p>جميع الحقوق محفوظة © Riva Coffee 2026</p>
    </footer>

</body>
</html>
