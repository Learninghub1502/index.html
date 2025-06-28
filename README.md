# index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Learning Hub - Free Learning Platform</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background: #0056b3;
      padding: 0.5rem;
      display: flex;
      justify-content: center;
      gap: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .card {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin-bottom: 1.5rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #007bff;
      color: white;
      margin-top: 2rem;
    }
    h2, h3 {
      color: #333;
    }
    .urdu {
      font-family: 'Noto Nastaliq Urdu', serif;
      direction: rtl;
      text-align: right;
      color: #444;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <h1>Learning Hub - Free Learning Platform</h1>
    <p>Learn anything, anytime - in English & Urdu</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#videos">Videos</a>
    <a href="#notes">Notes</a>
    <a href="#quizzes">Quizzes</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="home" class="card">
      <h2>Welcome to Learning Hub</h2>
      <p>This platform provides free educational material for general learners, including video tutorials, notes, quizzes, and more.</p>
      <p class="urdu">یہ ویب سائٹ ہر عمر کے طلباء کے لیے تعلیمی مواد فراہم کرتی ہے۔</p>
    </section>

    <section id="videos" class="card">
      <h3>Video Tutorials</h3>
      <ul>
        <li><a href="https://www.youtube.com" target="_blank">Mathematics (Urdu/English)</a></li>
        <li><a href="https://www.youtube.com" target="_blank">Science Concepts</a></li>
        <li><a href="https://www.youtube.com" target="_blank">English Vocabulary</a></li>
      </ul>
    </section>

    <section id="notes" class="card">
      <h3>Download Notes</h3>
      <ul>
        <li><a href="#">Class Notes (PDF)</a></li>
        <li><a href="#">Solved Examples</a></li>
        <li><a href="#">Formulas & Tips</a></li>
      </ul>
    </section>

    <section id="quizzes" class="card">
      <h3>Interactive Quizzes</h3>
      <p>Test your knowledge with basic and advanced level quizzes. More coming soon!</p>
    </section>

    <section id="contact" class="card">
      <h3>Contact Us</h3>
      <p>Email: support@learninghub.com</p>
      <p class="urdu">رابطہ کے لیے ہمیں ای میل کریں۔</p>
    </section>
  </div>

  <footer>
    &copy; 2025 Learning Hub - All Rights Reserved | Created by Farhan Ali
  </footer>
</body>
</html>
