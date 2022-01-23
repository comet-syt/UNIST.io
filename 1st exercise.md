1st exercise
=================
***************

#### 학습 목표
>제어문 중 하나인 if문에 대해 배운다.

### **1. Hello Python**    
가. condition : 조건문_참 거짓에 따라 달라지는 계산이나 상황을 수행하는 프로그래밍 언어의 특징   
나. syntax : 구문
다. indented : 들여쓰기

1. if문 알아보기
~~~ Python
number = float(input("Please enter a number:  "))
if number > 0:
    print('It is positive')
if number < 0:
    print('It is negative')
if number == 0:
    print('It is zero')
~~~
입력 : 10
결과 : It is positive.
<br/>
<br/>

2. else, elif 문 알아보기
~~~Python
number = float(input("Please enter a number:  "))
if number > 0:
    print('It is positive')
elif number < 0:
    print('It is negative')
else:
    print('It is zero')
~~~
입력 : 10
결과 : It is positive.
<br/>
<br/>
  
>### why elif, else

**1. Your code may be easier to read, as it's clearer that certain branches are being grouped together**   
**2. There may be a small efficiency gain (because the interpreter can skip some checks)**  
**3. It may allow you to simplify logic in some cases.**  


3. 마지막 연습
~~~Python
farenheit = float(input("Enter a temperature in Fahrenheit : "))
celsius = 5 / 9 * (farenheit - 32)
print(celsius)
if celsius > 28:
    print("Hot")
elif celsius > 15:
    print("Warm")
elif celsius > 0:
    print('Cool')
else:
    print('Cold')
~~~
