<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>유해나 — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;700&family=Noto+Sans+KR:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="assets/style.css">
  <style>
    :root{
      --yellow:#fbe170;
      --accent:#f6c84b;
      --text:#222;
      --muted:#555;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:'Noto Sans KR','Lato',sans-serif;background:#fff;color:var(--text);line-height:1.7;}

    header{width:100%;padding:30px 80px;background:var(--yellow);display:flex;justify-content:space-between;align-items:center;position:sticky;top:0;z-index:5;}
    header h1{font-size:20px;font-weight:700;}
    nav a{margin-left:28px;text-decoration:none;color:var(--text);font-weight:600;transition:.2s}
    nav a:hover{color:#000}

    .hero{display:flex;min-height:100vh;align-items:center;justify-content:center;background:var(--yellow);padding:60px 80px;gap:80px;flex-wrap:wrap;}
    .hero-img{flex:0 0 280px;height:280px;border-radius:50%;overflow:hidden;box-shadow:0 8px 30px rgba(0,0,0,0.1)}
    .hero-img img{width:100%;height:100%;object-fit:cover}
    .hero-content{max-width:500px}
    .hero-content h2{font-size:24px;font-weight:700;margin-bottom:12px}
    .hero-content p{font-size:15px;margin-bottom:18px;color:var(--muted)}
    .hero-content .highlight{font-weight:700;color:#000}

    section{padding:80px 80px;max-width:1000px;margin:auto}
    h3.section-title{font-size:18px;font-weight:700;margin-bottom:20px;color:var(--accent)}
    ul.timeline{list-style:none;padding:0;margin:0}
    ul.timeline li{margin-bottom:12px;color:var(--muted)}
    .skillset{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px;margin-top:30px}
    .skill{display:flex;align-items:center;gap:14px}
    .skill .badge{width:44px;height:44px;border-radius:10px;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700}
    .dots{display:flex;gap:6px;margin-left:auto}
    .dot{width:10px;height:10px;border-radius:50%;background:#ccc}
    .dot.on{background:#111}

    footer{padding:60px;text-align:center;font-size:13px;color:var(--muted)}

    @media(max-width:768px){
      header{flex-direction:column;gap:10px}
      .hero{flex-direction:column;gap:40px;padding:60px 30px;text-align:center}
    }
  </style>
</head>
<body>
  <header>
    <h1>Haena Ryu Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#experience">Experience</a>
      <a href="#skills">Skills</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-img"><img src="assets/profile.jpg" alt="유해나 프로필"></div>
    <div class="hero-content">
      <h2>새로운 빛을 선물하는 디자이너 유해나입니다.</h2>
      <p>제 이름인 ‘해나’는 <span class="highlight">‘해가 난다’</span>는 뜻입니다. 매일 뜨는 해는 익숙하지만 꼭 필요한 존재입니다. 규칙적으로 뜨는 해처럼 꾸준히 사람들에게 밝은 빛으로 도움을 줄 수 있는 디자이너가 되고 싶습니다.</p>
      <p><strong>희망 진로 분야:</strong> UX/UI · 웹 퍼블리싱 · 브랜딩</p>
    </div>
  </section>

  <section id="about">
    <h3 class="section-title">ABOUT</h3>
    <ul class="timeline">
      <li><strong>이름:</strong> 유해나 / Haena Ryu</li>
      <li><strong>생년월일:</strong> 2000.04.10</li>
      <li><strong>Email:</strong> <a href="mailto:youremail@example.com">youremail@example.com</a></li>
      <li><strong>GitHub:</strong> <a href="https://github.com/ssunmee">github.com/ssunmee</a></li>
    </ul>
  </section>

  <section id="education">
    <h3 class="section-title">EDUCATION</h3>
    <ul class="timeline">
      <li><strong>2019</strong> 계원예술고등학교 졸업</li>
      <li><strong>2021</strong> 성신여자대학교 디자인과 입학</li>
      <li><strong>2025</strong> 성신여자대학교 디자인과 졸업</li>
      <li><strong>2025</strong> 연세대학교 커뮤니케이션 대학원 입학</li>
    </ul>
  </section>

  <section id="experience">
    <h3 class="section-title">EXPERIENCE</h3>
    <ul class="timeline">
      <li><strong>2022</strong> 대한민국 패키징 대전 입선</li>
      <li><strong>2023</strong> 미리디 인턴 경험</li>
      <li><strong>2023</strong> 로얄제과 제주도의연인 콘테스트 우승
