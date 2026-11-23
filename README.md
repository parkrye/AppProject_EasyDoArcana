# EasyDoArcana

광고 · 네트워크 없는 안드로이드 타로 앱. 셔플부터 뒤집기까지 실물 카드처럼 직접 골라 보는 오늘의 카드 · 쓰리 카드 · 테마(연애 · 금전 · 직업 · 건강) · 프리 리딩. 78장 카드별 상세 해석과 점 보기 안내 포함. 기본 덱은 라이더 웨이트 스미스 1909년판 78장, 내 사진으로 카드 그림 · 뒷면을 바꾼 덱도 사용. 데이터는 기기 밖으로 나가지 않음. EasyDo 시리즈.

버그 · 제안은 [Issues](../../issues)에.

## 다운로드

최신 버전 0.1.1 — [Releases](https://github.com/parkrye/AppProject_EasyDoArcana/releases)에서 `EasyDoArcana-<버전>.apk`를 받아 설치. Android 8.0 이상.

- 처음 설치 시 "출처를 알 수 없는 앱" 설치 허용 필요. Play 프로텍트가 검사 화면을 띄울 수 있음
- 업데이트는 새 APK를 같은 방식으로 덮어 설치. 덱 · 설정 유지
- 앱 안 `설정 → 앱 정보 → 새 버전 받기`로 Releases 페이지를 열 수 있음 (자동 업데이트 알림 없음)
- 서명 인증서 SHA-256: `6c3e246a04591a129636bf1ce4fd971facb87a9a8d501f866e325b0a695105aa`
  (`apksigner verify --print-certs EasyDoArcana-<버전>.apk`로 확인). 각 Release 본문에 APK SHA-256도 기재

## 기능

| 기능 | 내용 |
|---|---|
| 덱 범위 | 메이저 아르카나 22장 / 메이저 + 마이너 78장 |
| 오늘의 카드 | 하루 한 장, 같은 날은 같은 카드 |
| 쓰리 카드 | 과거 · 현재 · 미래 3장 |
| 프리 리딩 | 장수 제한 없이 펼친 덱에서 뽑기, 뒤집기 · 되돌리기 · 다시 섞기 |
| 테마 | 연애 · 금전 · 직업 · 건강, 테마별 스프레드 |
| 카드 정보 | 키워드 · 정/역 의미, 카드를 누르면 그림 속 상징 |
| 카드 탭 | 78장 상세 — 테마별 정/역 의미 · 상황별 해석(예 · 아니오, 조언 · 장애물 · 결과 자리, 사람) · 상징, 좌우로 넘기기 |
| 점 보기 전에 | 질문 정하기 · 마음가짐 · 카드 읽는 법 안내 |
| 커스텀 덱 | 갤러리 이미지로 78장 카드 그림 · 뒷면 교체 |
| 연출 | 자동 셔플 · 컷(탭하면 건너뛰기) · 펼치기(양 끝이 이어져 계속 넘김) · 직접 고르기 · 배치 · 뒤집기, 뒤로가기 시 카드 모으기 |

정방향 · 역방향은 항상 섞여 나옴. 점 기록은 남기지 않음.

## 개인정보

인터넷 권한 없음 · 광고 없음 · 수집 · 전송 없음.

- 계정 · 광고 · 사용 통계 · 오류 보고 없음
- 덱 · 설정은 기기 안에만 저장. 앱 삭제 시 함께 삭제 (Android 클라우드 백업 제외)
- 사진은 고른 것만 앱 안으로 복사 (사진 접근 권한 없음)
- 앱 안 백업 파일은 사용자가 고른 위치에만 저장. 기기를 바꿀 때는 백업 파일을 옮겨 복원

## EasyDo 시리즈

| 앱 | 용도 | 플랫폼 |
|---|---|---|
| [EasyDoDraw](https://github.com/parkrye/MultiProject_EasyDoDraw) | 그림 · 애니메이션 | Android · Windows |
| [EasyDoWrite](https://github.com/parkrye/AppProject_EasyDoWrite) | 소설 · 글쓰기 | Android |
| [EasyDoRead](https://github.com/parkrye/AppProject_EasyDoRead) | 책 · 문서 읽기 | Android |
| [EasyDoShelve](https://github.com/parkrye/AppProject_EasyDoShelve) | 웹 소설 서재 | Android |
| [EasyDoPhoto](https://github.com/parkrye/AppProject_EasyDoPhoto) | 카메라 · 사진 편집 | Android |
| [EasyDoDiet](https://github.com/parkrye/AppProject_EasyDoDiet) | 식단 · 운동 기록 | Android |
| [EasyDoZip](https://github.com/parkrye/AppProject_EasyDoZip) | 파일 · 압축 관리 | Android |
| [EasyDoGame](https://github.com/parkrye/AppProject_EasyDoGame) | 미니 게임 모음 | Android |
| [EasyDoMix](https://github.com/parkrye/AppProject_EasyDoMix) | 영상 · 오디오 편집 | Android |
| [EasyDoRecord](https://github.com/parkrye/AppProject_EasyDoRecord) | 녹음 | Android |
| [EasyDoStudio](https://github.com/parkrye/DesktopProject_EasyDoStudio) | 화면 녹화 · 영상 편집 | Windows |
| [EasyDoMusic](https://github.com/parkrye/MultiProject_EasyDoMusic) | MIDI 연주 · 작곡 | Android · Windows |
| [EasyDoArcana](https://github.com/parkrye/AppProject_EasyDoArcana) | 타로 점 | Android |


## 라이선스

MIT License · © parkrye. 카드 그림은 라이더 웨이트 스미스 타로 1909년판(퍼블릭 도메인). 포함된 서드파티 라이브러리 고지는 앱 안 `설정 → 앱 정보 → 오픈소스 라이선스`에서 확인.
