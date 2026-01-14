---
name: changelog_generator
description: 변경 로그 자동 생성 스킬. "변경 로그 만들어줘", "업데이트 내역 정리해줘" 요청 시 활성화.
---

# Changelog Generator 📝

프로젝트 변경 로그를 자동으로 생성하는 스킬입니다.

## CHANGELOG.md 형식

```markdown
# Changelog

## [1.0.1] - 2026-01-15

### Added
- 새로 추가된 기능

### Changed
- 변경된 기능

### Fixed
- 수정된 버그
```

## 워크플로우

1. **Git 히스토리 분석**: 최근 커밋 확인
2. **변경사항 분류**: Added/Changed/Fixed 분류
3. **한글 요약**: 사용자 이해하기 쉽게 작성
4. **파일 생성**: CHANGELOG.md 생성/업데이트

## 카테고리

| 카테고리 | 영문 | 설명 |
|----------|------|------|
| 추가 | Added | 새 기능 |
| 변경 | Changed | 기존 기능 수정 |
| 수정 | Fixed | 버그 수정 |
| 삭제 | Removed | 기능 삭제 |
