# PITCH Master - Claude 작업 규칙

이 저장소는 현아 개인 계정 클로드(iamhyona)와 핏치 회사 계정 클로드(pitch@pitchpitch.kr) 두 곳에서 함께 관리합니다.

## 작업 전
1. 인수인계 문서를 읽는다: 구글 드라이브 PITCH_DB/[PITCH]PITCH_Master_인수인계
   https://docs.google.com/document/d/1h1rY4M0jOle21OcLVMeIXL_AHkW6Yfdyod7X2s2V640/edit
2. 문서 맨 아래 '변경 기록'에서 다른 계정이 최근에 바꾼 내용을 확인한다.
3. 최신본 기준으로 작업한다 (새로 clone 또는 git pull). Apps Script도 편집기에서 다시 읽고 고친다.

## 작업 후
1. 작게 커밋하고 바로 푸시한다. 커밋 메시지에 어느 계정인지 적는다 (예: [pitch@] 메일 팝업 수정).
2. 인수인계 문서의 '변경 기록'에 날짜 · 계정 · 내용을 한 줄 추가한다.
3. Apps Script 웹앱 '새 버전 배포'는 브라우저가 iamhyona@gmail.com으로 로그인된 상태에서만 한다.

## 기본 원칙
- 서버 주소는 index.html의 AS_URL 한 곳에서만 정한다.
- 수정은 핏치·관리 두 모드 모두 반영되는지 확인한다.
- 현아가 쓴 시트 내용과 사용자가 복사한 '청구서 수정'·'청구서 사본' 탭은 건드리지 않는다.
