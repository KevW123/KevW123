- 👋 Hi, I’m @KevW123
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
KevW123/KevW123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
version: "3"
services:
  web:
    build: .
    command: python redditweb.py
    ports:
      - "5000:5000"
