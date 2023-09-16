# Cost-of-groceries
# cook your dish here
store=int(input())
for s in range(store):
  n,x=map(int,input().split())
  a=list(map(int,input().split()))
  b=list(map(int,input().split()))
  c=0
  for d in range(n):
    if a[d]>=x: c+=b[d]
  print(c)
