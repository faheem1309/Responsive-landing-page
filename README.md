<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flowly — Animated README</title>
  <style>
    /* Base Styles */
    body {
      font-family: 'Arial', sans-serif;
      background: #f4f6ff;
      color: #222;
      margin: 0;
      padding: 30px;
      line-height: 1.6;
    }

    h1, h2, h3 {
      color: #6c63ff;
      margin-bottom: 10px;
    }

    h1 { font-size: 2.5rem; }
    h2 { font-size: 1.8rem; margin-top: 30px; }
    h3 { font-size: 1.4rem; margin-top: 20px; }

    p, li {
      margin-bottom: 10px;
    }

    ul {
      margin-left: 20px;
    }

    a {
      color: #6c63ff;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #857dff;
    }

    .section {
      background: #fff;
      padding: 25px;
      margin-bottom: 30px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.05);
      transform: translateY(30px);
      opacity: 0;
      animation: fadeSlide 0.8s forwards;
    }

    .section:nth-child(1) { animation-delay: 0.1s; }
    .section:nth-child(2) { animation-delay: 0.3s; }
    .section:nth-child(3) { animation-delay: 0.5s; }
    .section:nth-child(4) { animation-delay: 0.7s; }
    .section:nth-child(5) { animation-delay: 0.9s; }
    .section:nth-child(6) { animation-delay: 1.1s; }
    .section:nth-child(7) { animation-delay: 1.3s; }

    @keyframes fadeSlide {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    .highlight {
      color: #6c63ff;
      font-weight: bold;
    }

    pre {
      background: #eee;
      padding: 12px;
      border-radius: 6px;
      overflow-x: auto;
    }

  </style>
</head>
<body>

  <div class="section">
    <h1>Flowly — Motion-Rich Responsive Landing Page</h1>
    <p><span class="highlight">Flowly</span> is a <span class="highlight">responsive, interactive landing page</span> designed to demonstrate clean UI, continuous motion, and subtle animations.  
    It is a fictional brand project created for <span class="highlight">portfolio and learning purposes</span>.</p>
  </div>

  <div class="section">
    <h2>🎨 Key Features</h2>
    <ul>
      <li><strong>Responsive Layout:</strong> Flexbox and media queries ensure desktop, tablet, and mobile compatibility.</li>
      <li><strong>Hero Section:</strong> Gradient background with animated text and interactive buttons.</li>
      <li><strong>Floating Elements:</strong> Cards, logo, and hero text continuously float for subtle motion.</li>
      <li><strong>Interactive Cards:</strong> Cards respond to hover and mouse movement.</li>
      <li><strong>Pulsing CTA Buttons:</strong> Gentle animations guide attention.</li>
      <li><strong>Navigation:</strong> Smooth underline transitions on hover.</li>
      <li><strong>Accessibility:</strong> Keyboard focus indicators with <code>:focus-visible</code>.</li>
      <li><strong>SVG Logo:</strong> Resolution-independent, vector-based logo integrated with motion.</li>
      <li><strong>GSAP Animations:</strong> Smooth page load, scroll, and floating effects.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠 Tech Stack</h2>
    <ul>
      <li>HTML5 — Semantic and structured content</li>
      <li>CSS3 — Styling, transitions, keyframe animations, responsive layouts</li>
      <li>Vanilla JavaScript — DOM interactivity and motion handling</li>
      <li>SVG — Scalable logo design</li>
      <li>GSAP — Smooth animations and floating effects</li>
      <li>GSAP ScrollTrigger — Scroll-based animations (ready for future enhancements)</li>
    </ul>
  </div>

  <div class="section">
    <h2>💡 User Experience & Motion Design</h2>
    <ul>
      <li>Continuous floating of hero text, logo, and cards for subtle life-like motion.</li>
      <li>Staggered entrance animations for sections and elements on page load.</li>
      <li>Pulsing buttons draw attention without being distracting.</li>
      <li>Hover effects on cards for interactive depth and engagement.</li>
      <li>Gradient backgrounds and soft shadows to maintain elegance.</li>
    </ul>
  </div>

  <div class="section">
    <h2>📱 Responsive Design</h2>
    <ul>
      <li>Seamless scaling on all screen sizes.</li>
      <li>Cards stack vertically on smaller screens for readability.</li>
      <li>Typography and spacing adapt smoothly without breaking layout.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🌐 Links</h2>
    <ul>
      <li><strong>Live Demo:</strong> <a href="https://responsive-landing-page-three-gilt.vercel.app" target="_blank">responsive-landing-page-three-gilt.vercel.app</a></li>
      <li><strong>GitHub Repository:</strong> <a href="https://github.com/faheem1309/Responsive-landing-page.git" target="_blank">github.com/faheem1309/Responsive-landing-page</a></li>
    </ul>
  </div>

  <div class="section">
    <h2>⚡ Running Locally</h2>
    <p>Clone the repository and open <code>index.html</code> in any modern browser:</p>
    <pre><code>git clone https://github.com/faheem1309/Responsive-landing-page.git
cd Responsive-landing-page
open index.html</code></pre>
  </div>

  <div class="section">
    <h2>🌟 Takeaways</h2>
    <ul>
      <li>Learned to integrate <strong>GSAP animations</strong> with HTML/CSS</li>
      <li>Practiced <strong>responsive design</strong> using Flexbox and media queries</li>
      <li>Enhanced understanding of <strong>interactive UI behavior</strong> using Vanilla JS</li>
      <li>Built a <strong>portfolio-ready, motion-rich landing page</strong></li>
      <li>Implemented <strong>accessibility</strong> with keyboard focus support</li>
    </ul>
  </div>

  <div class="section">
    <h2>🔖 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong> — free for personal learning and portfolio purposes.</p>
  </div>

</body>
</html>
