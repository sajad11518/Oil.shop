<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>محل الزيوت الذهبي</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.rtl.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    body {
      background-color: #f9f9f9;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1605711285798-b1b3f14c0b63?auto=format&fit=crop&w=1470&q=80') center center/cover no-repeat;
      height: 400px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      background-color: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 10px;
    }
    .service-card img {
      height: 200px;
      object-fit: cover;
    }
  </style>
</head>
<body>

  <!-- العنوان -->
  <header class="hero">
    <div>
      <h1>محل الزيوت الذهبي</h1>
      <p>أفضل الزيوت وأجود الخدمات لسيارتك</p>
    </div>
  </header>

  <!-- شريط التنقل -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">الذهبي</a>
      <div class="collapse navbar-collapse show">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link" href="#services">الخدمات</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">اتصل بنا</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- الخدمات -->
  <section id="services" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">خدماتنا</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card service-card">
            <img src="https://images.unsplash.com/photo-1588854337221-c89c134ba76b?auto=format&fit=crop&w=800&q=80" class="card-img-top" alt="زيت المحرك">
            <div class="card-body">
              <h5 class="card-title">تغيير زيت المحرك</h5>
              <p class="card-text">نوفر أفضل الزيوت لسيارات البنزين والديزل.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card service-card">
            <img src="https://images.unsplash.com/photo-1614204424926-bc53eab7aab6?auto=format&fit=crop&w=800&q=80" class="card-img-top" alt="فلتر الزيت">
            <div class="card-body">
              <h5 class="card-title">تغيير فلتر الزيت</h5>
              <p class="card-text">نستخدم فلترات أصلية تضمن كفاءة المحرك.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card service-card">
            <img src="https://images.unsplash.com/photo-1610285975929-46ff0ec1917c?auto=format&fit=crop&w=800&q=80" class="card-img-top" alt="صيانة دورية">
            <div class="card-body">
              <h5 class="card-title">صيانة دورية</h5>
              <p class="card-text">فحص سريع للسيارة وتوصية بأفضل الحلول.</p>
            </div>
          </div>
        </div>
      </div>
      <div class="text-center mt-4">
        <button class="btn btn-warning" onclick="showMessage()">احجز موعدك الآن</button>
      </div>
    </div>
  </section>

  <!-- اتصل بنا -->
  <section id="contact" class="bg-dark text-white py-4">
    <div class="container text-center">
      <h3>اتصل بنا</h3>
      <p><i class="bi bi-geo-alt"></i> شارع الملك عبدالعزيز، الرياض</p>
      <p><i class="bi bi-telephone"></i> 0551234567</p>
      <p><i class="bi bi-envelope"></i> oilshop@example.com</p>
    </div>
  </section>

  <!-- الفوتر -->
  <footer class="text-center bg-secondary text-white py-3">
    <p>&copy; 2025 محل الزيوت الذهبي. جميع الحقوق محفوظة.</p>
  </footer>

  <script>
    function showMessage() {
      alert("تم استلام حجزك! سنتواصل معك قريبًا.");
    }
  </script>

</body>
</html>
