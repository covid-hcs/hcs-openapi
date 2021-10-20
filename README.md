# 🚧 hcs-openapi
문서 url: https://covid-hcs.github.io/hcs-openapi

교육청 건강상태 자가진단 내부 api의 openapi 스펙입니다.
현재 만들고 있는 상태이며, 아직 유용한 자료는 얼마 없을거에요.

문서를 웹사이트에서 열면 브라우저가 CORS를 막기 때문에, Chrome, Firefox 등 웹브라우저의
web security를 끈 인스턴스를 새로 시작해야 합니다.

윈도우에서 크롬의 경우 아래처럼 실행하면 됩니다. `chrome.exe`를 찾지 못했다고 뜬다면 적당한 경로를 입력해주세요.
```shell
chrome.exe --disable-web-security --disable-gpu --user-data-dir=%Temp%/chromeTemp
```
