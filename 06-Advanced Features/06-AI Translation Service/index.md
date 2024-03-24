# AI 번역 서비스

## 번역 서비스 설정

이 기능을 사용하면 읽을 수 없는 언어로 작성된 게임 화면을 모국어로 번역할 수 있습니다(예: 일본어를 영어로).

구성은 메인 메뉴의 게임 설정 및 AI 게임 번역에서 수행할 수 있습니다.

![](./01.avif)

게임 세팅

![](./02.avif)

AI 게임 번역 서비스

![](./03.avif)

AI 게임 번역 옵션

| 설정항목 | 세부내용 |
|:---:|:---:|
| Enable AI Translation Service | 번역 기능 On/Off |
| Target Language | 번역할 대상 언어 |
| AI Translation service URL | 번역 서비스 URL |
| Pause on translated screen | 번역 오버레이가 켜져 있는 동안 게임 계속 진행 / 일시 중지 |

## 번역 서비스 URL

ztranslate.net의 서비스를 사용하여 게임을 번역할 수 있습니다.
웹사이트에 등록해야 합니다.

![](./04.avif)

가입이 완료되면 설정으로 이동하여 API 키를 검색하세요.

![](./05.avif)

이제 Retrobat AI GAME TRANSLATION 설정에 URL + API 키를 입력하고 확인하세요.

다음 형식을 사용하세요.

`http://ztranslate.net/service?api_key=XXXYYYZZZ`

(XXXYYYZZZ를 자신의 API 키로 바꾸세요)

![](./06.avif)

## 게임 중 번역 호출

이제 `HOTKEY` + `R1` 조합을 사용하여 게임 내에서 AI 번역 서비스를 호출할 수 있습니다.