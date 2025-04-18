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
/* Design général */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  background-color: #ffffff;
  color: #222;
  transition: background-color 0.3s, color 0.3s;
  line-height: 1.7;
}

header {
  background-color: #e34c26;
  color: white;
  padding: 20px;
  text-align: center;
  position: relative;
}

header button {
  position: absolute;
  left: 20px;
  top: 20px;
  padding: 10px 15px;
  background-color: white;
  color: #e34c26;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-weight: bold;
}

main {
  padding: 20px;
  max-width: 900px;
  margin: auto;
}

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.html-image {
  width: 200px;
  margin-bottom: 20px;
}

.text {
  text-align: right;
}

footer {
  text-align: center;
  padding: 15px;
  background-color: #f2f2f2;
  margin-top: 40px;
}

/* Dark mode */
body.dark {
  background-color: #121212;
  color: #f0f0f0;
}

body.dark header {
  background-color: #1a1a1a;
  color: white;
}

body.dark footer {
  background-color: #1a1a1a;
}

body.dark header button {
  background-color: #333;
  color: white;
}p
