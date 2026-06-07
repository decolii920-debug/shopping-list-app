# 🛒 쇼핑 리스트 (Shopping List)

바닐라 JavaScript로 만든 가볍고 심플한 쇼핑 리스트 웹앱입니다.
브라우저의 `localStorage`에 데이터를 저장하므로 별도의 서버 없이 동작하며,
새로고침해도 목록이 유지됩니다.

## ✨ 기능

- ➕ 아이템 추가 (최대 100자)
- ✅ 체크박스로 완료 처리 (취소선 표시)
- ✕ 개별 아이템 삭제
- 💾 `localStorage` 자동 저장 / 복원
- 📱 모바일 친화적인 반응형 UI

## 🚀 실행 방법

별도의 빌드나 설치가 필요 없습니다. `index.html`을 브라우저로 열기만 하면 됩니다.

```bash
# 1) 저장소 클론
git clone https://github.com/decolii920-debug/shopping-list-app.git
cd shopping-list-app

# 2) 브라우저로 index.html 열기
#   - Windows:  start index.html
#   - macOS:    open index.html
#   - Linux:    xdg-open index.html
```

또는 GitHub Pages로 배포하여 바로 웹에서 사용할 수 있습니다
(Settings → Pages → Branch: `main` / Folder: `/ (root)` 로 설정).

## 🛠 기술 스택

- HTML5 / CSS3 (CSS 변수 활용)
- Vanilla JavaScript (ES6+)
- Web Storage API (`localStorage`)

## 📂 파일 구조

```
shopping-list-app/
├── index.html   # 앱 본체 (HTML + CSS + JS 단일 파일)
└── README.md
```

## 📄 라이선스

MIT
