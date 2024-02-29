# find-the-best-discount-in-sales in python
# Approach-1
t=int(input())
for_in range(t):
  a,b,c,d=map(int,input().split())
  a=a-c
  b=b-d
  if a>b:
    print("second")
  elif a<b:
    print("First")
  else:
    print("Any")
    
# Approach-2
t=int(input())
for_in range(t):
  a,b,c,d=map(int,input().split())
  if (a-c)>(b-d):
    print("second")
  elif (a-c)<(b-d) :
    print("First")
  else:
    print("Any")
