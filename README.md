# 🚀 Antigravity Skills Collection

Antigravity IDE에서 사용하는 스킬(기능 확장 모듈) 모음입니다.  
여러 기기(맥북, 맥미니, 윈도우 PC)에서 동일한 환경을 유지하기 위한 동기화 저장소입니다.

---

## 📌 스킬(Skill)이란?

**스킬**은 AI 어시스턴트가 특정 작업을 더 잘 수행할 수 있도록 도와주는 **전문 지식 패키지**입니다.

예를 들어:
- `python` 스킬 → Python 코딩을 더 잘 도와줌
- `flutter` 스킬 → Flutter 앱 개발을 도와줌
- `playwright-testing` 스킬 → 웹 테스트 자동화를 도와줌

---

## 📂 포함된 스킬 목록 (69개)

### 🌐 웹 개발
| 스킬명 | 설명 |
|--------|------|
| `react-web` | React 웹 프론트엔드 개발 |
| `nodejs-backend` | Node.js 백엔드 개발 |
| `typescript` | TypeScript 언어 지원 |
| `frontend_design` | 프론트엔드 디자인 가이드 |
| `pwa-development` | Progressive Web App 개발 |
| `site-architecture` | 웹사이트 구조 설계 |

### 📱 모바일 개발
| 스킬명 | 설명 |
|--------|------|
| `flutter` | Flutter 크로스플랫폼 앱 개발 |
| `react-native` | React Native 앱 개발 |
| `android-kotlin` | Android Kotlin 개발 |
| `android-java` | Android Java 개발 |
| `ios-simulator-skill` | iOS 시뮬레이터 사용 |
| `ui-mobile` | 모바일 UI 디자인 |

### 🐍 Python & 데이터
| 스킬명 | 설명 |
|--------|------|
| `python` | Python 프로그래밍 |
| `d3_visualization` | D3.js 데이터 시각화 |
| `ai-models` | AI 모델 활용 |

### 🗄️ 백엔드 & 데이터베이스
| 스킬명 | 설명 |
|--------|------|
| `supabase` | Supabase 백엔드 서비스 |
| `supabase-nextjs` | Supabase + Next.js 연동 |
| `supabase-node` | Supabase + Node.js 연동 |
| `supabase-python` | Supabase + Python 연동 |
| `database-schema` | 데이터베이스 스키마 설계 |

### 🧪 테스트 & 품질
| 스킬명 | 설명 |
|--------|------|
| `playwright-testing` | Playwright 웹 테스트 |
| `playwright_skill` | Playwright 고급 기능 |
| `ui-testing` | UI 테스트 자동화 |
| `test-driven-development` | TDD 개발 방법론 |
| `systematic-debugging` | 체계적 디버깅 기법 |

### 📋 코드 관리 & Git
| 스킬명 | 설명 |
|--------|------|
| `git_pushing` | Git 푸시 가이드 |
| `commit-hygiene` | 깔끔한 커밋 작성법 |
| `code-review` | 코드 리뷰 가이드 |
| `receiving-code-review` | 코드 리뷰 받기 |
| `requesting-code-review` | 코드 리뷰 요청하기 |
| `using-git-worktrees` | Git Worktree 활용 |

### 🛡️ 보안 & 인증
| 스킬명 | 설명 |
|--------|------|
| `security` | 보안 모범 사례 |
| `credentials` | 인증 정보 관리 |

### 📝 문서화 & 브랜딩
| 스킬명 | 설명 |
|--------|------|
| `document_suite` | 문서 작성 도구 |
| `changelog_generator` | 변경 로그 생성 |
| `brand_guidelines` | 브랜드 가이드라인 |

### 🎨 디자인 & 아트
| 스킬명 | 설명 |
|--------|------|
| `canvas-design` | 캔버스 디자인 |
| `algorithmic-art` | 알고리즘 아트 생성 |
| `ui-web` | 웹 UI 디자인 |

### 🔧 개발 프로세스
| 스킬명 | 설명 |
|--------|------|
| `agentic-development` | 에이전트 기반 개발 |
| `iterative-development` | 반복적 개발 방법론 |
| `executing-plans` | 계획 실행 가이드 |
| `writing-plans` | 계획 작성 가이드 |
| `project-tooling` | 프로젝트 도구 설정 |
| `verification-before-completion` | 완료 전 검증 |
| `finishing-a-development-branch` | 개발 브랜치 마무리 |

### 🔍 기타 유틸리티
| 스킬명 | 설명 |
|--------|------|
| `brainstorming` | 브레인스토밍 지원 |
| `research_assistant` | 리서치 도우미 |
| `skill_creator` | 새 스킬 생성 도구 |
| `skill-seekers` | 스킬 검색 |
| `artifacts_builder` | 아티팩트 빌더 |
| `deployment_helper` | 배포 도우미 |
| `code_tutor` | 코딩 튜터 |
| `canva-mcp` | Canva MCP 연동 |
| `notebooklm-skill` | NotebookLM 연동 |
| `ffuf-web-fuzzing` | 웹 퍼징 도구 |

---

## 🔧 설치 방법

### 다른 PC에서 스킬 동기화하기

```bash
# 1. 기존 스킬 폴더로 이동 (없으면 생성)
cd ~/.gemini/antigravity/.agent/skills

# 2. 저장소 클론 (기존 폴더가 비어있다면)
git clone https://github.com/dudqks0319-cpu/antigravity-skills.git .

# 또는 기존 폴더가 있다면 pull
git pull origin main
```

---

## 🔄 동기화 방법

### 변경사항 업로드 (이 PC → GitHub)
```bash
cd ~/.gemini/antigravity/.agent/skills
git add -A
git commit -m "스킬 업데이트"
git push
```

### 변경사항 다운로드 (GitHub → 이 PC)
```bash
cd ~/.gemini/antigravity/.agent/skills
git pull
```

---

## 📅 최종 업데이트
- 날짜: 2026-01-17
- 스킬 개수: 69개
