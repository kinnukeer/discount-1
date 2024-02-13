# discount-1
t=int(input())
for _ in range(t):
  a,b,c,d=map(int,input().split())
  a=a-c
  b=b-d
  if a>b:
    print("second")
  elif a<b:
    print("first")
  else:
    print("any")
  
