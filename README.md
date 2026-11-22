# 2026 영업 CRM · 모바일 웹앱

법인 종합검진 영업 CRM. iPhone Safari에서 홈 화면에 추가해 앱처럼 사용합니다.

## 구조
- `index.html` — 화면 전체 (UI 코드만, 데이터 없음)
- `manifest.json`, `icon-*.png` — 홈 화면 추가용 PWA 설정

## 데이터
영업 데이터는 이 저장소에 없습니다. 앱을 열고 **설정 → 토큰 연결**에서
비공개 저장소의 Fine-grained PAT(Contents: Read/Write)를 한 번 입력하면
비공개 데이터 파일을 직접 읽고 씁니다. 토큰은 그 기기 브라우저에만 저장됩니다.

## 사용
1. `https://mssuejang-bot.github.io/minsu-crm-app/` 접속
2. Safari 공유 → **홈 화면에 추가**
3. 설정 → 토큰 연결
