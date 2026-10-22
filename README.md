# DUO Launcher · AI Box updates

Carlinkit 및 호환 AI Box를 위한 테스트 APK와 서명된 업데이트 정보입니다. 앱 소스 코드는 포함하지 않습니다.

최신 버전: **1.6.3** · [AI Box APK 다운로드](https://github.com/byezzun/duo-launcher-updates/releases/download/v1.6.3/duo-launcher-aibox-1.6.3.apk). 1.6.1~1.6.2의 키보드 문제(앱 뒤로 숨거나 크기가 바뀜) 수정, 핸들 리모컨 다음 곡·이전 곡 전달, 앱 영역에 기본 런처(Quickstep)가 끼어들지 않도록 보완했습니다. 1.5.x에서 업데이트할 때 설치 권한을 허용한 뒤 DUO로 돌아와 ‘업데이트 확인’을 다시 눌러 주세요. 엠비언트 6225 Quickstep 문제는 실기기 해결 확인 전입니다.

## 화면 / Screenshots

| 두 앱 나란히 / Two apps side by side | 독 즐겨찾기 편집 / Editing dock favorites |
| --- | --- |
| ![지도와 음악 앱을 나란히 둔 DUO 홈 / DUO home with maps and music side by side](screenshots/home-pair.png) | ![즐겨찾기를 길게 눌러 순서 변경·삭제하는 편집 모드 / Edit mode after holding a dock favorite](screenshots/dock-edit.png) |

![시계·날씨와 앱 하나를 함께 보여 주는 화면 / Clock and weather beside one app](screenshots/clock-weather.png)

DUO의 실제 화면 코드를 PC에서 그린 이미지입니다. 차량에서는 각 영역에 실제 앱 화면이 나오며, 여기서는 예시 앱 아이콘으로 표시했습니다. 독의 ⓘ 경고 표시는 PC 환경에 시스템 권한이 없어서 보입니다.
Rendered on a PC from DUO's real UI code. On the AI Box each pane shows the running app; sample app icons stand in here. The warning badge in the dock appears only because the PC renderer has no system permissions.

## 사용 안내 / Tutorial

DUO를 처음 열면 나오는 안내 9단계입니다. 빨간 테두리가 각 단계에서 설명하는 부분입니다. 설정에서 언제든 다시 볼 수 있습니다.
The 9-step guide shown the first time DUO opens. The red outline marks what each step explains. You can replay it from Settings.

|   |   |   |
| --- | --- | --- |
| **1. Choose two apps**<br>![Choose two apps](screenshots/tutorial/en-1.png) | **2. Choose where an app opens**<br>![Choose where an app opens](screenshots/tutorial/en-2.png) | **3. Center handle**<br>![Center handle](screenshots/tutorial/en-3.png) |
| **4. App favorites**<br>![App favorites](screenshots/tutorial/en-4.png) | **5. Clear current screen**<br>![Clear current screen](screenshots/tutorial/en-5.png) | **6. Clock and settings**<br>![Clock and settings](screenshots/tutorial/en-6.png) |
| **7. Hide and restore the dock**<br>![Hide and restore the dock](screenshots/tutorial/en-7.png) | **8. Gestures and execution status**<br>![Gestures and execution status](screenshots/tutorial/en-8.png) | **9. Information and single-app pages**<br>![Information and single-app pages](screenshots/tutorial/en-9.png) |

<details>
<summary>한국어 화면 보기 / Korean screens</summary>

|   |   |   |
| --- | --- | --- |
| **1. 두 앱 선택**<br>![두 앱 선택](screenshots/tutorial/ko-1.png) | **2. 앱서랍에서 실행 위치 선택**<br>![앱서랍에서 실행 위치 선택](screenshots/tutorial/ko-2.png) | **3. 가운데 핸들**<br>![가운데 핸들](screenshots/tutorial/ko-3.png) |
| **4. 앱 즐겨찾기**<br>![앱 즐겨찾기](screenshots/tutorial/ko-4.png) | **5. 현재 화면 비우기**<br>![현재 화면 비우기](screenshots/tutorial/ko-5.png) | **6. 시계와 설정**<br>![시계와 설정](screenshots/tutorial/ko-6.png) |
| **7. 독 숨기기와 복원**<br>![독 숨기기와 복원](screenshots/tutorial/ko-7.png) | **8. 멀티터치와 실행 상태**<br>![멀티터치와 실행 상태](screenshots/tutorial/ko-8.png) | **9. 시계 화면과 단독앱 화면**<br>![시계 화면과 단독앱 화면](screenshots/tutorial/ko-9.png) |

</details>

위 화면과 같은 방식으로 PC에서 그린 이미지입니다. / Rendered on a PC like the screenshots above.

## 설치

Releases의 AI Box APK를 내려받아 기존 AI Box 버전 위에 업데이트합니다. 기존 앱을 먼저 삭제하지 마세요. 처음 설치한 경우 Android 설정에서 기본 홈으로 선택합니다.

1.4.2에는 OTA가 없으므로 최신 APK를 직접 설치해야 합니다. 구버전 OTA에서 오류가 나도 최신 APK를 직접 받아 기존 앱 위에 업데이트할 수 있습니다. 1.5.0부터 설정 → 업데이트 확인을 통해 이후 버전을 확인할 수 있습니다. 다운로드 및 Android 설치 확인은 사용자가 직접 선택합니다.

## 호환성

필요한 시스템 권한과 기기 펌웨어가 맞아야 내부 앱 실행이 가능합니다. 모든 Carlinkit·AI Box 모델을 검증한 것은 아니며 일반 휴대폰용 버전이 아닙니다. 태블릿 화면 유지와 실제 업데이트 설치·설정 보존은 기기별 확인이 필요합니다. 앱 서명이나 업데이트 기능이 없는 시스템 권한을 부여하지는 않습니다.

## English

Test builds for compatible Carlinkit and Android AI Boxes. Download the AI Box APK from Releases and update your existing installation. Do not uninstall first. Version 1.4.2 has no OTA client. Install the latest APK manually; use the same method if OTA fails on an older build. Later versions can be checked in Settings → Check for updates. Downloads and Android installation require your confirmation.

Required system privileges and firmware compatibility still apply. This is not a general phone build. Support for every AI Box, tablet layouts, DRM playback, and real-device update installation is not guaranteed. This repository contains distribution files and update metadata only.
