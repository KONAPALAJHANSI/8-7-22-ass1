s=input()
p=""
for i in s:
    
    if i not in p:
       
        if i.isdigit():
            p=p+i
print(p)
k=list(input())
