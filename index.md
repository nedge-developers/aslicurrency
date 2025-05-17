<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
<title> AsliCurrency</title>
 
  <meta name="viewport" content="width=device-width, initial-scale=1">

    /* Gallery of banners */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 0.5rem;
      margin-bottom: 2rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 4px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
}
    /* Centered download section */
    .download-section {
      text-align: center;
      margin: 2rem 0;
    }
    .download-section .button {
      display: inline-block;
      padding: 0.8em 1.8em;
      background: #0066cc;
      color: #fff;
      text-decoration: none;
      font-size: 1.1rem;
      border-radius: 4px;
      transition: background 0.25s ease;
    }
    .download-section .button:hover {
      background: #004999;
    }
}
    /* Steps styling */
    .steps {
      max-width: 600px;
      margin: 0 auto 2rem;
      list-style: none;
      counter-reset: step;
    }
    .steps li {
      position: relative;
      padding-left: 3rem;
      margin-bottom: 1.5rem;
    }
    .steps li::before {
      counter-increment: step;
      content: counter(step);
      position: absolute;
      left: 0; top: 0;
      width: 2rem; height: 2rem;
      border-radius: 50%;
      background: #0066cc;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
    }
}
    /* Privacy link */
    .footer {
      text-align: center;
      margin-top: 3rem;
    }
    .footer .link {
      color: #0066cc;
      text-decoration: none;
    }
    .footer .link:hover {
      text-decoration: underline;
    }
    
  </style>
</head>
<body>

  <!-- Banners -->
  <div class="gallery">
    <img src="/css/assets/top1.jpg" alt="Top banner">
    <img src="/css/assets/top2.jpg" alt="Mid banner 1">
    <img src="/css/assets/top3.jpg" alt="Mid banner 2">
    <img src="/css/assets/top4.jpg" alt="Mid banner 3">
    <img src="/css/assets/top5.jpg" alt="Mid banner 4">
    <img src="/css/assets/top6.jpg" alt="Mid banner 5">
    <img src="/css/assets/top7.jpg" alt="Mid banner 6">
    <img src="/css/assets/top8.jpg" alt="Mid banner 7">
    <img src="/css/assets/top9.jpg" alt="Mid banner 8">
    <img src="/css/assets/top10.jpg" alt="Mid banner 9">
  </div>

  <!-- Install steps -->
  <ol class="steps">
    <li>When prompted, click “Enable installations from unknown sources.”</li>
    <li>You can also manually enable it in your device settings:<br>
        <em>Settings → Security → Unknown sources</em>
    </li>
    <li>Once downloaded, open the APK file and follow the install prompts.</li>
  </ol>

  <!-- Download button -->
  <div class="download-section">
    <a class="button"
       href="https://github.com/nedge-developers/aslicurrency/releases/download/v2.0/Aslicurrency.apk"
       target="_blank" rel="noopener">
      Download AsliCurrency APP
    </a>
  </div>

  <!-- More banners if needed -->
  <div class="gallery">
    <img src="/css/assets/top11.jpg" alt="Banner">
    <img src="/css/assets/top12.jpg" alt="Banner">
    <img src="/css/assets/top13.jpg" alt="Banner">
    <img src="/css/assets/top14.jpg" alt="Banner">
  </div>

  <!-- Footer -->
  <div class="footer">
    <a href="/privacy/" class="link">Privacy Policy</a>
  </div>

</body>
</html>
