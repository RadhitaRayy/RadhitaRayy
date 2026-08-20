<div align="center">

<a href="https://github.com/RadhitaRayy">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&pause=1200&color=6EE7B7&center=true&vCenter=true&width=700&height=60&lines=Hi%2C+I'm+Radhita+Rayhan+%F0%9F%91%8B;Back-End+Developer;API+%26+Systems+Integration+Engineer;FastAPI+%C2%B7+PostgreSQL+%C2%B7+Docker" alt="Radhita Rayhan" />
</a>

<p>
  <img src="https://img.shields.io/badge/Jakarta_Pusat,_ID-0B1220?style=flat-square&logo=googlemaps&logoColor=6EE7B7&labelColor=0B1220" alt="Location" />
  <img src="https://img.shields.io/badge/he%2Fhim-0B1220?style=flat-square&labelColor=0B1220&color=0B1220" alt="Pronouns" />
  <img src="https://img.shields.io/badge/Open_to_collaborate-0B1220?style=flat-square&logo=handshake&logoColor=6EE7B7&labelColor=0B1220" alt="Open to collaborate" />
</p>

<p>
  <a href="https://linkedin.com/in/radhitarayhan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:radhitarayhan@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=RadhitaRayy&style=for-the-badge&color=6EE7B7&label=VISITORS" alt="Profile Views" />
</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" alt="divider" />

</div>

## 👨‍💻 About Me

```python
class RadhitaRayhan:
    role      = "Back-End Developer / Full-Stack Developer"
    focus     = ["API gateways", "service integration", "async Python"]
    daily     = ["FastAPI", "PostgreSQL", "Docker", "Laravel"]
    learning  = ["microservices", "Kubernetes", "observability"]
    debugger  = "console.log()  # and I'm not ashamed 😄"
```

Saya membangun **service back-end** yang menjadi jembatan antar-sistem — REST API,
integrasi OAuth pihak ketiga, background job terjadwal, dan deployment berbasis
container. Fokus saya sekarang: **FastAPI + PostgreSQL async** untuk trafik
request/response yang harus rapi, idempoten, dan mudah di-trace.

<br />

## 🧰 Tech Stack

<div align="center">

**Core — yang saya pakai sehari-hari**

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,nginx,linux,git,bash&theme=dark&perline=8" alt="Core stack" />

**Also comfortable with**

<img src="https://skillicons.dev/icons?i=php,laravel,mysql,js,nodejs,bootstrap,sass,postman&theme=dark&perline=8" alt="Secondary stack" />

**Exploring**

<img src="https://skillicons.dev/icons?i=kubernetes,redis,vercel,figma,gitlab,vscode&theme=dark&perline=6" alt="Exploring" />

<br />

<img src="https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white" />
<img src="https://img.shields.io/badge/Uvicorn-499848?style=flat-square&logo=gunicorn&logoColor=white" />
<img src="https://img.shields.io/badge/asyncpg-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/httpx-0B5394?style=flat-square&logo=curl&logoColor=white" />
<img src="https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white" />
<img src="https://img.shields.io/badge/REST_API-02569B?style=flat-square&logo=swagger&logoColor=white" />
<img src="https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white" />
<img src="https://img.shields.io/badge/Webhooks-6E56CF?style=flat-square&logo=webhooks&logoColor=white" />
<img src="https://img.shields.io/badge/IMAP_%2F_SMTP-D14836?style=flat-square&logo=maildotru&logoColor=white" />
<img src="https://img.shields.io/badge/Google_Calendar_API-4285F4?style=flat-square&logo=googlecalendar&logoColor=white" />
<img src="https://img.shields.io/badge/WhatsApp_API-25D366?style=flat-square&logo=whatsapp&logoColor=white" />

</div>

<br />

## 🌉 Featured Work — Bridge Gateway

> Middleware **FastAPI** yang menjembatani platform aplikasi dengan gateway agen AI.
> Satu pintu REST untuk aktivasi, onboarding, chat, kalender, connector, dan billing.

```mermaid
flowchart LR
    A["📱 Laravel App<br/>(BFF)"] -->|REST + Idempotency-Key| B
    B["🌉 Bridge Gateway<br/>FastAPI · Pydantic v2"]
    B -->|asyncpg| C[("🐘 PostgreSQL<br/>schema: bridge")]
    B -->|httpx| D["🤖 Agent Gateway"]
    B -->|OAuth 2.0| E["📅 Google Calendar / Meet"]
    B -->|IMAP read-only| F["📧 Mailbox"]
    B -->|poller| G["🔔 Webhooks"]
    H["🖥️ Internal Dashboard"] -->|NGINX + Basic auth| B
```

<table>
  <tr><td><b>Runtime</b></td><td>Python 3 · FastAPI · Uvicorn · Pydantic v2</td></tr>
  <tr><td><b>Data</b></td><td>PostgreSQL pada schema terpisah, akses async via <code>asyncpg</code></td></tr>
  <tr><td><b>Integrasi</b></td><td><code>httpx</code> client · OAuth 2.0 (Google Calendar/Meet/Gmail) · IMAP read-only · webhook poller</td></tr>
  <tr><td><b>Deploy</b></td><td>Docker Compose · NGINX reverse-proxy + Basic auth · log harian persisten</td></tr>
  <tr><td><b>Ekstra</b></td><td>Dashboard internal (vanilla JS) · koleksi Postman · dokumentasi antar-tim</td></tr>
</table>

<details>
<summary><b>🔍 Apa yang saya kerjakan di sini</b></summary>

<br />

- **Desain kontrak API** — 20+ router modular (aktivasi, onboarding, chat, kalender, connector, usage, VM, persona)
- **Relasi 1:N** antar entitas instance ⇄ agent, beserta migrasi datanya
- **Idempotensi** request lewat header `Idempotency-Key`, aman terhadap retry klien
- **Roll-up usage/billing** — agregasi event token per agen dan per instance
- **Background job** — poller webhook dan sweeper terjadwal tanpa flap saat restart
- **Observability** — log terstruktur harian, health probe, dashboard status internal

</details>

<br />

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RadhitaRayy&theme=github_dark" alt="Profile details" />
<img width="49%" src="https://github-widgetbox.vercel.app/api/profile?username=RadhitaRayy&data=followers,repositories,stars,commits&theme=darkmode" alt="Profile summary" />

<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=RadhitaRayy&theme=github_dark" alt="Repos per language" />
<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=RadhitaRayy&theme=github_dark" alt="Most commit language" />
<img width="32%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=RadhitaRayy&theme=github_dark&utcOffset=7" alt="Productive time" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=RadhitaRayy&theme=tokyo-night&hide_border=true&area=true&radius=8" alt="Contribution graph" />

</div>

<br />

## 🎯 Currently

| | |
|---|---|
| 🔭 | Membangun **API gateway & service integration** untuk platform agen AI |
| 🌱 | Mendalami **microservices, Docker orchestration, observability** |
| 👯 | Terbuka untuk kolaborasi **open source** dan proyek web yang menantang |
| 💬 | Tanya saya soal **Python/FastAPI, REST API design, PHP/Laravel, PostgreSQL** |
| 📫 | Kontak: **radhitaray123@gmail.com** |

<br />

<div align="center">

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" alt="divider" />

**Thanks for visiting! 👋**  
<sub>⭐ Star repo yang menurutmu menarik — itu bikin saya senang.</sub>

</div>
