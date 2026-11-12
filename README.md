<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:080b12,32:16243a,62:312e81,82:7c3aed,100:f5b97a&height=250&section=header&text=LuNu&fontSize=82&fontColor=ffffff&fontAlignY=36&desc=Building%20useful%20digital%20worlds&descAlignY=60&descSize=18" alt="LuNu profile header" width="100%" />

  <h1>Hi, I'm Trần Quang Lương</h1>
  <p><strong>LuNu</strong> · Developer from Vietnam · Product-minded software builder</p>
  <p>
    <a href="https://github.com/LuongNuong131"><img src="https://img.shields.io/badge/GitHub-LuongNuong131-18181b?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" /></a>
    <a href="https://github.com/LuongNuong131?tab=repositories"><img src="https://img.shields.io/badge/Explore%20projects-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Explore projects" /></a>
    <img src="https://komarev.com/ghpvc/?username=LuongNuong131&style=for-the-badge&color=f5b97a&label=PROFILE+VIEWS" alt="Profile views" />
  </p>
</div>

> I build software where **interfaces, systems and real-world use cases meet** — from internal operations tools to private media rooms and connected game worlds.

<p align="center">
  <a href="#featured-work">Featured work</a> ·
  <a href="#how-i-build">How I build</a> ·
  <a href="#technology">Technology</a> ·
  <a href="#currently-building">Currently building</a>
</p>

## The short version

I like turning an idea into something people can open, understand and actually use. My work moves between product design, frontend experiences, backend services, databases, authentication, realtime collaboration, media workflows and the small details that make an application feel intentional.

I learn by shipping. Some projects begin as experiments, some become practical tools, and some grow into connected products with multiple services behind them. Across all of them, I care about the same things: a clear user journey, a dependable foundation and an experience that feels more complete than a simple prototype.

> **My approach:** make the product understandable first, make the system dependable second, then keep refining the details that make it feel alive.

## Featured work

### AF Booking — an operations workspace for booking teams

<a href="https://github.com/LuongNuong131/AF_Booking"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=20,18,17&height=135&section=header&text=AF%20Booking&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=55" alt="AF Booking" width="100%" /></a>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Actively%20developed-c49a62?style=for-the-badge" alt="Actively developed" />
  <img src="https://img.shields.io/badge/Vue%203%20%2B%20TypeScript-42b883?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue 3 and TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/TiDB%20%2F%20MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="TiDB and MySQL" />
</p>

**AF Booking** is an internal multi-role workspace designed around one operational question: *what is the current state of this booking, who owns the next action and what changed?*

It adds the layer that booking teams need around an existing transaction system: canonical search, supplier folders, booking snapshots, append-only notes, handovers, reminders, invoices, reports, realtime activity and auditable administration. The product is deliberately focused on clarity and accountability rather than trying to become another booking engine.

<p align="center">
  <img src="https://raw.githubusercontent.com/LuongNuong131/AF_Booking/main/docs/images/login-preview.png" alt="AF Booking login experience" width="49%" />
  <img src="https://raw.githubusercontent.com/LuongNuong131/AF_Booking/main/docs/images/add-booking-preview.png" alt="AF Booking add booking workflow" width="49%" />
</p>

| Product layer | What it explores |
|---|---|
| **Workspace** | Smart search, supplier folders, monthly navigation and canonical booking detail. |
| **Handover** | Append-only notes, status updates, ownership, drafts, conflict review and activity history. |
| **Collaboration** | Watches, assignments, advisory locks, presence, takeover notifications and private tasks. |
| **Operations** | Reports, invoices, exports, admin workflows, integrity checks and system diagnostics. |
| **Engineering** | Vue 3, strict TypeScript, FastAPI, async SQLAlchemy, TiDB/MySQL, WebSockets and CI. |

