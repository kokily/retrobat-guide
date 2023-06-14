# Xbox

![](title.svg)

게임 콘솔 - 수명: 2001 - 2006


## 정 보

|||
|---|---|
| 에뮬레이터 | xemu |
|  | cxbx |
| 게임 경로 | ![](../../icon.png)roms \ ![](../../icon.png)xbox |
| 파일 확장자 | .xbe .iso |
|||

> CXBX는 .iso 이미지를 드라이브에 마운트할 수 있으려면 "dokan"이 필요합니다.  
[여기](https://github.com/dokan-dev/dokany/releases)에서 dokan v2를 다운로드할 수 있습니다.  


## 특 징

| Retroachievements | 넷플레이 |
|---|---|
| 아니오 | 아니오 |
|||


## 바이오스

| 바이오스 파일 | 폴더 | md5 |
|---|---|---|
| mcpx_1.0.bin | `\bios` | d49c52a4102f6df7bcf8d0617ac475ed |
| Complex_4627.bin | `\bios` | 39cee882148a87f93cb440b99dde3ceb |
| xbox_hdd.qcow2 | `\saves\xbox` |  |
|||


## 컨트롤

| RetroBat 키 | Xbox 키 |
|---|---|
| START | START |
| SELECT / BACK | Back |
| D-PAD | D-PAD |
| 왼쪽 아날로그 스틱 | 왼쪽 아날로그 스틱 |
| 오른쪽 아날로그 스틱 | 오른쪽 아날로그 스틱 |
| ![](../../south.webp) | A |
| ![](../../east.webp) | B |
| ![](../../north.webp) | Y |
| ![](../../west.webp) | X |
| L1 | L1 (White) |
| R1 | R1 (Black) |
| L2 | LT |
| R2 | RT |
| L3 | 왼쪽 스틱 버튼 |
| R3 | 오른쪽 스틱 버튼 |
|||


## 특정 시스템 정보

### 게임 언어 이슈

게임이 모두 독일어나 프랑스어로 되어 있다면 사용 중인 eeprom 파일이 올바른 언어로 설정되지 않았기 때문일 수 있습니다. 에뮬레이터는 eeprom 파일에 설정된 언어를 사용합니다.

원래 Xbox에서 언어를 올바르게 설정하고 BIOS 파일을 다시 추출하는 것이 좋습니다.

또는 Retrobat 폴더의 /saves/xbox/ 디렉터리에 있는 eeprom 파일을 [여기(Ernegien의 원래 Xbox EEPROM 편집기)](https://github.com/Ernegien/XboxEepromEditor)에서 사용할 수 있는 도구를 사용하여 편집하여 변경할 수 있습니다. Xbox eeprom 설정.