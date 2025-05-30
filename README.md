# 🧮 계산기 프로젝트

Swift로 구현한 사칙연산 계산기 프로젝트입니다.  
단계별로 기능을 확장하고, OOP 원칙(단일 책임 원칙, 추상화 등)을 고려하여 개발되었습니다.

---

## 📌 프로젝트 소개

이 프로젝트는 다음을 목표로 합니다:

- 기본적인 사칙연산 수행  
- 나머지 연산 및 예외 처리 추가  
- 연산별 클래스로 분리 및 추상화 적용  
- 단위 테스트 작성 (선택)

---

## 🛠 기능 목록

- [x] 더하기, 빼기, 곱하기, 나누기 연산  
- [x] 나머지 연산  
- [x] 0으로 나누기 예외 처리  
- [x] 연산별 클래스로 분리  
- [x] 추상화 프로토콜(AbstractOperation) 적용  
- [ ] 사용자 입력에 따른 CLI 인터페이스 (선택)  
- [ ] 단위 테스트 (선택)

---

## 📦 기술 스택

- Swift 5.9  
- Xcode 15  
- (선택) CommandLine / iOS Playground  
- OOP 원칙 적용

---

## 📁 디렉토리 구조

```
Calculator/
├── Calculator.swift
├── AddOperation.swift
├── SubtractOperation.swift
├── MultiplyOperation.swift
├── DivideOperation.swift
├── ModuloOperation.swift
├── AbstractOperation.swift
└── main.swift
```

---

## 🚀 실행 방법

💡 Xcode Playground 또는 Swift CLI 환경에서 실행 가능

### ▶️ Playground  
1. Xcode에서 새로운 Playground 생성  
2. Calculator 관련 클래스를 붙여넣기  
3. `let calculator = Calculator()` 로 테스트  

### ▶️ CLI  

```bash
swift main.swift
```

---

## 🧪 예시 실행 결과

```swift
let calc = Calculator()
print(calc.add(a: 4, b: 2))     // 6
print(calc.divide(a: 10, b: 2)) // 5
print(calc.modulo(a: 7, b: 3))  // 1
```

---

## 🤔 개선 포인트 (Lv3 → Lv4)

- 연산별 클래스로 분리하여 코드의 책임 분리  
- `AbstractOperation` 프로토콜로 추상화 적용 → 유지보수성 증가  
- 추후 테스트 및 UI 인터페이스로 확장 용이

---

## 📝 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.  
자세한 내용은 `LICENSE` 파일을 참고하세요.

---

## 🙋‍♀️ 만든 사람

송명균 – [GitHub 프로필](https://github.com/yourgithub)
