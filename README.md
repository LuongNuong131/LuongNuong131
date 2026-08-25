<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:09090b,45:312e81,75:7c3aed,100:f5b97a&height=230&section=header&text=LuNu&fontSize=78&fontColor=ffffff&fontAlignY=36&desc=Designing%20useful%20digital%20worlds&descAlignY=59&descSize=18" alt="LuNu profile header" width="100%" />

  <h1>Hi, I'm Trần Quang Lương</h1>
  <p><strong>LuNu</strong> · Developer from Vietnam · Product-minded software builder</p>
  <p>
    <a href="https://github.com/LuongNuong131"><img src="https://img.shields.io/badge/GitHub-LuongNuong131-18181b?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" /></a>
    <a href="https://github.com/LuongNuong131?tab=repositories"><img src="https://img.shields.io/badge/Explore%20projects-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Explore projects" /></a>
    <img src="https://komarev.com/ghpvc/?username=LuongNuong131&style=for-the-badge&color=f5b97a&label=PROFILE+VIEWS" alt="Profile views" />
  </p>
</div>

## The short version

I build software where **interfaces, systems and real-world use cases meet**. My work moves between product design, frontend experiences, backend services, databases, authentication, media workflows and the small details that make an application feel intentional.

I learn by shipping. Some projects are experiments, some are practical tools, and some grow into connected products with multiple services behind them. Across all of them, I care about the same things: a clear user journey, a dependable foundation and an experience that feels more complete than a simple prototype.

> **My approach:** turn an idea into something people can open, understand and actually use.

<p align="center">
  <a href="#featured-work">Featured work</a> ·
  <a href="#how-i-build">How I build</a> ·
  <a href="#technology">Technology</a> ·
  <a href="#connect">Connect</a>
</p>

## Featured work

### EchoMMO — a connected game ecosystem

<a href="https://github.com/LuongNuong131/EchoMMO"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,17,20&height=125&section=header&text=EchoMMO&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=55" alt="EchoMMO" width="100%" /></a>

**EchoMMO** is the project that best represents my interest in building a complete digital world rather than an isolated screen. It explores how a Vue frontend, Java backend, relational data, authentication, game mechanics, social systems and real-time communication can become one coherent product.

| Product layer | What it explores |
|---|---|
| **Identity** | Registration, login, roles, profiles, account security and recovery flows. |
| **Game systems** | Characters, combat, PvP, exploration, gathering, equipment, quests and progression. |
| **Economy** | Inventory, items, wallets, shops, gift codes and marketplace workflows. |
| **Community** | Friends, private messages, chat, notifications, reports and leaderboards. |
| **Operations** | Administration, moderation, configuration and data-oriented tooling. |

The project is organized as a connected family of repositories so that the product can be understood from interface to persistence:

