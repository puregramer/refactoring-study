---
title: "4장"
categories:
  - puregramer
---

### 4장, 타입 코드 처리하기
  
## 간단한 if 문 리팩터링
  - if 문에서 else 사용하지 말 것(!)
    
  > if-else는 하드코딩된 결정으로 볼 수 있다. if 문은 **검사**로 간주하고, if-else문은 **의사결정**으로 간주함

  - if-else 동작은 컴파일 시 처리되어 재컴파일 없이는 수정 불가 (이른 바인딩)
  - 반대 개념인 늦은 바인딩은 추가를 통한 변경이 가능함
  - 객체로 흐름을 제어하라
  - 클래스로 타입 코드 대체

