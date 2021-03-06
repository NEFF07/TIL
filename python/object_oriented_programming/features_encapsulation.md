# 캡슐화

> - 클래스에서 사용하는 변수와 함수는 하나의 클래스 안에 모아져 있어야 한다.

- 객체의 일부 구현 내용에 대해 외부로부터의 직접적인 액세스를 차단하는 것

- 파이썬에선 공식적으론 존재하지 않음.

## 접근제어자

> Python에선 접근 제어 정도가 강하지 않다.

- Public Access Modifier 아무나 볼 수 있는

- Protected Access Modifier 중간 정도

- Private Access Modifier 아주 프라이빗

### Public Member

- 언더바 없이 시작하는 메서드나 속성

- 어디서나 호출이 가능, 하위 클래스 override 허용

- 일반적인 메서드와 속성

### Protected Member

- 언더바 1개로 시작하는 메서드나 속성

- **암묵적 규칙**에 의해 클래스 내부 또는 부모 클래스에서만 호출 가능

    - 에러는 아니다.

- 하위 클래스 override 허용

### Private Member

- 언더바 2개로 시작하는 메서드나 속성

- 본 클래스 내부에서만 사용이 가능

- 하위클래스 상속 및 호출 불가능(오류)

> getter, setter method를 사용해서 호출한다.

## getter 메서드, setter 메서드

> 왜 직접 호출을 막을까?

- 캡슐화하려는 목적

- getter, setter 메서드로 특정 처리를 거쳐가는 용도로 활용할 수 있다. 

> 우회해서 가져오는 방법

- 변수에 접근할 수 있는 메서드를 별도로 생성

    - getter 메서드 : 변수의 값을 읽는 메서드

        - `@property` 데코레이터 사용

    - setter 메서드 : 변수의 값을 설정하는 메서드

        - `@변수.setter` 사용

- getter, setter를 설정해두면, 마치 변수처럼 사용할 수 있다. 함수를 호출할 필요 없이 자동으로 적용된다.

> getter, setter method를 더 편하게 사용하는 방법

[링크](https://www.daleseo.com/python-property/)