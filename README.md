# TCS Interview Prep
This is a note to write TCS interview prep, including Java, SQL, Angular8, and NodeJS.

## Java
- https://www.w3schools.com/java/
- https://www.youtube.com/watch?v=oJlCC1DutbA&list=PLW2UjW795-f6xWA2_MUhEVgPauhGl3xIp

### 자바의 정석

#### 챕터 1

<정보>
- 실행환경(JRE) + 개발도구(JDK = Java Development Kit) + 라이브러리(API) 
- 라이브러리 = 다른 사람이 미리 만들어 논 걸 제공하는 것
- 멀티 쓰레드 = 여러 개의 작업 가능 = 채팅하면서 파일도 주고 받을 수 있는 것
- 자바가상머신(JVM = Java Virtual Machine) = 한번 작성하면 어디서든 실행 (write once, run everywhere)

<기본>
- class 클래스이름 { public static void main(String[] args) {...} }
- main 메서드가 꼭 있어야 함!

<이클립스 단축키>
- ctrl+shift+L (단축키 전체 목록 나옴)
- ctrl + +,- (확대 축소)
- ctrl + D (한 줄 삭제)
- ctrl+alt+down (한 줄 아래로 복사) (윈도수 단축키와 충돌된 경우 ctrl+alt+up 하면 다시 돌아옴) (바꿀려면 Windows - Preferences -> General -> Keys -> Copy lines -> 단축키 바꿈)
- shift + down (여러 줄 한 번에 바꿈)
- alt+shift+A (여러 줄 한 번에 바꿈 / 토글)
- alt+up/down (줄 아예 이동)
- ctrl + i (자동 들여/띄여쓰기)
- ctrl + space (자동완성) (예: sysout이라고 쓴 뒤 ctrl + space 면 system.out.printLn()이 뜸)

#### 챕터 2

<변수(variable)>
- 하나의 값을 저장할 수 있는 메모리공간 
- 지역변수는 읽기 전에 꼭! 초기화 해야 함 (즉, int x = 0; 라고 최소한 써놔야 함)

<변수 타입>
![image](https://user-images.githubusercontent.com/68700599/115926033-be767680-a447-11eb-8975-0b696c3fa6af.png)

<상수(constant)>
- final int MAX = 100;

<리터럴(literal)>
- 그 자체로 값을 의미. 즉 위의 같은 경우는 100. 

<문자(char)과 문자열(string)>
- char ch = 'A';
- String s = "ABC";
- String s = ""; //empty string
- String s = "AB" + "CD" //문자열 결합

<기본형(primitive type)과 참조형(reference type)>
- 기본형: 오직 8개 (boolean, char, byte, short, int, long, float, double); 실제 값을 저장
- 참고형: 나머지 다 (String, System, Date 등); 메모리 주소를 저장
![image](https://user-images.githubusercontent.com/68700599/115926738-f336fd80-a448-11eb-8963-01c5109e250b.png)

<기본형 범위/크기>
![image](https://user-images.githubusercontent.com/68700599/115926894-31ccb800-a449-11eb-8d2c-08398defbda9.png)

<printf를 이용한 출력>
![image](https://user-images.githubusercontent.com/68700599/115927152-97b93f80-a449-11eb-99b2-8c57befa7f41.png)

![image](https://user-images.githubusercontent.com/68700599/115927358-e535ac80-a449-11eb-8810-036ad1faf2c8.png)

![image](https://user-images.githubusercontent.com/68700599/115927476-1ada9580-a44a-11eb-8844-993bfa5eb6f0.png)


## SQL

## Angular8

## NodeJS
