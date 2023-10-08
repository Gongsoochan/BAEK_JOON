# BAEKJOON

2023.10.05

입출력과 사칙연산

1_2557. Hello World!
print('Hello World!')

2_1000. A+B
a,b=map(int,input().split())
print(a+b)

3_1001.A-B
a,b=map(int,input().split())
print(a-b)

2023.10.06

4_10998. AXB
a,b=map(int,input().split(' '))
print(a*b)

5_1008. A/B
a,b=map(int,input().split())
print(a/b)

6_10869. 사칙연산
a,b=map(int,input().split())
print(int(a+b))
print(int(a-b))
print(int(a*b))
print(int(a/b))
print(int(a%b))

2023.10.07

7_10926. ??!
준하는 사이트에 회원가입을 하다가 joonas라는 아이디가 이미 존재하는 것을 보고 놀랐다. 준하는 놀람을 ??!로 표현한다. 준하가 가입하려고 하는 사이트에 이미 존재하는 아이디가 주어졌을 때, 놀람을 표현하는 프로그램을 작성하시오.
id=input()
print(id,'??!',sep='')

8_18108. 1998년생인 내가 태국에서는 2541년생?!
ICPC Bangkok Regional에 참가하기 위해 수완나품 국제공항에 막 도착한 팀 레드시프트 일행은 눈을 믿을 수 없었다. 공항의 대형 스크린에 올해가 2562년이라고 적혀 있던 것이었다.
불교 국가인 태국은 불멸기원(佛滅紀元), 즉 석가모니가 열반한 해를 기준으로 연도를 세는 불기를 사용한다. 반면, 우리나라는 서기 연도를 사용하고 있다. 불기 연도가 주어질 때 이를 서기 연도로 바꿔 주는 프로그램을 작성하시오.
y=int(input())
1000<=y<=3000
print(y-543)

9_10430. 나머지
(A+B)%C는 ((A%C) + (B%C))%C 와 같을까?
(A×B)%C는 ((A%C) × (B%C))%C 와 같을까?
세 수 A, B, C가 주어졌을 때, 위의 네 가지 값을 구하는 프로그램을 작성하시오.
A,B,C=map(int,input().split())
print((A+B)%C)
print(((A%C)+(B%C))%C)
print((A*B)%C)
print(((A%C)*(B%C))%C)

10_2588. 곱셈
(세 자리 수) × (세 자리 수)는 다음과 같은 과정을 통하여 이루어진다.
![image](https://github.com/Gongsoochan/BAEKJOON/assets/140775642/82f84326-9519-40ea-af5f-8d3307e652f8)
(1)과 (2)위치에 들어갈 세 자리 자연수가 주어질 때 (3), (4), (5), (6)위치에 들어갈 값을 구하는 프로그램을 작성하시오.
a=int(input())
b=int(input())
b1=int(str(b)[-1])
b2=(int(str(b)[-2]))*10
b3=(int(str(b)[-3]))*100
c=a*b1
d=a*b2
e=a*b3
f=c+d+e
print(c)
print(int(d/10))
print(int(e/100))
print(f)

11_11382. 꼬마 정민
꼬마 정민이는 이제 A + B 정도는 쉽게 계산할 수 있다. 이제 A + B + C를 계산할 차례이다!
a,b,c=map(int,input().split())
answer=a+b+c
print(answer)

23.10.08

12_10171. 고양이
print('\\    /\\')
print(" )  ( ')")
print('(  /  )')
print(' \(__)|')

13_10172. 개
print('|\_/|')
print('|q p|   /}')
print('( 0 )"""\\')
print('|"^"`    |')
print('||_/=\\\__|')

조건문

1_1330. 두 수 비교하기
두 정수 A와 B가 주어졌을 때, A와 B를 비교하는 프로그램을 작성하시오.
a,b=map(int,input().split(' '))
-10000<=a,b<=10000
if a>b:
    print('>')
elif a<b:
    print('<')
elif a==b:
    print('==')

2_9498. 시험 성적
시험 점수를 입력받아 90 ~ 100점은 A, 80 ~ 89점은 B, 70 ~ 79점은 C, 60 ~ 69점은 D, 나머지 점수는 F를 출력하는 프로그램을 작성하시오.
score=int(input())
if 60<=score<=69:
    print('D')
elif 70<=score<=79:
    print('C')
elif 80<=score<=89:
    print('B')
elif 90<=score<=100:
    print('A')
else:
    print('F')

3_2753. 윤년
연도가 주어졌을 때, 윤년이면 1, 아니면 0을 출력하는 프로그램을 작성하시오.
윤년은 연도가 4의 배수이면서, 100의 배수가 아닐 때 또는 400의 배수일 때이다.
예를 들어, 2012년은 4의 배수이면서 100의 배수가 아니라서 윤년이다. 1900년은 100의 배수이고 400의 배수는 아니기 때문에 윤년이 아니다. 하지만, 2000년은 400의 배수이기 때문에 윤년이다.
year=int(input())
1<=year<=4000
if year%4==0 and (year%100!=0 or year%400==0):
    print(1)
else:
    print(0)








