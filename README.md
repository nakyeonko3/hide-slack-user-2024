# slack-client-utils

브라우저 slack를 사용하면서 유용한 유틸모음.

## 목차

- [slack-client-utils](#slack-client-utils)
  - [목차](#목차)
  - [1. hide-slack-user-2024](#1-hide-slack-user-2024)
    - [1-1. 사용 방법](#1-1-사용-방법)
  - [2. vimium-c](#2-vimium-c)

## 1. hide-slack-user-2024

- slack 유저 차단 기능 확장 프로그램
  특정 slack 유저의 멘션, DM, 게시글을 보고 싶지 않을 때 유용함.
- 내가 만들었음.
- 주의) chrome slack client, firefox slack clinet 에서만 동작함
- 주의) 수동으로 해당 유저를 `음소거` 처리 한다음 사용해야함.

### 1-1. 사용 방법

- [**hide-slack-user-2024 스크립트 링크**](https://greasyfork.org/en/scripts/501978-hide-slack-user-2024)
- 수동으로 차단하고 싶은 유저를 `음소거` 처리 해야함.

1. [tempermonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=ko) 확장 프로그램을 설치
2. 설치 이후 익스텐션 사용 허가 설정하기
3. hide-slack-user-2024 스크립트를 설치
4. 설치 후 hide-slack-user-2024 스크립트에 hiddenUsers에 차단을 원하는 유저명을 입력하고 slack 웹페이지를 새로고침하면 작동함.


## 2. vimium-c

- slack 에서 마우스 키보드 키만으로도 채널 이동, slack 메시지 작성, 등을 가능하게 해줌. </br>

[GitHub - gdh1995/vimium-c: A keyboard shortcut browser extension for keyboard-based navigation and tab operations with an advanced omnibar](https://github.com/gdh1995/vimium-c)
