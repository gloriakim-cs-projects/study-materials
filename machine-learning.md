# Machine Learning

- Udemy: An Introduction to MAchine Learning for Data Engineers

## Udemy: An Introduction to MAchine Learning for Data Engineers

### Section 1: An Introduction
- The Modeling Process: 
- ![image](https://user-images.githubusercontent.com/68700599/117920525-9c3c7f80-b2b4-11eb-9290-d062962f9759.png)
- Terminology:
- ![image](https://user-images.githubusercontent.com/68700599/117920640-d86fe000-b2b4-11eb-82ae-0439bbfdc993.png)

### Section 2: Model Building in Python
- Why Python? = Jupyter + TensorFlow + Massive Data Libraries
- 실제 실기: Google Cloud Platform

### Section 3: Data Wrangling
- Pandas is a library in Python for data wrangling. 
- Most models use CSVs or another tabular data structure like a SQL table as their data for modeling. 
- Numpy is a numerical processing library in Python. 
- NaN means not a number. 
- A **series** is a one dimensional object similar to an array. 
- A **dataframe** is a tabular data structure composed of rows and columns. 

### Section 4: Machine Learning Algorithms
- Linear Regression:
- ![image](https://user-images.githubusercontent.com/68700599/117921705-d149d180-b2b6-11eb-9d36-0cd991ca1b16.png)
- Naive Bayes:
- email spam or not (using previous data) & combine the results (Free랑 Act Now 둘 다 합치면 완전 스팸 가능성 업업)
- ![image](https://user-images.githubusercontent.com/68700599/117921820-06562400-b2b7-11eb-86f1-ac594fd3b5fb.png)
- Decision Tree:
- ![image](https://user-images.githubusercontent.com/68700599/117921933-3bfb0d00-b2b7-11eb-96eb-9a0750c3e1dd.png)
- Logistic Regression:
- ![image](https://user-images.githubusercontent.com/68700599/117922026-65b43400-b2b7-11eb-93d9-82b6f576cc20.png)
- Linear VS Logistic (ref: https://www.javatpoint.com/linear-regression-vs-logistic-regression-in-machine-learning)
- ![image](https://user-images.githubusercontent.com/68700599/117922082-87152000-b2b7-11eb-8f70-2d52d1480b84.png)
- Neural Networks:
- ![image](https://user-images.githubusercontent.com/68700599/117922250-c8a5cb00-b2b7-11eb-9033-faa15dba89ad.png)
- ![image](https://user-images.githubusercontent.com/68700599/117922207-bc217280-b2b7-11eb-86a6-0230be0edcee.png)
- Support Vector Machine (SVM):
- 오렌지색은 너무 아슬아슬하고 블루가 딱 적당하게 그어짐!
- ![image](https://user-images.githubusercontent.com/68700599/117922327-e5420300-b2b7-11eb-892d-2de6678266d2.png)
- 그럼 어떻게 블루라인을 찾냐? 일단 (1) 너무 먼 애들은 빠이해줌 (2) 남은 애들을 linear optimization이란 테크닉을 써서 라인하고 최대한 멀리(!) 떨어뜰임 (왜냠 가까우면 너무 아슬해서 선 넘어갈 수 있으니까)
- ![image](https://user-images.githubusercontent.com/68700599/117922435-13274780-b2b8-11eb-8520-39880212f3cf.png)
- K-Means Clustering
- 빨간 동그라미가 타코 좋아하는 곳이라면, 내가 열어야 할 타코 집은? (물론 눈으로 하트가 있는 부분이라고 알지만, 컴퓨터는 어떻게 할까?)
- ![image](https://user-images.githubusercontent.com/68700599/117922850-b24c3f00-b2b8-11eb-8e4b-059c95f282b5.png)
- 먼저 랜덤하게 위치를 고름. 그 다음 가장 가까운 곳을 색깔로 표시함.
- ![image](https://user-images.githubusercontent.com/68700599/117922956-df98ed00-b2b8-11eb-822f-26f8c4e0b16e.png)
- 근데 가까운 곳 색깔로 표시한 곳 중간에 위치함 더 좋잖아?
- ![image](https://user-images.githubusercontent.com/68700599/117923036-0820e700-b2b9-11eb-85e5-edfa212628c2.png)
- 어? 근데 움직이고 보니 블루포인트 어차피 필요없네.. ㅃㅇ
- ![image](https://user-images.githubusercontent.com/68700599/117923080-15d66c80-b2b9-11eb-8b0d-241e24db1593.png)
- 이제 다시 센터로 옮기고... 한 번 봄
- ![image](https://user-images.githubusercontent.com/68700599/117923126-22f35b80-b2b9-11eb-9369-6840e8139452.png)
- 가장 optimal solution이 나올 떄까지 반복

### Section 5: Building a Single Perception Model
- (1) 먼저 random weight이랑 bias를 고름
- (2) Process input
- (3) Adjust weight

### Section 6: Neural Networks in Under Ten Minutes
- Backpropagation: 내가 알게 된 사실을 가지고 다시 시작하는 거. 
- Layers: 
- ![image](https://user-images.githubusercontent.com/68700599/118146184-f7b15f00-b3d3-11eb-8e3f-8ef3965f2618.png)
- Batching: 
- ![image](https://user-images.githubusercontent.com/68700599/118146524-4fe86100-b3d4-11eb-985d-0f1573db875e.png)

### Section 7: Gradient Descent
- Gradient Descent:
- ![image](https://user-images.githubusercontent.com/68700599/118146911-aeadda80-b3d4-11eb-9688-25e38770e933.png)
- stopping point = convergence (where 4 is)
- Overfitting: too accurate
- Regularization = 가장 괜찮은 line 찾는 법 (overfitting 없이)
- Cross-validation = 여러개 데이터 사용해서 우리가 overfitting한 거 고침
- Bias-Variance Tradeoff = training data랑 test data랑 accuracy 비교하는 것
- Feature Engineering = 데이터를 쪼은 것만 픽해서 가장 괜찮은 모델 만들려는 것
- ![image](https://user-images.githubusercontent.com/68700599/118147448-33005d80-b3d5-11eb-8b0a-3056d19c0bea.png)


