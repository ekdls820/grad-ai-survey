# 대학원생 AI 활용 현황 및 연구지원 요구 설문조사

GitHub Pages로 공개되는 설문 사이트입니다. 응답은 Google Apps Script 웹 앱을 거쳐 Google 시트에 한 줄씩 저장됩니다.

- `index.html`: 설문 화면과 분기 로직 (문항은 파일 안의 `SECTIONS` 배열에서 수정)
- 응답 저장: `index.html`의 `ENDPOINT` 주소(Apps Script 웹 앱)로 전송
- 응답 시트 열 이름은 각 문항의 `col` 값과 같아야 합니다. 문항을 추가하면 시트 1행에도 같은 이름의 열을 추가하세요.
