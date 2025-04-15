<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>하늘 (5K7E) 포트폴리오</title>
  <!-- 구글 폰트 불러오기 -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* 전체 레이아웃 및 배경 스타일 */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #74ABE2, #5563DE);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    
    /* 컨텐츠를 감싸는 박스 */
    .container {
      max-width: 800px;
      padding: 2rem;
      text-align: center;
      background-color: rgba(0, 0, 0, 0.3);
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }

    /* 프로필 이미지 스타일 */
    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 1.5rem;
      border: 3px solid #fff;
    }

    /* 제목 스타일 */
    h1 {
      font-size: 2.8rem;
      margin-bottom: 0.5rem;
    }
    
    h3 {
      font-size: 1.5rem;
      margin-bottom: 1.5rem;
    }
    
    /* 기술 아이콘 & 도구 섹션 */
    .section {
      margin-top: 2rem;
    }
    
    .section p {
      font-weight: bold;
      margin-bottom: 0.5rem;
    }
    
    .icons a {
      margin: 0 10px;
      transition: transform 0.3s;
      display: inline-block;
    }
    
    .icons a img {
      vertical-align: middle;
    }

    .icons a:hover {
      transform: scale(1.2);
    }
  </style>
</head>
<body>
  <div class="container">
    <img class="profile-img" src="https://cdn.domi.kr/4LLjhDOi64Xb2jKqP4xwTFDLHsHBOx.png" alt="프로필 이미지">
    
    <h1>안녕하세요 👋, 저는 하늘 (5K7E) 입니다.</h1>
    <h3>저는 대한민국에서 프론트 엔드 개발자로 활동하고 있습니다.</h3>
    
    <!-- 사용 언어 및 툴: 메인 개발 언어 -->
    <div class="section">
      <p>메인 개발 언어</p>
      <div class="icons">
        <a href="https://www.python.org" target="_blank" rel="noreferrer">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40">
        </a>
        <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40">
        </a>
        <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40">
        </a>
        <a href="https://nodejs.org" target="_blank" rel="noreferrer">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40">
        </a>
      </div>
    </div>
    
    <!-- 디자인 협업 및 데이터베이스 도구 -->
    <div class="section">
      <p>디자인 협업 툴</p>
      <div class="icons">
        <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
          <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="40" height="40">
        </a>
      </div>
      <p>데이터베이스 관리</p>
      <div class="icons">
        <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="40" height="40">
        </a>
      </div>
    </div>
  </div>
</body>
</html>
