# -Array-with-Odd-Sum
```python
t=int(input())
for count in range(t):
    n=int(input())
    a=list(map(int,input().split()))
    sum=0
    check=0
    checkk=0
    for i in range(n):
          sum+=a[i]
          if a[i]%2==0:
              check=1
          else:
              checkk=1
    if sum%2!=0:
        print("YES")
    elif check==0:
        print("NO")
    elif checkk==0:
        print("NO")       
    else:
        print("YES")
```
