<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta property="og:title" content="Master The Game" />
  <meta property="og:description" content="Elite soccer training for the Tri-City Area. Book your session now!" />
  <meta property="og:image" content="https://i.imgur.com/pXA84GN.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta property="og:image:alt" content="Master The Game Soccer Training Logo" />
  <meta property="og:url" content="https://mtgsoccer.com" />
  <meta property="og:type" content="website" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Master the Game</title>
  <base target="_top" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1a1a1a;
      color: #fff;
      margin: 20px 8px;
    }
    .container {
      max-width: 1000px;
      margin: 20px auto;
      padding: 20px;
      background-color: #1a1a1a;
      border-radius: 8px;
      color: #fff;
      box-sizing: border-box;
      display: flex;
      gap: 30px;
      flex-wrap: nowrap;
    }
    .content-section,
    .coach-section-slider {
      flex: 1 1 33.33%;
      min-width: 280px;
    }
    h1.headline {
      font-size: 2.4em;
      font-weight: 700;
      color: #fff;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
      margin: 15px 0 8px;
      letter-spacing: 1px;
      text-align: center;
    }
    h1.headline span {
      color: #00bcd4;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.4);
    }
    h2 {
      color: #00bcd4;
      font-size: 24px;
      margin-bottom: 20px;
    }
    h2.subtitle {
      font-size: 1.4em;
      font-weight: normal;
      color: #fff;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
      margin: 10px 0;
      letter-spacing: 1px;
      text-align: center;
    }
    h2.subtitle span {
      color: #00bcd4;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.4);
    }
    .book-now-btn {
      display: inline-block;
      margin: 20px 0;
      background-color: #00bcd4;
      color: #1a1a1a;
      border: none;
      padding: 12px 24px;
      border-radius: 6px;
      text-decoration: none;
      font-size: 16px;
      font-weight: bold;
      transition: background-color 0.3s ease;
      text-align: center;
    }
    .book-now-btn:hover {
      background-color: #0097a7;
    }
    .coach-section-slider {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .coach-bio-section {
      background-color: #2a2a2a;
      border-radius: 8px;
      padding: 15px;
      position: relative;
    }
    .coach-bio-container {
      display: flex;
      align-items: center;
      gap: 12px;
      flex-wrap: nowrap;
    }
    .coach-bio-container img {
      width: 100px;
      height: 140px;
      object-fit: cover;
      border-radius: 8px;
      flex-shrink: 0;
    }
    .coach-info {
      flex: 1;
      overflow: hidden;
    }
    .coach-info p {
      font-size: 13px;
      line-height: 1.4;
      margin-top: 8px;
      word-wrap: break-word;
    }
    .coach-info h3 {
      font-size: 15px;
      color: #00bcd4;
      margin: 0;
    }
    .logo {
      display: block;
      margin: 0 auto;
      max-width: 120px;
      height: auto;
    }
    .follow-us {
      text-align: center;
      background: rgba(255, 255, 255, 0.05);
      padding: 15px;
      border-radius: 6px;
    }
    .follow-us h2 {
      font-size: 20px;
      margin-bottom: 12px;
      text-transform: uppercase;
      letter-spacing: 1px;
    }
    .social-icons a {
      font-size: 20px;
      color: #fff;
      margin: 8px;
      transition: transform 0.2s ease;
    }
    .social-icons a[aria-label="Facebook"] {
      color: #1877f2;
    }
    .social-icons a:hover {
      transform: scale(1.2);
    }
    .nav-arrow {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      background-color: rgba(0,188,212,0.8);
      border-radius: 50%;
      width: 25px;
      height: 25px;
      color: #1a1a1a;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    .nav-arrow:hover {
      background-color: #0097a7;
    }
    .nav-prev {
      left: 8px;
    }
    .nav-next {
      right: 8px;
    }
    .schedule-visual {
      background-color: #2a2a2a;
      border-radius: 12px;
      padding: 12px;
      text-align: center;
    }
    .schedule-visual h3 {
      font-size: 18px;
      color: #00bcd4;
      margin: 0 0 8px;
    }
    .calendar-container {
      background-color: #1a1a1a;
      border: 2px solid #00bcd4;
      border-radius: 8px;
      padding: 8px;
    }
    .calendar-header {
      background-color: #00bcd4;
      color: #1a1a1a;
      font-size: 13px;
      font-weight: bold;
      padding: 4px;
      border-radius: 4px 4px 0 0;
    }
    .calendar-body {
      padding: 8px;
      font-size: 18px;
      line-height: 1.4;
      color: #fff;
    }
    .calendar-body p {
      margin: 4px 0;
    }
    .price-list {
      background-color: #2a2a2a;
      border: 2px solid #00bcd4;
      border-radius: 8px;
      padding: 15px;
      margin-bottom: 15px;
    }
    .price-list h3 {
      color: #00bcd4;
      font-size: 20px;
      margin-bottom: 12px;
      text-align: center;
    }
    .price-list ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .price-list li {
      display: flex;
      align-items: center;
      padding: 8px 0;
      font-size: 14px;
      color: #fff;
      border-bottom: 1px solid #444;
    }
    .price-list li:last-child {
      border-bottom: none;
    }
    .price-list li i {
      color: #00bcd4;
      margin-right: 8px;
      font-size: 18px;
    }
    @media (max-width: 800px) {
      .container {
        flex-direction: column;
        align-items: center;
        gap: 15px;
      }
      .content-section,
      .coach-section-slider {
        flex: 1 1 100%;
        min-width: 100%;
      }
      .coach-bio-container {
        flex-direction: column;
        align-items: flex-start;
      }
      .coach-bio-container img {
        width: 100%;
        height: auto;
        max-width: 180px;
      }
      .coach-info {
        width: 100%;
      }
      .nav-prev {
        left: 4px;
      }
      .nav-next {
        right: 4px;
      }
      .follow-us {
        font-size: 13px;
        padding: 12px;
      }
      .price-list li {
        font-size: 13px;
      }
      .price-list li i {
        font-size: 16px;
      }
    }
  </style>
</head>
<body>
  <img class="logo" src="https://i.imgur.com/8tNuYmw.png" alt="Your Logo" />
  <h1 class="headline">Are You Ready to <span>Master The Game?</span></h1>
  <h2 class="subtitle">Providing Elite Soccer Training for the <span>Tri-City Area</span></h2>

  <div class="container">
    <div class="content-section">
      <h2>Join Our Training Program</h2>
      <p>Master The Game offers elite soccer training for outfield players and goalkeepers in the Tri-City Area. Book your session today to train with top coaches!</p>
      <a href="https://script.google.com/macros/s/<YOUR_PROJECT_ID>/exec" class="book-now-btn" target="_blank">Book Your Session Now</a>
      <div class="price-list">
        <h3>Session Prices</h3>
        <ul>
          <li><i class="fas fa-dollar-sign"></i>1-on-1 Session: $60</li>
          <li><i class="fas fa-dollar-sign"></i>Group Session: $50</li>
          <li><i class="fas fa-dollar-sign"></i>Goalkeeper: $30</li>
        </ul>
      </div>
    </div>

    <div class="coach-section-slider">
      <div class="coach-bio-section">
        <h2>Meet the Coaches</h2>
        <div class="coach-bio-container">
          <img id="coach-image" src="https://i.imgur.com/I9Su8DG.png" alt="Coach" />
          <div class="coach-info">
            <h3 id="coach-name">Coach Malik</h3>
            <p id="coach-bio">Coach Malik, from London, England, has 20+ years of high-level soccer experience. A former professional academy and semi-professional player in the UK, he played college and semi-professional soccer in the U.S. He’s now the Head Girls Varsity Coach at Heritage HS and coaches for Detroit City FC.</p>
          </div>
        </div>
        <div class="nav-arrow nav-prev" aria-label="Previous coach">
          <i class="fa fa-chevron-left"></i>
        </div>
        <div class="nav-arrow nav-next" aria-label="Next coach">
          <i class="fa fa-chevron-right"></i>
        </div>
      </div>
      <div class="schedule-visual">
        <h3>Current Schedule</h3>
        <div class="calendar-container">
          <div class="calendar-header">June 2025</div>
          <div class="calendar-body">
            <p>Tuesdays: 1-on-1 Sessions</p>
            <p>Thursdays: Group Sessions</p>
            <p>Thursdays & Fridays: Goalkeeper</p>
            <p>Location: Saginaw Soccer Complex</p>
          </div>
        </div>
      </div>
      <div class="follow-us">
        <h2>Follow Us</h2>
        <div class="social-icons">
          <a href="https://www.facebook.com/people/Master-the-Game-MTG/61560819523382/" target="_blank" aria-label="Facebook">
            <i class="fab fa-facebook"></i>
          </a>
        </div>
      </div>
    </div>
  </div>

  <script>
    const coaches = [
      {
        name: "Coach Malik",
        bio: "Coach Malik, from London, England, has 20+ years of high-level soccer experience. A former professional academy and semi-professional player in the UK, he played college and semi-professional soccer in the U.S. He’s now the Head Girls Varsity Coach at Heritage HS and coaches for Detroit City FC.",
        image: "https://i.imgur.com/I9Su8DG.png"
      },
      {
        name: "Coach Vitor",
        bio: "Coach Vitor is a goalkeeper coach from Brazil with a strong background in developing players. He previously coached at Freeland High School, focusing on goalkeepers, and served as Head Coach of the SVSU Men’s Club Soccer team for two years. Currently, he coaches club and travel soccer with Detroit City FC.",
        image: "https://i.imgur.com/GmWYBSS.jpeg"
      },
      {
        name: "Coach Ole",
        bio: "Coach Ole, from Leipzig, Germany, brings a strong international background in coaching and player development. He’s coached at Real Madrid Foundation camps, worked with FC Eilenburg’s first team, and now develops players in Michigan as a Detroit City FC coach.",
        image: "https://i.imgur.com/w1FkPek.png"
      }
    ];
    let currentCoachIndex = 0;

    function displayCoach(index) {
      const coach = coaches[index];
      document.getElementById('coach-name').textContent = coach.name;
      document.getElementById('coach-bio').textContent = coach.bio;
      document.getElementById('coach-image').src = coach.image;
    }

    function prevCoach() {
      currentCoachIndex = (currentCoachIndex - 1 + coaches.length) % coaches.length;
      displayCoach(currentCoachIndex);
    }

    function nextCoach() {
      currentCoachIndex = (currentCoachIndex + 1) % coaches.length;
      displayCoach(currentCoachIndex);
    }

    document.querySelector('.nav-prev').addEventListener('click', prevCoach);
    document.querySelector('.nav-next').addEventListener('click', nextCoach);
    displayCoach(currentCoachIndex);
  </script>
</body>
</html>
