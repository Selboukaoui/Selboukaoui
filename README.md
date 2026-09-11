<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:2c5364,100:00c6ff&height=230&section=header&text=SAMIR%20ELBOUKAOUI&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Systems%20%E2%86%94%20Web%2C%20I%20build%20both%20sides%20of%20the%20stack&descSize=17&descAlignY=55" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=00C6FF&center=true&vCenter=true&width=800&lines=kernel+syscalls+by+day%2C+React+components+by+night;C+%2F+C%2B%2B+%C2%B7+TypeScript+%C2%B7+Node.js+%C2%B7+Next.js;Linux+%C2%B7+Docker+%C2%B7+NGINX+%C2%B7+PostgreSQL;42+Networks+%C2%B7+open+to+PFE+%2F+internship+roles" alt="Typing SVG"/>

<br>

<a href="https://github.com/Selboukaoui"><img src="https://img.shields.io/badge/GitHub-Selboukaoui-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/samirelboukaoui/"><img src="https://img.shields.io/badge/LinkedIn-Samir%20Elboukaoui-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:samirelboukaouidev@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="#"><img src="https://img.shields.io/badge/Open%20to-PFE%20%2F%20Internship-2ea44f?style=for-the-badge&logo=target&logoColor=white"/></a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Selboukaoui&label=PROFILE+VIEWS&color=0072ff&style=for-the-badge" />

</div>

---

## whoami

<table>
<tr>
<td width="60%" valign="top">

```
$ whoami
Samir Elboukaoui, Software & DevOps Engineering student
42 Networks 

$ cat interests.txt
> OS internals: processes, signals, syscalls
> Networking: sockets, protocols, IRC-scale servers
> Full-stack web: React/Next.js down to the REST API
> Infrastructure: Docker, NGINX, reverse proxies, CI/CD
> Automation & AI-assisted tooling

$ status --current
Building MenaCode (competitive-programming platform, live team project)
Finishing 42 Networks common core, chasing a PFE internship
```

I like living at the boundary: close enough to the OS to catch a signal
by hand, comfortable enough on the web to ship the product on top of it.
Most of what's below was built to prove that to myself first, and to
recruiters second.

</td>
<td width="40%" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300"/>

</td>
</tr>
</table>

---

<div align="center">

## Stack

**Languages**
<br>
<img src="https://skillicons.dev/icons?i=c,cpp,js,ts,python,bash" />

**Frontend**
<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css" />

**Backend**
<br>
<img src="https://skillicons.dev/icons?i=nodejs,express" />

**Data**
<br>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,prisma" />

**Infra & Tools**
<br>
<img src="https://skillicons.dev/icons?i=linux,docker,nginx,git,github,vscode,grafana,kubernetes" />

</div>

---

## Featured builds

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🏆 MenaCode
*Full-stack competitive-programming platform, team of 4, in progress*

<p>
<img src="https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Socket.IO-black?style=flat-square&logo=socket.io"/>
</p>

A judge-style platform where users solve problems, run contests, and climb
a rating ladder. My part spans the stack:

- Custom OAuth 2.0 (Authorization Code Flow) for Google and 42 Intra, provider-agnostic, plus JWT/httpOnly-cookie sessions and a hashed-token reset flow
- Real-time chat and presence built on Socket.IO (`Map<userId, Set<socketId>>` for multi-tab support), debugged through disconnect races and StrictMode double-invokes
- Contest-rating charts, a GitHub-style submission heatmap, and server-side paginated submission lists (Express + Prisma)
- Prisma/PostgreSQL schema work on Supabase, cascade deletes, migration-conflict cleanup, and a full seed script
- Husky + commitlint + ESLint/Prettier pipeline; shipped a Next.js production build to Render

<sub>🔒 Private team repository</sub>

</td>
<td width="50%" valign="top">

### 🐳 Inception
*Containerized web infrastructure, built from scratch*

<p>
<img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white"/>
<img src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white"/>
<img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"/>
</p>

- NGINX terminating TLS in front of WordPress, MariaDB, and Redis, each in its own container
- Docker's internal DNS used for service-to-service resolution and port routing, no host-network shortcuts
- Everything reproducible from a single `docker compose up`, no images pulled pre-built

