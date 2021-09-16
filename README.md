- 👋 Hi, I’m @Pitzeruser
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Pitzeruser/Pitzeruser is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
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
