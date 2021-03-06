# 5장 형식 맞추기

## 기억하고 싶은 내용

> 이름은 간단하면서도 설명이 가능하게. 이름만 보고도 올바른 모듈을 살펴보고 있는지 아닌지를 판단할 정도로 신경써서 짓는다.
소스 파일 **첫 부분은 고차원 개념과 알고리즘을 설명**한다.
**아래로 내려갈수록 의도를 세세하게 묘사**한다.
**마지막에는 가장 저차원 함수와 세부 내역**이 나온다. (p.98)
>

> **각 행은 수식이나 절**을 나타내고, **일련의 행 묶음은 완결된 생각 하나를 표현**한다. **생각 사이에는 빈 행을 넣어 분리**해야 마땅하다.
**빈 행**은 **새로운 개념을 시작**한다는 시각적 단서다. 코드를 읽어 내려가다 보면 빈 행 바로 다음 줄에 눈길이 멈춘다. (p.98)
>

> 일반적으로 C++에서는 모든 인스턴스 변수를 클래스 마지막에 선언한다.
반면 JAVA에서는 보통 클래스 맨 처음에 인스턴스 변수를 선언한다.
**잘 알려진 위치**에 **인스턴스 변수**를 모은다는 사실이 중요하다. (p.103)
>

> **한 함수가 다른 함수를 호출**한다면 두 함수는 **세로로 가까이 배치**한다. 호출하는 함수를 호출되는 함수보다 먼저 배치한다. 그러면 프로그램이 자연스럽게 읽힌다. (p.104)


## 소감 및 생각

### 잘 쓰여진 글같은 코드
변수와 함수의 선언문, 함수의 호출 등을 배치함에 있어서 어떻게 배치하는 것이 좋을 지 감이 잡힌 것 같다. 잘 쓰여진 신문과 같이, 우리의 코드도 잘 짜여진 하나의 글처럼 막힘없이 읽혀야 할 것이다.
### Enter와 Spacebar의 의도까지도 생각해
또한 개행과 띄어쓰기도 단락과 문장의 가독성을 도와주는 도구이다. 그러므로 Enter와 Spacebar를 누르는 것도 함부로 해선 안될 것이다.

## 새롭게 배운 개념

- 클래스 변수, 인스턴스 변수, 지역 변수
    - **클래스 변수**는 클래스 영역에서 선언되고 static으로 선언된다. public을 붙이면 전역 변수가 된다.
    - **인스턴스 변수**는 클래스 영역에서 선언된다.
    - **지역 변수**는 함수, 메서드에서 선언된다.

- 행을 의도적으로 분리하는 습관이 필요하다.
**Enter** 한 번 누르는 것에도 생각이 있어야 한다.


- **쉼표, 띄어쓰기**를 이용해서 요소의 관계를 나타낼 수 있다.
다음은 관계를 나타내는 예시
    - 연산자를 강조
    - 함수와 인수 관계
    - 인수간의 관계
    - 연산자 우선순위 강조
