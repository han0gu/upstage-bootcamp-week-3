# upstage-bootcamp-week-3

<header>이게 내가 만든 헤더다 !</header>

## Git 커밋 히스토리

```mermaid
gitgraph
    commit id: "Initial commit"
    commit id: "강산이의 첫번째 커밋"
    branch hong
    checkout hong
    commit id: "홍인표의 첫 커밋"
    commit id: "feat. 충돌 위한 커밋"
    checkout main
    commit id: "이번엔 한승완이 수정함"
    commit id: "추가: 김종현이 파일을 수정함"
    commit id: "feat: greeter add"
    commit id: "홍인표님 많관부라서요 :)"
    commit id: "Because I also want to contribute"
    commit id: "fix conflict"
    commit id: "한승완이 두번째 수정을 시도함"
    commit id: "fix conflict"
    branch feature/readme
    checkout feature/readme
    commit id: "pr 테스트- 리드미 생일 추가"
    commit id: "feat: README에 생일 정보를 추가합니다."
    commit id: "텍스트 파일에 새 줄을 추가합니다"
    checkout hong
    commit id: "fix. 리드미 수정"
    commit id: "Revert 'fix. 리드미 수정'"
    commit id: "fix. 리드미 수정"
    commit id: "advanced mission_day03_answer_한승완"
    checkout main
    merge hong
    merge feature/readme
    branch docs
    checkout docs
    commit id: "docs 작업"
    checkout main
    branch feature/header
    checkout feature/header
    commit id: "feat: implement header"
    checkout main
    merge feature/header
    branch feature/style
    checkout feature/style
    commit id: "현재 브랜치"
```

---

# 홍인표입니다.
- 많관부~ 

# Hi this is Kolja.
- Nice to meet you~~

이번엔 한승완이 수정함

이번엔 김종현이 수정함 :)

한승완이 또 수정 시도해볼게 !!!!!!!!
이번엔 한승완이 수정함,

충돌을 위한 메시지입니다. - 홍인표 

# 생일을 입력하세요.
- 인표: sep 20
- 종현: mar 7
- Kolja: may 28

<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>Footer Example</title>
  <style>
    footer {
      background-color: #222;
      color: #ccc;
      padding: 40px 20px;
      font-size: 14px;
    }

    .footer-container {
      max-width: 1200px;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .footer-section {
      margin-bottom: 20px;
    }

    .footer-section h4 {
      color: #fff;
      margin-bottom: 10px;
    }

    .footer-section ul {
      list-style: none;
      padding: 0;
    }

    .footer-section ul li {
      margin-bottom: 6px;
    }

    .footer-section a {
      color: #ccc;
      text-decoration: none;
    }

    .footer-section a:hover {
      color: #fff;
    }

    .footer-bottom {
      text-align: center;
      border-top: 1px solid #444;
      margin-top: 20px;
      padding-top: 20px;
      font-size: 13px;
    }
  </style>
</head>
<body>

  <!-- Footer -->
  <footer>
    <div class="footer-container">
      
      <div class="footer-section">
        <h4>회사 정보</h4>
        <p>주식회사 샘플</p>
        <p>서울특별시 강남구 테헤란로 123</p>
        <p>사업자등록번호: 123-45-67890</p>
      </div>

      <div class="footer-section">
        <h4>고객지원</h4>
        <ul>
          <li><a href="#">공지사항</a></li>
          <li><a href="#">자주 묻는 질문</a></li>
          <li><a href="#">문의하기</a></li>
        </ul>
      </div>

      <div class="footer-section">
        <h4>약관</h4>
        <ul>
          <li><a href="#">이용약관</a></li>
          <li><a href="#">개인정보처리방침</a></li>
        </ul>
      </div>

    </div>

    <div class="footer-bottom">
      © 2026 Sample Company. All rights reserved.
    </div>
  </footer>

</body>
</html>
