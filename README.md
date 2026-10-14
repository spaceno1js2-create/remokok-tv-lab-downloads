# 리모콕 TV LAB 테스트 APK

Android TV Remote v2 기반의 독립 실험용 앱입니다. 기존 Google Play REMOKOK과 다른 패키지입니다.

- 앱 이름: 리모콕 TV LAB
- 버전: 0.2.0-tester (versionCode 2)
- 패키지명: com.remokok.tvlab
- Android 8.0(API 26) 이상 설치 대상. 실제 검증: Samsung SM-F971N / Android 17(API 37).
- Windows 모의 서버에서 검색·TLS 페어링·리모컨·삼성 키보드 한글 입력을 검증했습니다.
- KT·SK·LG 셋톱박스 및 실제 TV 검색창 호환성은 아직 미검증입니다.

## 다운로드와 설치

Releases의 `remokok-tv-lab-0.2.0-tester-debug.apk`를 다운로드하세요.
APK를 열고 요청되는 경우 다운로드에 사용한 앱의 ‘이 출처 허용’을 켠 뒤 설치하세요.
Android 17에서는 앱의 로컬 네트워크 권한을 허용하고 검색을 다시 누르세요.
스마트폰과 셋톱박스는 서로 접근 가능한 같은 LAN에 연결해야 합니다. 게스트 망/IPTV VLAN에서는 검색·연결이 제한될 수 있습니다.
기존 REMOKOK을 삭제하거나 데이터를 지울 필요가 없습니다.

## 배포 범위

이 저장소에는 다운로드 안내만 둡니다. 앱 소스코드, 인증서 개인키, 서명키, 비밀번호/환경설정 파일은 게시하지 않습니다.
릴리스 첨부 파일은 테스트 APK 1개입니다. Debug 서명이며 Google Play RC9과 별개입니다.

SHA-256: `a8245364fc44210027cb31cfcef174f8514632be629cfbb409ecda24b560d61a`
