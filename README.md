from textwrap import dedent
import pypandoc

md = dedent(r"""
<p align="center">
  <img src="./banner.png" alt="Naveed Umar Banner" width="100%">
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=26&pause=1200&color=3B82F6&center=true&vCenter=true&width=850&lines=Software+Engineer;React+%7C+Next.js+%7C+Flutter+Developer;Building+AI-Powered+Digital+Products;Open+to+Junior+Remote+Opportunities"/>
</p>

<h1 align="center">Hi 👋, I'm Naveed Umar</h1>

<h3 align="center">
Software Engineer passionate about building modern web applications, cross-platform mobile apps and AI-powered digital products.
</h3>

<p align="center">
<a href="https://naveedumar.com"><img src="https://img.shields.io/badge/Portfolio-Visit_Website-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/naveed-umar-565abb27a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:naveedumar559@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

# 👨‍💻 About Me

I'm currently completing my Bachelor's in Software Engineering while building production-ready applications and working on real client projects.

- 🎓 Software Engineering Student (Final Year)
- 💼 Software Engineer at **BeyByte**
- 🌍 Open to Junior Remote Software Engineering roles
- 🚀 Passionate about clean architecture, UI/UX and scalable products
- 🤖 Interested in AI-powered applications and automation

---

# ⚡ Tech Stack

### Languages
<p><img src="https://skillicons.dev/icons?i=js,ts,dart,html,css"/></p>

### Frontend
<p><img src="https://skillicons.dev/icons?i=react,nextjs,tailwind"/></p>

### Mobile
<p><img src="https://skillicons.dev/icons?i=flutter"/></p>

### Backend & Database
<p><img src="https://skillicons.dev/icons?i=nodejs,firebase"/></p>

### Tools
<p><img src="https://skillicons.dev/icons?i=git,github,vscode,figma,postman,vercel"/></p>

---

# 💼 Experience

## Software Engineer — BeyByte

- Built responsive business websites.
- Worked with real clients from discovery to delivery.
- Collaborated on UI/UX, frontend development and project planning.
- Focused on performance, accessibility and maintainability.

## Freelance Projects

Designed and developed modern business websites with a focus on branding, conversion and user experience.

---

# 🚀 Featured Projects

## 🌐 Personal Portfolio

Modern portfolio showcasing projects, skills and experience.

**Tech:** Next.js • Tailwind CSS • Framer Motion

🔗 https://naveedumar.com

---

## 🏥 Edina Eye Clinic

Healthcare website with premium UI/UX, appointment booking and responsive experience.

---

## 💼 BeyByte

Agency website showcasing services, portfolio and digital solutions.

---

## 📱 Fitnex

Flutter application featuring authentication, AI assistant integration and responsive mobile UI.

---

# 💻 What I'm Building

<table>
<tr>
<td width="50%">

### 🌐 Frontend

- React
- Next.js
- Tailwind CSS
- Responsive UI

</td>

<td width="50%">

### 📱 Mobile

- Flutter
- Firebase
- REST APIs
- Clean Architecture

</td>
</tr>

<tr>
<td>

### 🤖 AI

- Prompt Engineering
- AI Integrations
- Workflow Automation

</td>

<td>

### ☁ Deployment

- GitHub
- Vercel
- Firebase Hosting

</td>
</tr>
</table>

---

# 📈 Activity

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=naveed-umar&theme=github-dark&hide_border=true"/>
</p>

---

# 🎯 Currently Learning

- Advanced React Patterns
- Next.js App Router
- Flutter Clean Architecture
- Software System Design
- AI-powered Web Applications
- Cloud Deployment Workflows

---

# 🤝 Let's Connect

<p align="center">
<a href="https://naveedumar.com">🌐 Portfolio</a> •
<a href="https://www.linkedin.com/in/naveed-umar-565abb27a/">💼 LinkedIn</a> •
<a href="mailto:naveedumar559@gmail.com">📧 Email</a>
</p>

---

<p align="center">
<i>"Transforming ideas into modern digital products through thoughtful design and quality engineering."</i>
</p>

<p align="center">
⭐ Thanks for visiting my GitHub profile!
</p>
""")

# Save using pypandoc per instructions
pypandoc.convert_text(md, 'md', format='md', outputfile='/mnt/data/README.md', extra_args=['--standalone'])
print("saved")
