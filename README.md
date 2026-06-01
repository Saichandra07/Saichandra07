<div align="center">

<!-- BANNER -->
<img src="./assets/banner-top.svg" width="100%"/>

<!-- NAME -->
# Hi, I'm Saichandra 👋

<!-- TYPING ANIMATION -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1000&color=E63946&center=true&vCenter=true&width=580&lines=Full-Stack+Developer;Java+%C2%B7+Spring+Boot+%C2%B7+React;WebSocket+%C2%B7+PWA+%C2%B7+Gemini+AI;Shipped+to+production" alt="Typing SVG" />

<!-- CONTACT BADGES -->
<br/>
<a href="https://www.linkedin.com/in/saichandra-thatikonda/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:thatikondasaichandra@gmail.com">
  <img src="https://img.shields.io/badge/Email-E63946?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://pitstop-silk.vercel.app">
  <img src="https://img.shields.io/badge/Live%20Demo-FFB700?style=for-the-badge&logo=vercel&logoColor=black"/>
</a>

</div>

---

## 🚗 Featured Project — PitStop

> **On-demand roadside mechanic. Like Swiggy for car breakdowns.**
> A user hits SOS → nearby mechanics are notified in real time → one accepts → both track the job on a live map. Three roles (User, Mechanic, Admin), full auth, AI job briefings, and Web Push that wakes a locked phone screen.

<div align="center">
  <a href="https://pitstop-silk.vercel.app">
    <img src="https://raw.githubusercontent.com/Saichandra07/pitstop/main/docs/demo.gif" alt="PitStop Demo" width="780"/>
  </a>
</div>

<br/>

**What makes it non-trivial:**

- **Cascading broadcast rings** — SOS triggers `@Scheduled` escalation across 0→2, 2→5, 5→10, 10→20 km rings using Haversine distance. No mechanic gets missed; no spam storm on day one.
- **Race-free WebSocket push** — job update events are published inside `afterCommit()`, so a connected client can never receive a job ID before the row is readable in the DB.
- **Web Push that wakes a locked screen** — VAPID push sent with `Urgency: HIGH` + `requireInteraction: true`; a mechanic's phone lights up even when the app is closed.

**Stack:** `Spring Boot 3` · `Spring Security / JWT` · `PostgreSQL` · `React 18 + Vite` · `WebSocket / STOMP` · `Gemini 2.5 Flash` · `Web Push (VAPID)` · `Cloudinary` · `PWA`

<div align="center">

<a href="https://pitstop-silk.vercel.app">
  <img src="https://img.shields.io/badge/Live%20App-pitstop--silk.vercel.app-FFB700?style=for-the-badge&logo=vercel&logoColor=black"/>
</a>
&nbsp;
<a href="https://github.com/Saichandra07/pitstop">
  <img src="https://img.shields.io/badge/View%20Repo-Saichandra07%2Fpitstop-E63946?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

## 🛠 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,postgres,react,js,vite,css,git,github,vercel&theme=dark" />

<br/>
<sub>Deployed on <strong>Render</strong> (backend) · <strong>Vercel</strong> (frontend) · <strong>Neon PostgreSQL</strong> (cloud DB)</sub>

</div>

---

## 📊 GitHub Stats

<div align="center">

<table>
<tr>
<td>
<img src="https://github-readme-stats.vercel.app/api?username=Saichandra07&show_icons=true&count_private=true&bg_color=0A0A0F&title_color=E63946&icon_color=FFB700&text_color=F0F0F0&border_color=2A2A3A&hide_border=false" alt="GitHub Stats"/>
</td>
<td>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Saichandra07&layout=compact&count_private=true&bg_color=0A0A0F&title_color=E63946&text_color=F0F0F0&border_color=2A2A3A" alt="Top Languages"/>
</td>
</tr>
</table>

</div>

---

## 👤 About Me

- 🔨 I build full-stack systems end to end — Spring Boot REST APIs, React frontends, shipped to production
- 📚 Currently strengthening DSA foundations and studying system design patterns
- 🎯 Open to **backend** or **full-stack** roles

---

<div align="center">
<img src="./assets/banner-bottom.svg" width="100%"/>
</div>
