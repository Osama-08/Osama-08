<!-- GIF Banner -->
<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" />
</p>

<!-- Animated Typing Header -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=25&center=true&vCenter=true&width=550&lines=Hi+I'm+Muhammad+Osama+Abbasi!;Full+Stack+Developer;MERN+%7C+Nextjs+%7C+APIs+%7C+Cloud;Clean+Code+%26+Modern+Web+Apps" />
</p>

---

# 👨‍💻 About Me  
I’m a passionate **Full Stack Developer** with **3+ years of experience** in building scalable and modern web applications using the **MERN stack**, **Nextjs**, and cloud technologies. I focus on creating clean, maintainable, and performance-optimized solutions that help businesses grow.

---

# 🚀 Tech Stack  

### **Frontend**
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Nextjs-black?logo=next.js)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/-TailwindCSS-06B6D4?logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white)

### **Backend**
![Node](https://img.shields.io/badge/-Node-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20APIs-FF6C37?logo=fastapi&logoColor=white)

### **Database**
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/-Mongoose-880000)

### **Tools**
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?logo=postman)
![VS Code](https://img.shields.io/badge/-VSCode-007ACC?logo=visual-studio-code)

---

# 📌 Featured Projects  
✨ **DevLadder — Learning Platform**  
✨ **E-Commerce Web App (MERN)**  
✨ **Nimbus — Media SaaS Platform**  
✨ **StackOverflow Clone**  

---

# 📊 GitHub Stats  

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Osama-08&show_icons=true&theme=tokyonight" />
  <img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=Osama-08&theme=tokyonight" />
</p>

<p align="center">
  <img height="190" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Osama-08&layout=compact&theme=tokyonight" />
</p>

---

# 🐍 Snake Animation (Auto-Generated Contribution Snake)

<p align="center">
  <img src="https://raw.githubusercontent.com/Osama-08/Osama-08/output/snake.svg" alt="snake animation" />
</p>

**Setup Required:**  
Create a repo named **Osama-08** (your username) → enable GitHub Actions → add this workflow:

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Osama-08
          outputs: dist/snake.svg

      - name: Push snake to output branch
        uses: actions/upload-artifact@v3
        with:
          name: snake
          path: dist/snake.svg
