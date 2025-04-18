<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>www.achourrayane.edu</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>بحث حول HTML</h1>
    <button id="toggle-theme">الوضع الليلي</button>
  </header>

  <main>
    <section class="content">
      <img src="https://www.htmlcsscolor.com/preview/gallery/000000.png" alt="HTML image" class="html-image">
      <div class="text">
        <h2>ما هي HTML؟</h2>
        <p>
          HTML هي لغة ترميز تُستخدم لإنشاء صفحات الويب. تُعتبر الأساس الذي تُبنى عليه جميع مواقع الإنترنت. تسمح HTML بتحديد العناوين، الفقرات، الروابط، الصور، والجداول وغيرها.
        </p>
        <h2>Qu'est-ce que HTML ?</h2>
        <p>
          HTML est un langage de balisage utilisé pour créer des pages web. C’est la base de tous les sites internet. Il permet de structurer les titres, paragraphes, liens, images, tableaux, etc.
        </p>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 www.achourrayane.edu - Tous droits réservés</p>
  </footer>

  <script>
    const btn = document.getElementById('toggle-theme');
    btn.onclick = () => {
      document.body.classList.toggle('dark');
      btn.textContent = document.body.classList.contains('dark') ? 'الوضع العادي' : 'الوضع الليلي';
    }
  </script>
</body>
</html>
