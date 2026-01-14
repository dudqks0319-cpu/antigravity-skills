# 🎨 Youngbeen Skills

> Antigravity AI 에이전트를 위한 커스텀 스킬 모음집

## 📌 스킬이란?

**스킬(Skill)**은 AI에게 주는 **"작업 매뉴얼"**입니다.

```
사용자: "버그 고쳐줘"
→ AI가 systematic-debugging 스킬을 읽고
→ 체계적인 4단계 디버깅 프로세스 적용
→ 더 정확하고 효율적인 결과!
```

## 🚀 빠른 설치

다른 PC에서 복원할 때:
```bash
git clone https://github.com/dudqks0319-cpu/youngbeen-skills.git ~/.gemini/antigravity/.agent/skills
```

---

## 📦 스킬 목록 (64개)

### 🎼 Core - 핵심 스킬

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `youngbeen_mode` | 메인 AI 비서 페르소나 | 항상 적용 |
| `base` | 기본 TDD 워크플로우 | 코드 작성 시 |
| `security` | 보안 패턴 | 민감 작업 시 |
| `credentials` | API 키 관리 | 인증 설정 시 |
| `code_tutor` | 비개발자용 설명 | 질문할 때 |

### 🧪 Testing & Debugging

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `systematic-debugging` | 체계적 4단계 디버깅 | 버그 수정 시 ⭐ |
| `test-driven-development` | 테스트 우선 개발 | 새 기능 개발 |
| `verification-before-completion` | 완료 전 검증 | 작업 마무리 |
| `playwright-testing` | E2E 웹 테스트 | 웹앱 테스트 |
| `ui-testing` | UI 테스트 | 화면 검증 |

### 📱 Mobile Development

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `ios-simulator-skill` | iOS 시뮬레이터 제어 | iOS 앱 테스트 |
| `react-native` | React Native 개발 | 모바일 앱 |
| `flutter` | Flutter 개발 | 크로스플랫폼 |
| `android-java` | Android Java | 안드로이드 |
| `android-kotlin` | Android Kotlin | 안드로이드 |
| `ui-mobile` | 모바일 UI 가이드 | 모바일 디자인 |

### 🎨 UI/UX Design

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `frontend_design` | 프론트엔드 디자인 | UI 제작 |
| `ui-web` | 웹 UI (다크모드, 접근성) | 웹 디자인 |
| `brand_guidelines` | 브랜드 일관성 | 디자인 통일 |
| `user-journeys` | UX 흐름 설계 | 사용자 경험 |
| `pwa-development` | PWA 개발 | 오프라인 앱 |

### 💻 Languages & Frameworks

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `typescript` | TypeScript 개발 | TS 프로젝트 |
| `python` | Python 개발 | Python 코드 |
| `nodejs-backend` | Node.js 백엔드 | 서버 개발 |
| `react-web` | React 웹 개발 | React 앱 |
| `supabase` | Supabase 연동 | DB/인증 |

### 🤖 AI & Agents

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `agentic-development` | AI 에이전트 개발 | 에이전트 제작 |
| `llm-patterns` | LLM 앱 패턴 | AI 앱 개발 |
| `ai-models` | AI 모델 레퍼런스 | 모델 선택 |
| `notebooklm-skill` | NotebookLM 연동 | 문서 기반 질문 |

### 🔧 Utilities

| 스킬 | 설명 | 사용 시점 |
|------|------|----------|
| `git_pushing` | Git 커밋/푸시 | 코드 업로드 |
| `changelog_generator` | 변경 로그 생성 | 버전 관리 |
| `code-review` | 코드 리뷰 | 품질 점검 |
| `deployment_helper` | 배포 도우미 | 사이트 배포 |
| `document_suite` | 문서 생성 (Word/Excel) | 보고서 작성 |
| `research_assistant` | 정보 조사 | 리서치 |
| `d3_visualization` | 데이터 시각화 | 차트 제작 |

---

## 💡 사용 방법

### 자동 활성화
자연어로 요청하면 관련 스킬이 자동으로 적용됩니다:

```
"버그 찾아줘" → systematic-debugging 적용
"iOS 앱 테스트해줘" → ios-simulator-skill 적용
"차트 만들어줘" → d3_visualization 적용
```

### 스킬 직접 호출
특정 스킬을 명시적으로 사용하고 싶을 때:
```
"systematic-debugging 스킬로 이 에러 분석해줘"
```

---

## 📁 폴더 구조

```
~/.gemini/antigravity/.agent/skills/
├── youngbeen_mode/     # 메인 페르소나
│   └── SKILL.md
├── systematic-debugging/
│   ├── SKILL.md
│   └── *.md (부가 자료)
├── ios-simulator-skill/
│   ├── SKILL.md
│   └── scripts/       # Python 스크립트
└── ... (64개 스킬)
```

---

## 🔄 업데이트

최신 스킬로 업데이트:
```bash
cd ~/.gemini/antigravity/.agent/skills
git pull
```

---

## 📖 출처

- [Superpowers](https://github.com/obra/superpowers) (14개)
- [Claude Bootstrap](https://github.com/alinaqi/claude-bootstrap) (35개)
- [iOS Simulator Skill](https://github.com/conorluddy/ios-simulator-skill)
- [NotebookLM Skill](https://github.com/PleasePrompto/notebooklm-skill)
- Custom (Youngbeen Mode 등)

---

## 📝 라이선스

MIT License - 자유롭게 사용하세요!

---

Made with ❤️ by Youngbeen
