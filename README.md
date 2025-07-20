<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SN | خدمات تعليمية وتجارية</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" crossorigin="anonymous" />
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: Tahoma, sans-serif; margin: 0; background: #0f0f0f; color: #f5f5f5; line-height: 1.6; }

    header, nav, footer { background: #1a1a1a; color: white; text-align: center; padding: 20px; }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      border: 1px solid #d4af37;
      border-radius: 30px;
      padding: 10px 20px;
      background: rgba(255,255,255,0.05);
    }

    nav a { color: white; margin: 5px 15px; text-decoration: none; font-weight: bold; transition: color 0.3s; }
    nav a:hover { color: #d4af37; }

    .lang-switch { position: fixed; top: 10px; left: 10px; z-index: 9999; }
    .lang-switch select { padding: 5px 10px; border-radius: 5px; border: none; }

    .hero { background: #2b6777; color: white; text-align: center; padding: 60px 20px; }
    .hero h1 { font-size: 2.5rem; }
    .hero p { font-size: 1.2rem; }

    .btn {
      background: #d4af37;
      color: black;
      padding: 10px 20px;
      border: none;
      text-decoration: none;
      border-radius: 5px;
      margin: 10px;
      display: inline-block;
      font-weight: bold;
      cursor: pointer;
    }

    section { padding: 30px 20px; max-width: 1000px; margin: auto; }
    h2 { color: #d4af37; }
    ul { list-style: none; padding: 0; }
    li { margin: 10px 0; }

    .stats {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
    }

    .stats div {
      flex: 1 1 200px;
      text-align: center;
      margin: 10px;
      font-size: 1.2rem;
    }

    form input, form textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      width: 100%;
    }

    form button { cursor: pointer; }

    footer {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      padding: 30px;
      color: white;
      font-size: 0.9rem;
      background: #111;
    }

    .footer-section { flex: 1 1 200px; padding: 10px; }
    .footer-section h4 { color: #d4af37; }
    .footer-section a { color: white; text-decoration: none; display: block; margin: 5px 0; }
    .footer-section a:hover { color: #d4af37; }

    .footer-section i {
      color: white;
      transition: color 0.3s;
    }

    .footer-section i:hover {
      color: #d4af37;
    }
  </style>
</head>
<body>

<!-- Language Switcher -->
<div class="lang-switch">
  <select onchange="switchLanguage(event)">
    <option value="ar">العربية</option>
    <option value="en">English</option>
  </select>
</div>

<!-- Header -->
<header>
  <h1>SN</h1>
  <p data-ar="نبني القوة، نطلق الفعل، نوصل العالم." data-en="Building Strength, Action, Network.">نبني القوة، نطلق الفعل، نوصل العالم.</p>
</header>

<!-- Navigation -->
<nav>
  <a href="#services" data-ar="الخدمات" data-en="Services">الخدمات</a>
  <a href="#about" data-ar="من نحن" data-en="About">من نحن</a>
  <a href="#why" data-ar="لماذا SN؟" data-en="Why SN">لماذا SN؟</a>
  <a href="#stats" data-ar="إحصائيات" data-en="Stats">إحصائيات</a>
  <a href="#contact" data-ar="تواصل" data-en="Contact">تواصل</a>
</nav>

<!-- Hero -->
<section class="hero">
  <h1 data-ar="ابدأ تجارتك بثقة مع SN" data-en="Start Your Business with SN">ابدأ تجارتك بثقة مع SN</h1>
  <p data-ar="حلول تعليمية وسياحية وتجارية بين ماليزيا، تركيا، وأفريقيا" data-en="Educational, tourism & trade solutions between Malaysia, Turkey & Africa">حلول تعليمية وسياحية وتجارية بين ماليزيا، تركيا، وأفريقيا</p>
  <a class="btn" href="#contact" data-ar="تواصل معنا الآن" data-en="Contact Us Now">تواصل معنا الآن</a>
</section>

<!-- Services -->
<section id="services">
  <h2 data-ar="خدماتنا" data-en="Our Services">خدماتنا</h2>
  <h3>🇲🇾 ماليزيا | Malaysia</h3>
  <ul>
    <li> القبولات الجامعية | University admissions</li>
    <li> استخراج التأشيرات | Visa processing</li>
    <li> استقبال في المطار | Airport pickup</li>
    <li> سكن وخدمات ترجمة | Housing & translation</li>
  </ul>
  <h3>🇹🇷 تركيا | Turkey</h3>
  <ul>
    <li> جولات سياحية | Guided tours</li>
    <li> حجوزات فنادق وطيران | Hotel & flight bookings</li>
    <li> قبولات وتأشيرات | Admissions & visas</li>
  </ul>
  <h3>🌍 التجارة الدولية | Global Trade</h3>
  <ul>
    <li> استيراد وتوزيع منتجات غذائية، الكترونيات، ملابس | Import & distribution of food, electronics, fashion</li>
    <li> شحن إلى أفريقيا والخليج | Shipping to Africa & the Gulf</li>
  </ul>
</section>

<!-- Why SN -->
<section id="why">
  <h2>لماذا SN؟ | Why SN</h2>
  <ul>
    <li> شراكات قوية في ماليزيا وتركيا | Strong partnerships in Malaysia & Turkey</li>
    <li> حلول متكاملة للطلاب والتجار | Complete services for students & traders</li>
    <li> تركيز على الأسواق الناشئة | Focus on emerging markets</li>
    <li> دعم احترافي وشفاف | Professional and transparent support</li>
  </ul>
</section>

<!-- Stats -->
<section id="stats" class="stats">
  <div><strong>6+</strong><br>خدمات رئيسية | Core services</div>
  <div><strong>4+</strong><br>دول نخدمها | Countries served</div>
  <div><strong>24/7</strong><br>دعم مباشر | Support</div>
  <div><strong>100%</strong><br>رضا العملاء | Satisfaction</div>
</section>

<!-- About -->
<section id="about">
  <h2>من نحن | About Us</h2>
  <p>SN هي شركة مسجلة في ماليزيا تقدم حلولًا تعليمية، تجارية وسياحية تربط آسيا بأفريقيا والخليج.<br>
  SN is a registered company in Malaysia offering educational, commercial, and tourism solutions connecting Asia to Africa and the Gulf.</p>
</section>

<!-- Contact -->
<section id="contact">
  <h2>تواصل معنا | Contact Us</h2>
  <form onsubmit="sendToWhatsApp(); return false;" style="display: flex; flex-direction: column; gap: 15px;">
    <input type="text" id="name" placeholder="الاسم الكامل | Full Name" required>
    <input type="email" id="email" placeholder="البريد الإلكتروني | Email" required>
    <input type="text" id="phone" placeholder="رقم الهاتف | Phone Number" required>
    <textarea id="message" placeholder="اكتب رسالتك هنا | Your Message" required></textarea>
    <button class="btn" type="submit">إرسال عبر واتساب | Send via WhatsApp</button>
  </form>
</section>

<!-- Footer -->
<footer>
  <div class="footer-section">
    <h4>روابط | Links</h4>
    <a href="#services">الخدمات | Services</a>
    <a href="#about">من نحن | About</a>
    <a href="#contact">تواصل | Contact</a>
  </div>

  <div class="footer-section">
    <h4>خدماتنا | Our Services</h4>
    <a>قبولات جامعية | University Admissions</a>
    <a>تأشيرات | Visa Processing</a>
    <a>توزيع تجاري | Trade Distribution</a>
  </div>

  <div class="footer-section">
    <h4>تابعنا على | Follow us on</h4>
    <div style="font-size: 1.8rem; display: flex; gap: 15px;">
      <a href="#"><i class="fab fa-youtube"></i></a>
      <a href="https://facebook.com/exploresan"><i class="fab fa-facebook-f"></i></a>
      <a href="https://instagram.com/exploreturkeywithsn"><i class="fab fa-instagram"></i></a>
      <a href="#"><i class="fab fa-x-twitter"></i></a>
      <a href="#"><i class="fab fa-linkedin-in"></i></a>
    </div>
  </div>
</footer>

<!-- Scripts -->
<script>
function switchLanguage(event) {
  const lang = event.target.value;
  const html = document.documentElement;
  html.setAttribute('lang', lang);
  html.setAttribute('dir', lang === 'ar' ? 'rtl' : 'ltr');
  document.querySelectorAll('[data-ar][data-en]').forEach(el => {
    el.innerHTML = lang === 'ar' ? el.getAttribute('data-ar') : el.getAttribute('data-en');
  });
}

function sendToWhatsApp() {
  const name = document.getElementById("name").value;
  const email = document.getElementById("email").value;
  const phone = document.getElementById("phone").value;
  const message = document.getElementById("message").value;
  const text = `الاسم: ${name}%0Aالبريد: ${email}%0Aالهاتف: ${phone}%0Aالرسالة: ${message}`;
  const whatsappNumber = "905365648731";
  const url = `https://wa.me/${whatsappNumber}?text=${text}`;
  window.open(url, "_blank");
}
</script>

</body>
</html>