[Open AF Booking →](https://github.com/LuongNuong131/AF_Booking)

### LuNu Music — a private listening room

<a href="https://github.com/LuongNuong131/LuNu_Music"><img src="https://img.shields.io/badge/LuNu%20Music-Premium%20music%20library-f5b97a?style=for-the-badge&logo=musicbrainz&logoColor=171717" alt="LuNu Music" /></a>

**LuNu Music** is a fullstack music library designed as a private listening room. It combines a Vue 3/Vite interface with a FastAPI backend, Supabase data, Cloudinary media delivery, Render deployment and Vercel hosting.

The product includes a global player, queue, Now Playing view, personal playlists, Lyrics Lab, Personal Rotation, media administration, member proposals, notifications and **LuNu Cinema / Tea Room** for authorized video content. Its visual language is built around Midnight Vinyl: dark surfaces, warm amber accents, glass panels and responsive layouts that remain usable from desktop to mobile.

| System | Implementation |
|---|---|
| **Experience** | Vue 3, Vite, responsive design tokens, player shell and mobile-safe interaction layers. |
| **Services** | FastAPI, signed sessions, media jobs, moderation workflows and notification APIs. |
| **Data** | Supabase Postgres for users, songs, Cinema, proposals, profiles and social features. |
| **Media** | Cloudinary delivery with yt-dlp and FFmpeg processing for authorized content. |
| **Delivery** | Vercel frontend and Render Docker backend. |

[Open LuNu Music →](https://github.com/LuongNuong131/LuNu_Music)

### EchoMMO — a connected game ecosystem

<a href="https://github.com/LuongNuong131/EchoMMO"><img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,17,20&height=125&section=header&text=EchoMMO&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=55" alt="EchoMMO" width="100%" /></a>

**EchoMMO** represents my interest in building a complete digital world rather than an isolated screen. It explores how a Vue frontend, Java backend, relational data, authentication, game mechanics, social systems and realtime communication can become one coherent product.

| Product layer | What it explores |
|---|---|
| **Identity** | Registration, login, roles, profiles, account security and recovery flows. |
| **Game systems** | Characters, combat, PvP, exploration, gathering, equipment, quests and progression. |
| **Economy** | Inventory, items, wallets, shops, gift codes and marketplace workflows. |
| **Community** | Friends, private messages, chat, notifications, reports and leaderboards. |
| **Operations** | Administration, moderation, configuration and data-oriented tooling. |

The project is organized as a connected family of repositories so the product can be understood from interface to persistence:

- [EchoMMO](https://github.com/LuongNuong131/EchoMMO) — application shell and early product experience.
- [EchoMMO-Frontend](https://github.com/LuongNuong131/EchoMMO-Frontend) — Vue interface, Pinia state, routing, localization and game views.
- [EchoMMO-Backend](https://github.com/LuongNuong131/EchoMMO-Backend) — Java 17, Spring Boot, REST, JPA, JWT and WebSocket configuration.
- [EchoMMO-DB](https://github.com/LuongNuong131/EchoMMO-DB) — MySQL schema and seed data for the game world.

## Selected work

| Project | What it represents | Main technologies |
|---|---|---|
| [LuNu Messenger](https://github.com/LuongNuong131/LuNu-Messenger) | A focused communication product exploring conversations and application flow. | Vue |
| [CRM Nội Bộ](https://github.com/LuongNuong131/CRM_NoiBo) | An internal-management system centered on structured data and practical workflows. | Vue |
| [Thanh Luan Mobile](https://github.com/LuongNuong131/Thanh-Luan-Mobile-Frontend) · [Backend](https://github.com/LuongNuong131/Thanh-Luan-Mobile-Backend) | A mobile-oriented product line with a dedicated backend service. | Vue · Java |
| [LuNu Tool VN](https://github.com/LuongNuong131/LuNu_Tool_VN) | Python tooling for practical experiments and automation. | Python |
| [FCDBB](https://github.com/LuongNuong131/FCDBB) · [LuNu_FCDBB](https://github.com/LuongNuong131/LuNu_FCDBB) | A continuing Vue product line shaped through iterative development. | Vue |

## How I build

I prefer projects with enough depth to reveal the relationship between product decisions and engineering decisions. A polished interface becomes much more meaningful when the underlying data model, permission boundary, error state and deployment path have been considered as well.

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
  <img src="https://skillicons.dev/icons?i=vue,vite,typescript,javascript,html,css,python,fastapi,java,spring,mysql,postgres,supabase,docker,git,github,vercel&perline=9" alt="Technologies used by LuNu" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-Vue%203%20%7C%20Vite%20%7C%20TypeScript-41B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Frontend stack" />
  <img src="https://img.shields.io/badge/Backend-Python%20%7C%20FastAPI%20%7C%20Java%20%7C%20Spring-009688?style=flat-square&logo=fastapi&logoColor=white" alt="Backend stack" />
  <img src="https://img.shields.io/badge/Data-Postgres%20%7C%20Supabase%20%7C%20MySQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="Data stack" />
  <img src="https://img.shields.io/badge/Runtime-Node%20%7C%20Docker%20%7C%20FFmpeg-111827?style=flat-square&logo=docker&logoColor=white" alt="Runtime stack" />
  <img src="https://img.shields.io/badge/Delivery-Vercel%20%7C%20Render%20%7C%20GitHub-18181b?style=flat-square&logo=github&logoColor=white" alt="Delivery stack" />
</p>

| Area | Tools I work with |
|---|---|
| **Product interfaces** | Vue 3, Vue Router, Pinia, TypeScript, JavaScript, HTML, CSS, responsive design and interaction systems. |
| **Services** | Python, FastAPI, Java, Spring Boot, REST APIs, WebSockets, authentication and validation. |
| **Persistence** | PostgreSQL, Supabase, MySQL, TiDB, SQLAlchemy, schema design and data workflows. |
| **Media and runtime** | Cloudinary, FFmpeg, yt-dlp, Node.js, Docker and server-side processing. |
| **Workflow** | Git, GitHub, Vercel, Render, GitHub Actions, VS Code and iterative product documentation. |

## GitHub activity

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=LuongNuong131&theme=tokyonight" width="100%" alt="LuNu GitHub profile details" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=LuongNuong131&theme=tokyonight" height="175" alt="LuNu GitHub statistics" />
  <a href="https://github.com/denvercoder1/github-readme-streak-stats"><img src="./profile/streak.svg" height="175" alt="LuNu GitHub contribution streak" /></a>
</div>

## Currently building

I am continuing to evolve **AF Booking** as a real operations product: refining booking search, collaboration, handovers, reporting, invoices, integrity tooling and the boundaries between realtime convenience and durable data.

In parallel, **LuNu Music** continues to grow as a private media room, with safer media lifecycles, long-running jobs, moderation, notifications and a calmer listening experience. I also keep exploring larger connected systems through EchoMMO and smaller tools that help turn ideas into working software faster.

## Beyond the code

I enjoy the space between engineering and expression. A booking workspace, a music room, a messenger, a game world and a small utility may look unrelated on the surface, but each one asks the same question:

> **Can an idea become a place someone can meaningfully interact with?**

That is the kind of work I want to keep doing — useful enough to matter, thoughtful enough to feel personal and technically strong enough to grow.

## Connect

<div align="center">
  <p><strong>Thanks for visiting my profile.</strong></p>
  <p>Explore the repositories, follow the experiments and connect if you want to build something meaningful.</p>
  <a href="https://github.com/LuongNuong131?tab=repositories"><img src="https://img.shields.io/badge/Explore%20all%20projects-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Explore all projects" /></a>
</div>

<br />

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f5b97a,45:7c3aed,75:312e81,100:080b12&height=115&section=footer" alt="LuNu profile footer" width="100%" />
</div>

<!--
  Profile README for github.com/LuongNuong131
  A product portfolio centered on shipped experiences, system depth and continuous iteration.
  Contribution streak is generated into profile/streak.svg by GitHub Actions.
-->
