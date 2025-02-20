---
title: "복잡도"
excerpt: "복잡도에 관한 간단한 정리"

categories:
  -algorithm
tags:
  -algorithm

date: 2022-04-08
last_modified_at: 2022-04-08
---

## 복잡도

복잡도는  

+시간 복잡도: 알고리즘을 위해 필요한 연산의 횟수  
+공간 복잡도: 알고리즘을 위해 필요한 메모리의 양  

로 나타낸다.

***
## 시간 복잡도

시간 복잡도를 표현할 떄는 빅오(Big-O) 표기법을 사용한다.  

### 종류에는

|빅오 표기법|명칭|  
|:---|:---|  
|O(1)|상수 시간|  
|O(logN)|로그 시간|  
|O(N)|선형 시간|  
|O(NlogN)|로그 선형 시간|  
|O(N^2)|이차 시간|  
|O(N^3)|삼차 시간|  
|O(2^n)|지수 시간|  

등이 있다  

일반적으로 문제를 풀 때의 시간 제한이 1초인 문제에 대해  

+N의 500범위가 인 경우: 시간 복잡도가 O(N^3)인 알고리즘을 설계하면 문제를 풀 수 있다.  
+N의 2,000범위가 인 경우: 시간 복잡도가 O(N^2)인 알고리즘을 설계하면 문제를 풀 수 있다.  
+N의 100,000범위가 인 경우: 시간 복잡도가 O(NlogN)인 알고리즘을 설계하면 문제를 풀 수 있다.  
+N의 10,000,000범위가 인 경우: 시간 복잡도가 O(N)인 알고리즘을 설계하면 문제를 풀 수 있다.  

***
## 공간 복잡도

코딩 테스트 문제는 대부분 리스트(배열)을 사용해서 풀어야한다.  
대부분의 문제는 다수의 데이터에 대한 효율적인 처리를 요구하기 때문이다.  

코딩테스트에서는 보통 메모리 사용량을 128 ~ 512MB 정도로 제안  
일반적인 경우 데이터의 개수가 1,000만 단위가 넘어가지 않도록 알고리즘을 설계해야한다.  

