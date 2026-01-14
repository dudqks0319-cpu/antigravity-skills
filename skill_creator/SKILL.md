---
name: skill_creator
description: 새로운 스킬을 만드는 도우미 스킬. "스킬 만들어줘", "새 스킬 추가해줘" 요청 시 활성화.
---

# Skill Creator 🛠️

새로운 커스텀 스킬을 만드는 도우미입니다.

## 스킬 생성 워크플로우

1. **목적 파악**: 어떤 작업을 자동화할지 확인
2. **이름 결정**: 스킬 이름 (영문, snake_case)
3. **트리거 정의**: 언제 이 스킬이 활성화될지
4. **규칙 작성**: 스킬이 따를 지침
5. **파일 생성**: `.agent/skills/[이름]/SKILL.md`

## SKILL.md 템플릿

```markdown
---
name: [스킬_이름]
description: [언제 활성화되는지 설명]
---

# [스킬 제목]

[스킬 설명]

## 규칙

1. ...
2. ...

## 예시

...
```

## 저장 위치

```
~/.gemini/antigravity/.agent/skills/
└── [스킬_이름]/
    └── SKILL.md
```
