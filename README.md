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

# 안녕하세요! 
- 컨텐트-1 홍인표입니다. 

이번엔 한승완이 수정함

이번엔 김종현이 수정함 :)

한승완이 또 수정 시도해볼게 !!!!!!!!
이번엔 한승완이 수정함,

충돌을 위한 메시지입니다. - 홍인표 

# 생일을 입력하세요.
- 인표: dec 20
- 종현: mar 7
- Kolja: may 28

