l=[]
n=int(input("enter no.of elements"))
for i in range(n):
    x=int(input())
    l.append(x)
c=0
print(l)
res=[]
for i in l:
    if i not in res:
        res.append(i)       
c=c+1
print(res)
print(c)

o/p:
enter elements:4
1
2
1
4
[1,2,1,4]
[1,2,4]
1
