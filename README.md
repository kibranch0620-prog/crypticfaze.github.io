
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CrypticFaze</title>
  <style>
    body {
      margin: 0;
      background: #18181b;
      color: #f4f4f5;
      font-family: 'Segoe UI', Arial, sans-serif;
      min-height: 100vh;
    }
    header {
      background: #27272a;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: .05em;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-top: 1rem;
    }
    nav a {
      color: #fbbf24;
      text-decoration: none;
      font-weight: bold;
      transition: color .2s;
    }
    nav a:hover {
      color: #f59e42;
    }
    main {
      max-width: 800px;
      margin: 3rem auto 0;
      background: #232328;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 8px 32px rgba(0,0,0,0.25);
    }
    h2 {
      color: #38bdf8;
      margin-bottom: 1rem;
    }
    p {
      font-size: 1.1rem;
      line-height: 1.8;
    }
  </style>
</head>
<body>
  <header>
    <h1>FutureStacks Studios</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Blogs</a>
      <a href="#">Projects</a>
    </nav>
  </header>
  <main>
    <h2>Welcome!</h2>
    <p>This is my personal website where I post my Blogs and Projects.</p>
  </main>
</body>
</html>

# crypticfaze.github.io
Name: Kindrik Branch

Description: Bachelor of Science Degree in Cybersecurity at Chestnut Hill College, where I have developed a strong academic foundation in computer hardware, networking, digital forensics, and applied operating systems. 

LinkedIn: https://www.linkedin.com/in/kindrik-branch-789778327?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app

<div class="blog-post">
  <div class="blog-title">Understanding AES Encryption and Why It Remains Critical in Modern Cybersecurity</div>
  <div class="blog-date">Dec 1, 2025</div>
  <p>This is the content of my new blog post...</p>
</div>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
  <title>Minimal Dark Theme</title>
  <style>
    body {
      margin: 0;
      background: #18181b;
      color: #f4f4f5;
      font-family: 'Segoe UI', Arial, sans-serif;
      min-height: 100vh;
    }
    header {
      background: #27272a;
      padding: 2rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-top: 1rem;
    }
    nav a {
      color: #fbbf24;
      text-decoration: none;
      font-weight: bold;
      transition: color .2s;
      cursor: pointer;
    }
    nav a:hover {
      color: #f59e42;
    }
    main {
      max-width: 800px;
      margin: 3rem auto 0;
      background: #232328;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 8px 32px rgba(0,0,0,0.25);
    }
    .blog-section {
      display: none;
      margin-top: 2rem;
    }
    .blog-post {
      margin-bottom: 2rem;
      border-bottom: 1px solid #29292e;
      padding-bottom: 1.5rem;
    }
    .blog-title {
      color: #38bdf8;
      font-size: 1.5rem;
      margin: 1rem 0 0.5rem;
    }
    .blog-date {
      color: #fbbf24;
      font-size: 0.9rem;
      margin-bottom: 0.5rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Minimal Dark Theme</h1>
    <nav>
      <a href="#" onclick="showBlogs(event)">Blogs</a>
      <a href="#">Portfolio</a>
      <a href="#">Contact</a>
    </nav>
  </header>
  <main>
    <div id="welcome">
      <h2>Welcome!</h2>
      <p>This is a sleek, minimal dark website theme. Click "Blogs" to see blog posts.</p>
    </div>
    <div class="blog-section" id="blogSection">
      <h2>My Blog</h2>
      <div class="blog-post">
        <div class="blog-title">How I Designed My Minimal Website</div>
        <div class="blog-date">Dec 2, 2025</div>
        <p>This blog post describes my process for designing a minimal dark theme website...</p>
      </div>
      <div class="blog-post">
        <div class="blog-title">Tips for Writing CSS Like a Pro</div>
        <div class="blog-date">Nov 29, 2025</div>
        <p>Here are some of my favorite tips for writing efficient and clean CSS...</p>
      </div>
      <!-- Add more blog posts here -->
    </div>
  </main>
  <script>
    function showBlogs(event) {
      event.preventDefault(); // Prevents page from jumping to the top
      document.getElementById('blogSection').style.display = 'block';
      // Optionally hide other content
      document.getElementById('welcome').style.display = 'none';
    }
  </script>
</body>
</html>
