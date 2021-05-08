# Angular
- Angular - The Complete Guide (2021 Edition) https://tcsglobal.udemy.com/course/the-complete-guide-to-angular-2/learn/lecture/6655670?start=15#content

## Angular - The Complete Guide (2021 Edition)

### Section 1: Getting Started

#### What is Angular
- Angular is a **JavaScript Framework** which allows you to create reactive **Single-Page-Applications** (SPAs).
- 이게 무슨 뜻이냐면, 웹페이지에 가면 index.html 딱 한 페이지만 보이는데, 이게 다른 거랑 연결되고 또 연결된거임.

#### Understanding Angular Version
- AngularJS는 엄청 다른데, Angular2에서 9까지는 6개월마다 업데이트하고 거의 비슷함.
![image](https://user-images.githubusercontent.com/68700599/117378071-4e7ddc80-ae9a-11eb-8d29-96f29c1bdb56.png)

#### Install angular
- npm install -g @angular/cli@latest

#### Project Setup 
- ng new my-first-app
- ng g c my-component
- cd my-first-app
- ng serve --open (running on localhost:4000)

#### Structure Behind
- index.html에 <app-root></app-root> 라는 걸 넣어둠. 그리고 app.component.ts에 있는 selector가 app-root라 그걸 그대로 연결하는 거임.
- [(ngModel)] = 여기에 써있는 거 듣고 바꿔줌. 물론 ngModel 쓰려면 import 고고.
---> <input type="text" [(ngModel)]="name"> 
---> app.module.ts에 import { FormsModule } from '@angular/forms' 

#### Course Structure
![image](https://user-images.githubusercontent.com/68700599/117461938-bde3e280-af13-11eb-8e2a-087fb087d2bf.png)

#### What is TypeScript?
![image](https://user-images.githubusercontent.com/68700599/117462074-e10e9200-af13-11eb-9ef0-f6f6b17e57d0.png)

### Section 2: The Basics

#### Component
- Components 다시 사용 가능하고 one page의 small parts를 각각 맡아용 (각각의 style business logic 등)
- @ 는 decorator. 우리가 만드는 components file이 component 라고 알려주는 것. 즉 @component. 근데 `ng g c my-component` 사용해서 만들면 미리 되어있음.
- ![image](https://user-images.githubusercontent.com/68700599/117480880-ce05bd00-af27-11eb-9f4c-aa1965138101.png)
- JavaScript object을 pass 해줘야 해서 {} 엏는거임
- ![image](https://user-images.githubusercontent.com/68700599/117480938-e07ff680-af27-11eb-8bfd-f241ce48968d.png)
- Component에 Selector 넣고 templateUrl 넣고
- ![image](https://user-images.githubusercontent.com/68700599/117480967-ebd32200-af27-11eb-96c5-758d73b6b155.png)

#### Module
- Components = build; modules = group together
- Component file을 그냥 add 만 한다고 angular이 이 파일 있다고 알진 않음. 모듈에 얘 있다~고 말해줘야 함
- ![image](https://user-images.githubusercontent.com/68700599/117481139-23da6500-af28-11eb-95e3-e663f4a73a3c.png)

#### Custom Component 넣는 법
- (1) 컴포넌트 만든다
- (2) 모듈에 넣는다
- (3) Main/root app component (html)에 만든 컴포넌트를 넣는다
- ![image](https://user-images.githubusercontent.com/68700599/117481676-ec1fed00-af28-11eb-98cb-a0ed8d9222af.png)
- ![image](https://user-images.githubusercontent.com/68700599/117481714-f7731880-af28-11eb-984c-656d0b1a7095.png)
- Components are reusable! 그래서 html에 두 번 써도 ㅇㅋ
- ![image](https://user-images.githubusercontent.com/68700599/117481757-078af800-af29-11eb-9283-c04ea91857ed.png)
- Ng g c 가 다 해주니만 하나는 해야 함: Main/root component html에 같이 넣어주는 것!

#### Databinding
- ![image](https://user-images.githubusercontent.com/68700599/117483297-2c806a80-af2b-11eb-8c45-48ce393c54aa.png)

#### String Interpolation
- String interpolation = {{ variable name }} String으로 만들 수 있음.
- ![image](https://user-images.githubusercontent.com/68700599/117483418-4e79ed00-af2b-11eb-8b7a-ba83b4f7fcde.png)
- ![image](https://user-images.githubusercontent.com/68700599/117483457-59cd1880-af2b-11eb-9356-318f40e8a503.png)
- Function (java용어로는 method)도 string interpolation 이서 부르기 가능함!
- ![image](https://user-images.githubusercontent.com/68700599/117483504-6b162500-af2b-11eb-96f5-d1a68e0a65f5.png)

#### Property Binding
- Property binding = state를 바꾸고 싶을 때 쓰는 것! [property]=“function 이름” 하면 ㅇㅋ.
- ![image](https://user-images.githubusercontent.com/68700599/117483623-897c2080-af2b-11eb-9f0c-8f47b66d41d0.png)
- ![image](https://user-images.githubusercontent.com/68700599/117543897-68c3d180-afe4-11eb-815e-e367cfcd5050.png)






### Section 3: Course PRoject - The Basics

### Section 4: Debugging

### Section 5: Components & Databinding Deep Dive

### Section 6: Course Project - Components & Databinding

### Section 7: Directives Deep Dive

### Section 8: Course Project - Directives

### Section 9: Using Services & Dependency Injection

### Section 10: Course Project - Services & Dependency Injection

### Section 11: Changing Pages with Routing

### Section 12: Course Project - Routing

### Section 13: Understanding Observables

### Section 14: Course Project - Observables

### Section 15: Handling Forms in Angualr Apps

### Section 16: Course Project - Forms

### Section 17: Using Pipes to Transform Output

### Section 18: Making Http Requests

### Section 19: Course Project - Http

### Section 20: Authentication & Route Protection in Angular

### Section 21: Dynamic Components

### Section 22: Angular Modules & Optimizing ANgular Apps

### Section 23: Deploying an Angular App

### Section 24: Bonus: Working with NgRx in our Project

### Section 25: Bonus: Angular Universal

### Section 26: Angular Animations

### Section 27: Adding Offline Capabilities with Service Workers

### Section 28: A Basic Inforduction to Unit Testing in Angular Apps

### Section 29: Angular as a Platform & Closer Look at the CLI

### Section 30: Angular CHanges & New Features

### Section 31: Course Roundup

### (DONE) Section 32: Bonus: TypeScript Introduction (for Angular 2 Usage)

#### What is TypeScript?
- TypeScript is a "superset" to JavaScript. (Still using syntax of JavaScript)
- 예 (아래처럼 type을 specify할 수 있어서 error을 더 줄여줌):
- ![image](https://user-images.githubusercontent.com/68700599/117462479-5712f900-af14-11eb-8dc4-589a7ce78fb7.png)

#### Base Type & Primitives
- variable 이름 넣을 때 무조건 lowercase! 왜냠 uppercase는 object를 refer함.
- ![image](https://user-images.githubusercontent.com/68700599/117463242-1071ce80-af15-11eb-8d16-784ea3dcc202.png)
- let age: number = 15; 으로도 쓸 수 있음.

#### Array & Object Types
- ![image](https://user-images.githubusercontent.com/68700599/117463844-b4f41080-af15-11eb-91b2-7f8067e4489e.png)
- ![image](https://user-images.githubusercontent.com/68700599/117463977-d523cf80-af15-11eb-8b31-fef9ed5a5357.png)

#### Type Inference
- TypeScript는 type을 쓰지 않아도 알아서 type이 string인지 알아서 에러가 뜨는 거임.
- 그래서 직접적으로 string이라고 specify하는 건 사실 redundant하고 그래서 ㄴㄴ함.
![image](https://user-images.githubusercontent.com/68700599/117464429-419ece80-af16-11eb-977a-dc18b3876b16.png)

#### Working with Union Types
- 여러가지 타입(union types)을 쓰고 싶으면 직접적으로 type을 써야함. | 사용함.
- ![image](https://user-images.githubusercontent.com/68700599/117464962-cbe73280-af16-11eb-86fc-afa135587f8f.png)
- ![image](https://user-images.githubusercontent.com/68700599/117465040-e4574d00-af16-11eb-9b74-598bcb7d268d.png)

#### Assigning Type Aliases
- 만든 type을 여러번 쓰고 싶을 때 쓰는 거.
---> 이걸 ![image](https://user-images.githubusercontent.com/68700599/117465299-28e2e880-af17-11eb-9703-169fd0541d5f.png)
---> 이렇게 바꿈 ![image](https://user-images.githubusercontent.com/68700599/117465335-36986e00-af17-11eb-80b1-7d51072b9a6f.png)
---> 혹은 이렇게 ![image](https://user-images.githubusercontent.com/68700599/117465386-444df380-af17-11eb-9959-ee82f6ea55ce.png)

#### Diving into Functions & Function Types
- return type을 infer함: ![image](https://user-images.githubusercontent.com/68700599/117465753-a0b11300-af17-11eb-8f88-bc87331e4f79.png)
- 혹은 return value를 이렇게 define할 수도 있음 (물론 왠만하면 진짜 필요하지 않은 이상 ㄴㄴ함): ![image](https://user-images.githubusercontent.com/68700599/117465874-bcb4b480-af17-11eb-8b80-cbb39b066d47.png)
- 아무 return 없으면 void로 세팅됨: ![image](https://user-images.githubusercontent.com/68700599/117466063-f1287080-af17-11eb-97bd-d4ab5e37746d.png)
- *참고: print는 이미 JS에서 쓰고 있는 function 이름이라 다른 걸로 바꿔야 함; printOutput 이라던지.

#### Understanding Generics
- ...array = copy the existing array
- Type을 any라고 쓰면 에러가 안 뜸. 근데 T라고 쓰면 T라고 쓰진 애들은 전부 다 같다는 뜻이라 에러가 뜸. 
- ![image](https://user-images.githubusercontent.com/68700599/117475135-52087680-af21-11eb-923c-b4de0228e169.png)
- 그게 넘버든 string이든 상관은 없음. 다 같으면 됨.
- ![image](https://user-images.githubusercontent.com/68700599/117475324-81b77e80-af21-11eb-892b-8461d3c6b814.png)

#### Classes & TypeScript
- JS는 type을 세팅할 수 없지만, TS는 됨! 
- ![image](https://user-images.githubusercontent.com/68700599/117475543-c80cdd80-af21-11eb-9c6f-e78650aefd4d.png)
- 그리고 public/private도 세팅 가능함! (public은 .으로 access할 수 있는 거.)
- ![image](https://user-images.githubusercontent.com/68700599/117475829-20dc7600-af22-11eb-884b-453cd7625c34.png)
- 이런 public/private은 constructor에서 세팅 가능 ㅇㅇ. 위에 쓴 건 comment해도 똑같은 result임.
- ![image](https://user-images.githubusercontent.com/68700599/117475950-3ea9db00-af22-11eb-8b2a-332810fa0ef5.png)

#### Working with Interfaces
- Interfaces = object type definition
- 이렇게 method 쓰는 거 아님!!: ![image](https://user-images.githubusercontent.com/68700599/117476155-7ca6ff00-af22-11eb-9160-4e3a2cd329d3.png)
- 이렇게 써서 type을 알려줘야 함: ![image](https://user-images.githubusercontent.com/68700599/117476364-99433700-af22-11eb-81a7-38c675eb2a2f.png)
- 이렇게 쓴 다음, 하나 object 만들 땐, type에 있는 거 전부 specify해줘야 함 (i.e., firstName, age, greet()): ![image](https://user-images.githubusercontent.com/68700599/117476738-cd1e5c80-af22-11eb-85c3-199e5563f1b4.png)
- 이거 사실 type Human = {...} 라고 써도 됨. 근데 interface는 좋은 점이 더 있음. 뭐냐면 클래스들이 이런 interface를 쓰면 정확하게 룰 따라 쓸 수 있게 도와줌. 즉 firstName, age, greet()을 제대로 넣고 또 쓸 수 있게 도와줌: ![image](https://user-images.githubusercontent.com/68700599/117477126-39995b80-af23-11eb-9f0c-d2401d70244a.png)
