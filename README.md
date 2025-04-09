# 🛠 백엔드 스터디 레포지토리

안녕하세요! 스터디장 이동하입니다.
이곳은 우리 백엔드 스터디에서 실습, 과제, 프로젝트 등을 함께 공유하고 협업하는 공간입니다.  
GitHub을 처음 쓰는 분도 따라하기 쉽게 하나하나 설명해드릴게요 🙌

---

## 📌 스터디 레포 사용 방법

### 1. 이 레포지토리를 **포크(Fork)** 해주세요
- 페이지 오른쪽 상단에 있는 `Fork` 버튼을 눌러서  
  이 레포지토리를 **내 GitHub 계정으로 복사**합니다.

### 2. 포크한 레포를 내 컴퓨터에 **클론(Clone)** 해주세요
```bash
git clone https://github.com/본인아이디/AIAX_STUDY.git
cd AIAX_STUDY
```

### 3. 원본(스터디장) 레포를 `upstream`으로 연결해주세요 (처음 한 번만)
```bash
git remote add upstream https://github.com/moveonha/AIAX_STUDY.git
```

---

## 📁 폴더 구조 예시

```
AIAX_STUDY/
├── sang_hoon/
│   ├── html/
│   │   └── home.html
│   └── server/
├── yoo_jung/
│   ├── html/
│   │   └── home.html
│   └── server/
└── README.md
```

> 개인 폴더 내 내용만 수정해주세요!

---

## 🧪 실습 제출 방법

### ✅ 브랜치 생성
```bash
git checkout -b 이름/week01
```

### ✅ 코드 작성 후 커밋
```bash
git add .
git commit -m "feat: week01 REST API 실습 완료"
```

### ✅ 본인 GitHub 레포지토리로 푸시
```bash
git push origin 이름/week01
```

---

## 🔁 Pull Request (PR) 보내기

1. 본인 GitHub 페이지에서 `Compare & pull request` 클릭
2. 아래처럼 설정
   - base repository: `moveonha/AIAX_STUDY`
   - base: `main`
   - compare: `이름/week01`
3. PR 제목 예시: `[dongha] week01 실습 제출`
4. PR 설명에는 한 줄 정도로 실습 내용 요약 or 느낀 점 적기

---

## 📝 작성 규칙

- 실습 폴더 이름은 간단하게 주제나 과제명으로!
  - 예: `rest-api-practice`, `springboot-crud`, `jwt-auth`
- README나 주석으로 설명 남겨두면 더 좋아요!

---

## 🔄 원본 레포에서 최신 코드 받아오기 (매주 시작 전)

```bash
git checkout main
git pull upstream main
git push origin main
```

---

처음이라 익숙하지 않아도 괜찮아요! 천천히 따라오시면 금방 익숙해집니다 😄  
모르는 부분은 언제든 편하게 물어보세요!

우리 같이 성장해봐요 💪🔥
