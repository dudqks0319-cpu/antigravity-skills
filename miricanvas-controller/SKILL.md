---
name: Miricanvas Controller
description: Puppeteer를 사용하여 미리캔버스(MiriCanvas)를 제어하고 디자인 작업을 자동화합니다.
---

# Miricanvas Controller (Experimental)

이 스킬은 Puppeteer MCP를 활용하여 미리캔버스 웹사이트를 제어합니다. 공식 API가 아닌 웹 자동화 방식이므로 사이트 구조 변경에 따라 동작하지 않을 수 있습니다.

## 사용 방법
Claude에게 다음과 같이 요청하세요:

1.  **로그인**: "미리캔버스에 로그인해줘" (브라우저가 열리면 직접 로그인해야 할 수 있음)
2.  **템플릿 검색**: "미리캔버스에서 '겨울 이벤트' 템플릿 검색해줘"
3.  **스크린샷**: "현재 디자인 화면 캡쳐해줘"

## 내부 동작 (Pseudo-Code)
이 스킬은 내부적으로 `puppeteer` 도구를 호출하여 다음을 수행합니다:

```javascript
// 검색 예시
await page.goto('https://www.miricanvas.com/templates');
await page.type('input[type="search"]', '검색어');
await page.keyboard.press('Enter');
```

## 주의사항
*   **로그인 세션**: 브라우저를 닫으면 로그인이 풀릴 수 있습니다.
*   **속도**: 웹 페이지 로딩 속도에 따라 동작이 지연될 수 있습니다.
*   **요소 선택자**: 미리캔버스 웹사이트의 CSS 클래스명이 변경되면 스크립트 수정이 필요합니다.
