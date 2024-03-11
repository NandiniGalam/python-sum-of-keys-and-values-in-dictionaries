# python-sum-of-keys-and-values-in-dictionaries
#sum of dictionary
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res=0 
for i in d:
  res=res+i  + d[i]
print(res)


#next approach
#using built in method(.) and buit in function(sum)
d={}
n=int(input())
for i in range(n):
  k,v=map(int,input().split())
  d[k]=v 
res1=d.values()
res2=d.keys()
print(sum(res1)+sum(res2))

