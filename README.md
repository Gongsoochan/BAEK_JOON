# BAEKJOON

2023.10.05

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
id=input()
print(id,'??!',sep='')

8_18108. 1998년생인 내가 태국에서는 2541년생?!
y=int(input())
1000<=y<=3000
print(y-543)

9_10430. 나머지
A,B,C=map(int,input().split())
print((A+B)%C)
print(((A%C)+(B%C))%C)
print((A*B)%C)
print(((A%C)*(B%C))%C)

10_2588. 곱셈
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
a,b,c=map(int,input().split())
answer=a+b+c
print(answer)

12_10171. 고양이


13_10172. 개


