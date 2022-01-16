- 👋 Hi, I’m @Sauravkumar1232
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Sauravkumar1232/Sauravkumar1232 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
n=int(input())
for i in range(1,n+1):
    for j in range(1,i):
        print(n-j+1,end="")
    for j in range(1,2*n):
        if i+1<=j<=2*n-i:
            print(n-i+1,end="")
    for j in range(i+1,1,-1):
        print(n-j+2,end="")
    print()
for i in range(1,n):
    for j in range(i,n):
        print(n-j+i,end="")
    for j in range(1,n+i):
        if n+1-i<=j<=n-1+i:
            print(i+1,end="")
    for j in range(i,n):
        print(j+1,end="")    
    print()    