| Repository | Responsibility |
|---|---|
| [EchoMMO](https://github.com/LuongNuong131/EchoMMO) | Original application shell and early product experience. |
| [EchoMMO-Frontend](https://github.com/LuongNuong131/EchoMMO-Frontend) | Vue interface, Pinia state, routing, localization and game views. |
| [EchoMMO-Backend](https://github.com/LuongNuong131/EchoMMO-Backend) | Java 17, Spring Boot, REST, JPA, JWT, validation, email and WebSocket configuration. |
| [EchoMMO-DB](https://github.com/LuongNuong131/EchoMMO-DB) | MySQL schema and seed data for the game world. |

> **Why it matters:** EchoMMO is where domain modeling, product design, security, persistence, game mechanics and community features come together in one long-running experiment.

### LuNu Music — a personal listening room

<a href="https://github.com/LuongNuong131/LuNu_Music"><img src="https://img.shields.io/badge/LuNu%20Music-Premium%20music%20library-f5b97a?style=for-the-badge&logo=musicbrainz&logoColor=171717" alt="LuNu Music" /></a>

**LuNu Music** is a fullstack music library designed as a private listening room. It combines a Vue 3/Vite interface with a FastAPI backend, Supabase data, Cloudinary media delivery, Render deployment and Vercel hosting.

The product includes a global player, queue, Now Playing view, personal playlists, Lyrics Lab, plain-text lyrics workflows, Personal Rotation, admin media management, member proposals, notifications and **LuNu Cinema / Tea Room** for authorized video content. Its visual language is built around Midnight Vinyl: dark surfaces, warm amber accents, glass panels and responsive layouts that remain usable from desktop to mobile.

| System | Implementation |
|---|---|
| **Frontend** | Vue 3, Vite, Vue Router, composables and a responsive design system. |
| **Backend** | FastAPI, signed LuNu sessions, media jobs and server-side integrations. |
| **Data** | Supabase Postgres for users, songs, Cinema, proposals and notifications. |
| **Media** | Cloudinary delivery with yt-dlp and FFmpeg processing for authorized content. |
| **Deployment** | Vercel frontend and Render Docker backend. |

[Open the LuNu Music repository →](https://github.com/LuongNuong131/LuNu_Music)

## Selected work

| Project | What it represents | Main technologies |
|---|---|---|
| [LuNu Messenger](https://github.com/LuongNuong131/LuNu-Messenger) | A focused communication product exploring conversations and application flow. | Vue |
| [CRM Nội Bộ](https://github.com/LuongNuong131/CRM_NoiBo) | An internal-management system centered on structured data and practical workflows. | Vue |
| [Thanh Luan Mobile](https://github.com/LuongNuong131/Thanh-Luan-Mobile-Frontend) · [Backend](https://github.com/LuongNuong131/Thanh-Luan-Mobile-Backend) | A mobile-oriented product line with a dedicated backend service. | Vue · Java |
| [LuNu Tool VN](https://github.com/LuongNuong131/LuNu_Tool_VN) | Python tooling for practical experiments and automation. | Python |
| [FCDBB](https://github.com/LuongNuong131/FCDBB) · [LuNu_FCDBB](https://github.com/LuongNuong131/LuNu_FCDBB) | A continuing Vue product line shaped through iterative development. | Vue |

## How I build

I prefer projects with enough depth to reveal the relationship between product decisions and engineering decisions. A polished interface is valuable, but it becomes much more meaningful when the underlying data model, permission boundary, error state and deployment path have been considered as well.

| Principle | What it means in practice |
|---|---|
| **Start from the user journey** | Define what someone is trying to accomplish before adding screens or abstractions. |
| **Build the vertical slice** | Connect interface, API, persistence and feedback early so the product can be tested as a whole. |
| **Make state visible** | Loading, empty, error, success and permission states should be understandable instead of silent. |
| **Design for the real device** | Desktop, tablet and mobile are different interaction contexts, not only different widths. |
| **Keep the system honest** | Document limitations, protect credentials and avoid promising behavior the infrastructure cannot support. |
| **Improve through iteration** | Treat every bug report and awkward interaction as evidence for the next refinement. |

## Technology

<div align="center">
  <img src="https://skillicons.dev/icons?i=vue,vite,javascript,html,css,python,fastapi,java,spring,mysql,postgres,supabase,docker,git,github,vercel&perline=9" alt="Technologies used by LuNu" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-Vue%203%20%7C%20Vite%20%7C%20JavaScript-41B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Frontend stack" />
  <img src="https://img.shields.io/badge/Backend-Python%20%7C%20FastAPI%20%7C%20Java%20%7C%20Spring-009688?style=flat-square&logo=fastapi&logoColor=white" alt="Backend stack" />
  <img src="https://img.shields.io/badge/Data-Postgres%20%7C%20Supabase%20%7C%20MySQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="Data stack" />
  <img src="https://img.shields.io/badge/Delivery-Vercel%20%7C%20Render%20%7C%20Docker-111827?style=flat-square&logo=docker&logoColor=white" alt="Delivery stack" />
</p>

| Area | Tools I work with |
|---|---|
| **Product interfaces** | Vue 3, Vue Router, JavaScript, HTML, CSS, responsive design and interaction systems. |
| **Services** | Python, FastAPI, Java, Spring Boot, REST APIs, authentication and validation. |
| **Persistence** | PostgreSQL, Supabase, MySQL, schema design and data workflows. |
| **Media and runtime** | Cloudinary, FFmpeg, yt-dlp, Node.js, Docker and server-side processing. |
| **Workflow** | Git, GitHub, Vercel, Render, VS Code and iterative product documentation. |

## GitHub activity

<div align="center">
  <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=LuongNuong131&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" height="175" alt="LuNu's GitHub statistics" />
  <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=LuongNuong131&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="175" alt="LuNu's most used languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=LuongNuong131&theme=tokyonight&hide_border=true" alt="LuNu's GitHub contribution streak" />
</div>

## Currently building

I am continuing to evolve **LuNu Music** as a real product rather than a static demo: improving the media lifecycle, making long-running jobs safer, refining moderation and notifications, and keeping the listening experience calm and responsive. In parallel, I continue exploring larger systems through EchoMMO and smaller tools that help turn ideas into working software faster.

## Beyond the code

I enjoy the space between engineering and expression. A game world, a music room, a messenger, an internal tool and a small utility may look unrelated on the surface, but each one asks the same question: **can an idea become a place someone can meaningfully interact with?**

That is the kind of work I want to keep doing — useful enough to matter, thoughtful enough to feel personal and technically strong enough to grow.

## Connect

<div align="center">
  <p><strong>Thanks for visiting my profile.</strong></p>
  <p>Explore the repositories, follow the experiments and connect if you want to build something meaningful.</p>
  <a href="https://github.com/LuongNuong131?tab=repositories"><img src="https://img.shields.io/badge/Explore%20all%20projects-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Explore all projects" /></a>
</div>

<br />

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f5b97a,45:7c3aed,75:312e81,100:09090b&height=110&section=footer" alt="LuNu profile footer" width="100%" />
</div>

<!--
  Profile README for github.com/LuongNuong131
  Designed as a compact portfolio: clear identity, selected work and a visible engineering philosophy.
-->