[🔗 Repo](https://github.com/Selboukaoui/Inception)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌐 ft_irc
*An IRC server, from the RFC up, in C++98*

<p>
<img src="https://img.shields.io/badge/C%2B%2B98-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/poll()-non--blocking%20I%2FO-informational?style=flat-square"/>
</p>

- Single-threaded server built around `poll()`, handling many concurrent clients on non-blocking sockets
- Full core command set: `PASS`, `NICK`, `USER`, `JOIN`, `PART`, `KICK`, `INVITE`, `TOPIC`, `MODE`, `PRIVMSG`, `QUIT`, plus DCC support
- Reviewed for spec compliance against modern IRC documentation, not just "works with my own client"

[🔗 Repo](https://github.com/Selboukaoui/IRC)

</td>
<td width="50%" valign="top">

### 🎮 cub3d
*A raycasting engine, Wolfenstein-3D style, in C*

<p>
<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/MinilibX-Graphics-blueviolet?style=flat-square"/>
</p>

- First-person raycasting renderer, textured walls, sprites, and a minimap, driven by a custom map-parsing config format
- Manual memory management throughout, no leaks tolerated on AddressSanitizer

[🔗 Repo](https://github.com/Selboukaoui/CUB3D-1337-42)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐚 minishell
*A POSIX-ish shell, from scratch*

<p>
<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

- Custom lexer/parser for pipes, redirections, quoting, and built-ins
- Command execution via `fork`/`execve`, plus proper signal handling (`SIGINT`, `SIGQUIT`) matching real shell behavior

[🔗 Repo](https://github.com/Selboukaoui/minishell)

</td>
<td width="50%" valign="top">

### 🧱 42 Networks common core
*The projects that built the foundation*

Algorithms, memory management, OOP and templates in C++, process/socket
programming, and more, one project per core CS concept.

<details>
<summary><b>Browse the vault</b></summary>
<br>

- [`push_swap`](https://github.com/Selboukaoui/push_swap): sorting algorithm under a move-count constraint
- [`philosopher`](https://github.com/Selboukaoui/philosopher): dining philosophers, threads/mutexes
- [`so_long`](https://github.com/Selboukaoui/so_long): 2D game engine basics
- [`minitalk`](https://github.com/Selboukaoui/minitalk): inter-process communication over UNIX signals
- [`LIBFT`](https://github.com/Selboukaoui/LIBFT): a libc reimplementation, the foundation everything else is built on
- [`CPP05`-`CPP09`](https://github.com/Selboukaoui/CPP09): exceptions, polymorphism, STL containers, templates

</details>

</td>
</tr>
</table>

---

<div align="center">

## Analytics

<img src="https://github-readme-stats.vercel.app/api?username=Selboukaoui&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Selboukaoui&layout=compact&theme=tokyonight&hide_border=true" width="49%" />

<br><br>

<img src="https://streak-stats.demolab.com?user=Selboukaoui&theme=tokyonight&hide_border=true&background=0D1117" />

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Selboukaoui/Selboukaoui/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Selboukaoui/Selboukaoui/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/Selboukaoui/Selboukaoui/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake" width="100%" />
</picture>

</div>

---

<div align="center">

## Right now

<table>
<tr>
<td align="center">🎯<br><b>Hunting a PFE internship</b><br><sub> remote-friendly</sub></td>
<td align="center">🛠️<br><b>Shipping MenaCode</b><br><sub>real-time features, auth</sub></td>
<td align="center">📚<br><b>Studying CS</b><br><sub>University of the People</sub></td>
<td align="center">🤖<br><b>Exploring AI-assisted tooling</b><br><sub>small automation utilities</sub></td>
</tr>
</table>

</div>

---

<div align="center">

## Let's talk

If you're hiring for a DevOps, backend, or full-stack internship, or just
want to talk about shells, sockets, or shipping side projects, my inbox
is open.

<a href="https://www.linkedin.com/in/samirelboukaoui/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:samirelboukaouidev@gmail.com"><img src="https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br><br>

<i>Build. Break. Learn. Improve.</i>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,50:2c5364,100:0f2027&height=120&section=footer"/>

</div>
