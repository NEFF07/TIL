# 6장 객체와 자료 구조

## 기억하고 싶은 내용

> 객체 지향 코드에서 어려운 변경은 절차적인 코드에서 쉬우며, 절차적인 코드에서 어려운 변경은 객체 지향 코드에서 쉽다! (...) 분별 있는 프로그래머는 모든 것이 객체라는 생각이 미신임을 잘 안다. 때로는 단순한 자료 구조와 절차적인 코드가 가장 적합한 상황도 있다. (p.122)

> 이런 혼란으로 말미암아 때때로 절반은 객체, 절반은 자료 구조인 잡종 구조가 나온다.
> 이런 잡종 구조는 새로운 함수는 물론이고 새로운 자료 구조도 추가하기 어렵다. 양쪽 세상에서 단점만 모아놓은 구조다. 그러므로 잡종 구조는 되도록 피하는 편이 좋다. (p.125)

## 소감 및 생각

자료구조와 객체에 대해서, 상당히 어려운 내용을 배웠다. 

개인적으로 정리하자면, 자료구조는 명사, 객체는 동사랄까..? 

## 새롭게 배운 개념

### 자료 전달 객체

자료 구조체의 전형적인 형태는 공개 변수만 있고 함수가 없는 클래스다. 이런 자료 구조체를 때로는 자료 전달 객체(Data Transfer Object)라 한다. DTO는 굉장히 유용한 구조체다. 특히 데이터베이스와 통신하거나 소켓에서 받은 메시지의 구문을 분석할 때 유용하다.

### 자료구조 VS 객체

객체는 동작을 공개하고 자료를 숨긴다. 그래서 기존 동작을 변경하지 않으면서 새 객체 타입을 추가하기는 쉬운 반면, 기존 객체에 새 동작을 추가하기는 어렵다. (p.127)

자료 구조는 별다른 동작 없이 자료를 노출한다. 그래서 기존 자료 구조에 새 동작을 추가하기는 쉬우나, 기존 함수에 새 자료 구조를 추가하기는 어렵다. (p.127)

시스템을 구현할 때, 새로운 자료 타입을 추가하는 유연성이 필요하면 객체가 더 적합하다. 새로운 동작을 추가하는 유연성이 필요하면 자료 구조와 절차적인 코드가 더 적합하다. 우수한 소프트웨어 개발자는 편견 없이 이 사실을 이해해 직면한 문제에 최적인 해결책을 선택한다. (p.128)
