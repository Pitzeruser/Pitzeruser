- š Hi, Iām @Pitzeruser
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
Pitzeruser/Pitzeruser is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
while True:
    try:
        n=int(input())
        r=[]
        for i in range(n):
            r.append(int(input()))
        for i in sorted(set(r)):
            print(i)
    except:
        break
