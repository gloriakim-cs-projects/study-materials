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

### Section 32: Bonus: TypeScript Introduction (for Angular 2 Usage)

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
- 





