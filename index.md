<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AsliCurrency</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    /* Body styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      max-width: 900px;
      margin: 0 auto;
      line-height: 1.6;
    }
    
    /* Gallery styles */
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin-bottom: 30px;
    }
    
    .gallery img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    
    /* Steps styles */
    .steps {
      background-color: #f9f9f9;
      padding: 20px 40px;
      border-radius: 8px;
      margin-bottom: 30px;
    }
    
    .steps li {
      margin-bottom: 15px;
    }
    
    /* Download section styles */
    .download-section {
      text-align: center;
      margin: 40px 0;
    }
    
    .button {
      display: inline-block;
      background-color: #4CAF50;
      color: white;
      padding: 15px 30px;
      text-decoration: none;
      border-radius: 4px;
      font-size: 18px;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    
    .button:hover {
      background-color: #45a049;
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
    <img src="/api/placeholder/400/200" alt="Top banner">
    <img src="/api/placeholder/400/200" alt="Mid banner 1">
    <img src="/api/placeholder/400/200" alt="Mid banner 2">
    <img src="/api/placeholder/400/200" alt="Mid banner 3">
    <img src="/api/placeholder/400/200" alt="Mid banner 4">
    <img src="/api/placeholder/400/200" alt="Mid banner 5">
    <img src="/api/placeholder/400/200" alt="Mid banner 6">
    <img src="/api/placeholder/400/200" alt="Mid banner 7">
    <img src="/api/placeholder/400/200" alt="Mid banner 8">
    <img src="/api/placeholder/400/200" alt="Mid banner 9">
  </div>
  
  <!-- Install steps -->
  <ol class="steps">
    <li>When prompted, click "Enable installations from unknown sources."</li>
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
    <img src="/api/placeholder/400/200" alt="Banner">
    <img src="/api/placeholder/400/200" alt="Banner">
    <img src="/api/placeholder/400/200" alt="Banner">
    <img src="/api/placeholder/400/200" alt="Banner">
  </div>
  
  <!-- Footer -->
  <div class="footer">
    <a href="/privacy/" class="link">Privacy Policy</a>
  </div>
</body>
</html>
