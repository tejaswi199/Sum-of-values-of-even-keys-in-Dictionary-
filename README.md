n=int(input())
d={}
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v
s=0
for j in d:
  if j%2 == 0:
    s=s+d[j]
print(s)
