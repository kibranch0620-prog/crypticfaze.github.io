/index.html
/blogs.html
/blogs/
   post1.html
   post2.html
   ...
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FutureStacks Studios</title>
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
    }
  </style>
</head>
<body>
  <header>
    <h1>FutureStacks Studios</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="blogs.html">Blogs</a>
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




<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Applied Cryptography Blog</title>
  <style>
    body {
      margin: 0;
      background: #18181b;
      color: #f4f4f5;
      font-family: 'Segoe UI', Arial, sans-serif;
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
    }
    nav a:hover {
      color: #f59e42;
    }
    main {
      max-width: 900px;
      margin: 3rem auto;
      background: #232328;
      padding: 2rem;
      border-radius: 1rem;
    }
    h2 {
      color: #38bdf8;
    }
  </style>
</head>

<body>
  <header>
    <h1>Blog Post</h1>
    <nav>
      <a href="../index.html">Home</a>
      <a href="../blogs.html">Blogs</a>
      <a href="#">Projects</a>
    </nav>
  </header>

  <main>
    <h2>Understanding AES Encryption and Why It Remains Critical in Modern Cybersecurity</h2>

    <p>
      12/1/2025: Encryption plays a huge role in cybersecurity, especially with how often data is stolen or intercepted today. One of the most important encryption algorithms we rely on is the Advanced Encryption Standard (AES). It’s used almost everywhere on Wi-Fi networks, messaging apps, VPNs, cloud services, and even in hardware like smartphones and laptops. AES is a symmetric encryption algorithm, meaning it uses the same key to encrypt and decrypt data. This makes it fast and efficient, which is one reason it replaced the older DES algorithm back in 2001. AES works with 128-bit, 192-bit, or 256-bit keys, and the higher the key size, the stronger the security. AES-256, for example, is still considered extremely strong even with today’s powerful computers. To understand what AES actually does, it's helpful to look at the basic structure. AES works on 128-bit blocks of data and goes through multiple rounds of transformations that scramble the data until it becomes unreadable without the key. Each round includes steps like SubBytes, ShiftRows, and MixColumns, which all add confusion and complexity to the encrypted output. The goal is to make the ciphertext so scrambled that no attacker can reverse it or guess the key through brute force.
    </p>

 <p>Below is a simple Python example showing how AES encryption works using the PyCryptodome library.</p>

  <pre style="background:#1e1e1e; color:#f4f4f5; padding:1rem; border-radius:0.5rem; overflow-x:auto;">
  <code>
from Crypto.Cipher import AES
from Crypto.Random import get_random_bytes

key = get_random_bytes(16)
cipher = AES.new(key, AES.MODE_EAX)

plaintext = b"Hello, AES encryption!"
ciphertext, tag = cipher.encrypt_and_digest(plaintext)

print("Ciphertext:", ciphertext)
  </code>
  </pre>
</main>

  
  </main>
</body>
</html>

