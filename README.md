<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>متجر جدة لمستلزمات القطط والببغاوات</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: 'Cairo', Arial, sans-serif;
      background: linear-gradient(135deg, #e0f7fa 60%, #fffde4 100%);
      margin: 0; padding: 0;
      direction: rtl;
      color: #333;
    }
    header {
      background: url('https://img.freepik.com/free-photo/cute-kitten-parrot_23-2148997246.jpg?size=1200') center/cover no-repeat;
      text-align: center;
      padding: 60px 20px 40px 20px;
      color: #fff;
      position: relative;
    }
    header:after {
      content: "";
      position: absolute; left: 0; top: 0; width: 100%; height: 100%;
      background: rgba(60, 60, 120, 0.25);
      z-index: 1;
    }
    header h1, header p { position: relative; z-index: 2; }
    nav {
      background: #f9fafc;
      border-bottom: 1px solid #c2e9fb;
      padding: 10px 0; overflow-x: auto;
      text-align: center;
    }
    nav a {
      display: inline-block;
      color: #333;
      text-decoration: none;
      padding: 8px 32px;
      font-weight: bold;
      transition: background 0.2s;
      border-radius: 25px;
      margin: 0 3px;
    }
    nav a:hover { background: #e1f5fe; }
    section { padding: 30px 10px; max-width: 900px; margin: 30px auto 0 auto; background: #fff; border-radius: 14px; box-shadow: 0 2px 12px #e0e0e0; }
    h2 { color: #4dd0e1; margin-top: 0; }
    .products { display: flex; flex-wrap: wrap; gap: 18px; }
    .product-card {
      flex: 1 1 220px;
      background: #fafafa;
      border-radius: 12px;
      box-shadow: 0 1px 5px #e0e0e0;
      padding: 14px; margin-bottom: 10px;
      min-width: 210px;
      position: relative;
    }
    .product-card span.emoji {
      font-size: 2.2em;
      position: absolute; top: 10px; left: 10px;
      opacity: .18;
    }
    .info-table { width:100%; border-collapse:collapse; }
    .info-table td { padding:6px 8px; border-bottom:1px solid #f1f1f1; }
    .contact {
      background: #e1f5fe;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    @media(max-width:700px) {
      .products { flex-direction:column; }
      section { margin: 10px; padding: 12px 4px}
      header { padding: 40px 6px 18px 6px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>🐾 متجر جدة لمستلزمات القطط والببغاوات 🦜</h1>
    <p>كل ما تحتاجه قطتك أو ببغاءك في مكان واحد بخدمة توصيل سريعة داخل جدة</p>
  </header>

  <nav>
    <a href="#cats">مستلزمات القطط</a>
    <a href="#parrots">مستلزمات الببغاوات</a>
    <a href="#offers">العروض</a>
    <a href="#bestsellers">الأكثر مبيعًا</a>
    <a href="#about">من نحن</a>
    <a href="#contact">تواصل معنا</a>
  </nav>

  <section id="cats" style="background-image: url('https://img.freepik.com/free-photo/beautiful-cat-portrait_23-2149214410.jpg?size=1200'); background-size: cover; background-position: right; background-repeat: no-repeat;">
    <h2>🐱 مستلزمات القطط</h2>
    <div class="products">
      <div class="product-card">
        <span class="emoji">🐾</span>
        <strong>طعام جاف للقطط</strong>
        <p>طعام متوازن غني بالفيتامينات والمعادن.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🛏️</span>
        <strong>سرير قطط فاخر</strong>
        <p>سرير مريح ودافئ بتصميم أنيق.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">⚽</span>
        <strong>لعبة كرة ملونة</strong>
        <p>كرة خفيفة وآمنة للعب القطط.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🧤</span>
        <strong>فرشاة تمشيط شعر</strong>
        <p>فرشاة لطيفة لفك التشابكات والعناية بالشعر.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🍽️</span>
        <strong>وعاء طعام مزدوج</strong>
        <p>وعاء بلاستيك صحي للطعام والماء.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🪨</span>
        <strong>رمل قطط معطر</strong>
        <p>رمل طبيعي معطر يدوم طويلاً.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🔔</span>
        <strong>طوق عنق مزخرف</strong>
        <p>طوق قطط مع جرس صغير وألوان جذابة.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🎒</span>
        <strong>حقيبة حمل قطط</strong>
        <p>حقيبة مريحة وآمنة لنقل القطة.</p>
        <b>السعر: </b>
      </div>
    </div>
  </section>

  <section id="parrots" style="background-image:url('https://img.freepik.com/free-photo/closeup-shot-colorful-parrot-tree-branch-blurred-background_181624-26040.jpg?size=1200'); background-size:cover; background-position:left; background-repeat:no-repeat;">
    <h2>🦜 مستلزمات الببغاوات</h2>
    <div class="products">
      <div class="product-card">
        <span class="emoji">🦜</span>
        <strong>قفص ببغاء متوسط</strong>
        <p>قفص معدني متين مع ملحقات أرجوحة ومجثم.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🌾</span>
        <strong>طعام بذور متنوعة</strong>
        <p>خلطة صحية لجميع أنواع الببغاوات.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🪀</span>
        <strong>لعبة أرجوحة خشبية</strong>
        <p>أرجوحة طبيعية وآمنة للتسلية.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🍽️</span>
        <strong>طبق طعام مزدوج</strong>
        <p>طبق مقاوم للبكتيريا سهل التنظيف.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🪶</span>
        <strong>فيتامينات للريش</strong>
        <p>مكملات غذائية لتعزيز صحة الريش.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🌳</span>
        <strong>مجثم طبيعي</strong>
        <p>مجثم من الخشب الطبيعي قابل للتثبيت.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🧳</span>
        <strong>علبة نقل ببغاء</strong>
        <p>علبة بلاستيكية متينة للانتقال الآمن.</p>
        <b>السعر: </b>
      </div>
      <div class="product-card">
        <span class="emoji">🎲</span>
        <strong>حلية ألعاب ملونة</strong>
        <p>ألعاب ترفيهية لتعزيز نشاط الببغاء.</p>
        <b>السعر: </b>
      </div>
    </div>
  </section>

  <section id="offers">
    <h2>✨ العروض الجديدة</h2>
    <ul>
      <li>عروض موسمية على طعام القطط والببغاوات</li>
      <li>خصومات على ألعاب القطط</li>
      <li>شحن مجاني عند الشراء بقيمة معينة</li>
      <li>هدية مجانية عند شراء قفص ببغاء</li>
    </ul>
  </section>

  <section id="bestsellers">
    <h2>⭐ الأكثر مبيعًا</h2>
    <ul>
      <li>طعام جاف للقطط</li>
      <li>قفص ببغاء متوسط</li>
      <li>لعبة أرجوحة خشبية</li>
    </ul>
  </section>

  <section id="about">
    <h2>ℹ️ من نحن</h2>
    <p>
      متجر جدة هو وجهتك الأولى لكل مستلزمات قططك وببغاواتك — منتجات أصلية، أسعار تنافسية، خدمة مميزة، وتوصيل سريع داخل جدة.<br>
      رؤيتنا: توفير حياة أفضل لحيوانك الأليف!
    </p>
  </section>

  <section id="contact" class="contact">
    <h2>📞 تواصل معنا</h2>
    <table class="info-table">
      <tr>
        <td>هاتف:</td>
        <td><a href="tel:0558223499">0558223499</a></td>
      </tr>
      <tr>
        <td>هاتف إضافي:</td>
        <td><a href="tel:0597205652">0597205652</a></td>
      </tr>
      <tr>
        <td>موقع المحل:</td>
        <td><a href="https://maps.app.goo.gl/uWSZjGikXRjwWmQi6" target="_blank">اضغط هنا للوصول عبر خرائط Google</a></td>
      </tr>
      <tr>
        <td>انستغرام:</td>
        <td>@petstore_jeddah</td>
      </tr>
    </table>
  </section>
</body>
</html>
