<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LARS — Climbing Themed</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Rock+Salt&family=Roboto:wght@400;700&display=swap');
    
    body {
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #4a3c31 0%, #8c7a63 100%);
      background-image:
        url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?ixlib=rb-4.0.3&auto=format&fit=crop&w=1280&q=80');
      background-size: cover;
      background-position: center;
      color: #f0ead8;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
      text-shadow: 1px 1px 3px #0009;
    }

    header {
      font-family: 'Rock Salt', cursive;
      font-size: 5rem;
      margin-bottom: 1rem;
      color: #e2d3b3;
      text-shadow:
        2px 2px 0 #4a3c31,
        4px 4px 10px #000a;
    }

    .dropdown {
      background: rgba(60, 50, 38, 0.85);
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.7);
      width: 320px;
      margin: 1rem auto;
      color: #dcd2b0;
      border: 2px solid #9c8a68;
    }

    details {
      padding: 1rem 1.5rem;
      cursor: pointer;
    }

    summary {
      font-weight: 700;
      font-size: 1.4rem;
      list-style: none;
      outline: none;
      position: relative;
      padding-left: 30px;
    }

    summary::-webkit-details-marker {
      display: none;
    }

    summary::before {
      content: '🧗';
      position: absolute;
      left: 0;
      top: 50%;
      transform: translateY(-50%);
      font-size: 1.6rem;
      transition: transform 0.3s ease;
    }

    details[open] summary::before {
      transform: translateY(-50%) rotate(90deg);
    }

    .dropdown-content {
      margin-top: 1rem;
      font-size: 1rem;
      line-height: 1.5;
      color: #e6dfc3;
      user-select: text;
    }

    a {
      color: #ffd27f;
      text-decoration: underline;
    }

    a:hover {
      color: #ffca3a;
    }

    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #d6caa7cc;
      text-align: center;
      user-select: none;
      text-shadow: none;
      position: relative;
      padding: 3rem 1rem 1rem;
      width: 100%;
      max-width: 600px;
      background:
        url('data:image/svg+xml;utf8,<svg fill="none" stroke="%23a3957e" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg"><path d="M4 60c0-14 28-36 28-36s28 22 28 36"/></svg>')
        no-repeat center bottom;
      background-size: 80% 60px;
      filter: contrast(0.7) brightness(0.5);
      opacity: 0.8;
      margin-left: auto;
      margin-right: auto;
      border-top: 1px solid rgba(255,255,255,0.1);
      box-shadow: inset 0 20px 20px -15px #0008;
    }
  </style>
</head>
<body>
  <header>LARS</header>

  <div class="dropdown">
    <details>
      <summary>About Me</summary>
      <div class="dropdown-content">
        Hi, I’m Lars — a climbing enthusiast and coach who lives for the thrill of the next challenge.  
        Whether it’s bouldering or lead climbing, I believe every climb is a new adventure.  
        Join me on the journey to reach new heights!
      </div>
    </details>
  </div>

  <div class="dropdown">
    <details>
      <summary>Contact</summary>
      <div class="dropdown-content">
        📧 Email: <a href="mailto:lars@example.com">lars@example.com</a><br />
        📱 Phone: (123) 456-7890<br />
        📍 Location: Flemington, NJ
      </div>
    </details>
  </div>

  <footer>© 2025 Lars</footer>
</body>
</html>
