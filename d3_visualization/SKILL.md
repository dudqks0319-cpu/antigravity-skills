---
name: d3_visualization
description: D3.js 데이터 시각화 스킬. "차트 만들어줘", "그래프 만들어줘", "시각화해줘" 요청 시 활성화.
---

# D3.js Visualization 📊

D3.js를 사용하여 데이터를 시각화하는 스킬입니다.

## 지원 차트 유형

| 차트 | 용도 |
|------|------|
| 막대 차트 | 항목별 비교 |
| 라인 차트 | 추세/변화 |
| 파이 차트 | 비율/구성 |
| 도넛 차트 | 비율 (중앙 라벨) |
| 스캐터 플롯 | 상관관계 |

## 기본 템플릿

```html
<!DOCTYPE html>
<html>
<head>
  <script src="https://d3js.org/d3.v7.min.js"></script>
</head>
<body>
  <div id="chart"></div>
  <script>
    // D3.js 코드
  </script>
</body>
</html>
```

## 스타일 가이드

- 색상: 모던 그라디언트 팔레트
- 애니메이션: 부드러운 전환 효과
- 반응형: SVG viewBox 활용
- 접근성: 툴팁, 레이블 포함
