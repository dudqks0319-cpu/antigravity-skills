---
name: canva-mcp
description: Canva 디자인 도구 연동 가이드. MCP를 통해 Claude/AI 에이전트에서 Canva 디자인 생성/편집 가능. "캔바로 디자인해줘", "인스타그램 포스트 만들어줘" 요청 시 참고.
---

# Canva MCP 연동 가이드 🎨

Canva를 AI 에이전트와 연동하여 디자인을 자동화하는 방법입니다.

## ⚠️ 중요 안내

**Canva는 "스킬"이 아니라 "MCP 커넥터"로 연동됩니다.**

| 방식 | 스킬 (Skill) | MCP 커넥터 |
|------|-------------|-----------|
| 동작 | 지침서 읽고 따름 | 외부 서비스 API 호출 |
| Canva | ❌ | ✅ |

---

## 📋 Canva MCP 연결 방법

### 요구사항
- Claude Pro 또는 Team 구독
- Canva 계정 (Pro 권장)

### 연결 단계

1. **Claude.ai** 접속
2. **Settings** → **Connectors** 이동
3. **MCP** 선택
4. **Canva** 커넥터 활성화
5. Canva 계정 로그인 및 권한 허용

---

## 💡 할 수 있는 것들

```
"인스타그램 포스트 만들어줘"
"소셜 미디어 카러셀 생성해줘"
"이 디자인 PNG로 내보내줘"
"Canva 템플릿 검색해줘"
```

---

## ⚠️ Antigravity에서의 사용

현재 Antigravity에서 Canva MCP 직접 연동은 **지원되지 않습니다**.

### 대안
1. **browser_subagent** 사용: Canva 웹사이트 직접 조작
2. **generate_image** 사용: AI 이미지 생성 후 수동으로 Canva에 업로드
3. **Claude.ai 웹** 사용: Claude.ai에서 Canva MCP 연동 후 작업

---

## 📚 참고 자료

- [Canva MCP 공식 문서](https://www.canva.com/help/)
- [Claude Connectors](https://claude.ai/settings/connectors)
