# 📘 Code Review Checklist

## ✅ PR 이해
- [ ] PR 제목과 설명이 명확한가?
- [ ] 어떤 기능/이슈를 다루는지 설명이 되어 있는가?

---

## 🔍 코드 품질
- [ ] 로직이 명확하고 이해하기 쉬운가?
- [ ] 중복된 코드가 없는가?
- [ ] 함수/메서드는 하나의 책임만 갖고 있는가 (SRP)?
- [ ] 변수 및 함수 이름이 의미 있게 지어졌는가?
- [ ] 하드코딩된 값이 적절히 처리되었는가 (상수 처리 등)?

---

## 🛠️ 성능/보안/확장성
- [ ] 성능 이슈가 발생할 가능성은 없는가? (e.g., 반복문, 쿼리 등)
- [ ] 외부 입력 값에 대한 검증은 충분한가?
- [ ] 확장 가능성을 고려한 설계인가 (기능 추가 시 유연함)?

---

## 🧪 테스트 및 신뢰성
- [ ] 유닛 테스트 또는 통합 테스트가 존재하는가?
- [ ] 엣지 케이스에 대한 처리가 있는가?
- [ ] 예외 처리가 적절히 이루어졌는가?

---

## 📝 스타일 및 가독성
- [ ] 팀의 코딩 스타일 가이드에 부합하는가? (e.g., Lint 규칙)
- [ ] 불필요한 주석이나 디버깅 코드가 없는가?
- [ ] 변경된 코드가 기존 구조와 잘 어울리는가?

---

## 🤝 커뮤니케이션
- [ ] 리뷰 코멘트는 명확하고 공손하게 작성되었는가?
- [ ] 제안은 명령이 아닌 제안 형태로 표현되었는가?
- [ ] 칭찬할 부분은 피드백과 함께 언급되었는가?
