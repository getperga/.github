<h1 align="center">Perga</h1>

<p align="center">
  <strong>A personal workspace for your notes, plans, and ideas.</strong>
  <br>
  Capture searchable notes, organize your knowledge, and plan your days in one place.
</p>

<p align="center">
  <a href="https://demo.getperga.me/">Try the live demo</a> ·
  <a href="https://getperga.me/signup/">Use Perga Cloud</a> ·
  <a href="https://docs.getperga.me/docs/installation">Self-host Perga</a>
</p>

<p align="center">
  <a href="https://github.com/getperga/perga-api/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-2563eb.svg" alt="License: MIT"></a>
  <a href="https://github.com/getperga/perga-api/stargazers"><img src="https://img.shields.io/github/stars/getperga/perga-api?style=flat&amp;label=API%20stars" alt="API stars"></a>
  <a href="https://github.com/getperga/perga-web/stargazers"><img src="https://img.shields.io/github/stars/getperga/perga-web?style=flat&amp;label=Web%20stars" alt="Web stars"></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/getperga/perga-web/main/docs/assets/notes_screenshot.png" alt="Perga notes" width="49%">
  <img src="https://raw.githubusercontent.com/getperga/perga-web/main/docs/assets/planner_screenshot.png" alt="Perga daily planner" width="49%">
</p>

## What you can do with Perga

- Write rich-text notes and organize them into folders.
- Search, import, and export your notes.
- Plan today while keeping weekly and monthly context in view.
- Create monthly and custom agendas for longer-term plans.
- Install Perga as a PWA and use it in light or dark mode.

## One product, two open-source applications

Perga is split into a browser client and an API. A self-hosted installation runs both applications with PostgreSQL.

| Repository | Role | Stack |
| --- | --- | --- |
| [`perga-web`](https://github.com/getperga/perga-web) | Responsive browser client and PWA | React, TypeScript, Vite, Tailwind CSS, Tiptap |
| [`perga-api`](https://github.com/getperga/perga-api) | REST API, authentication, and data storage | FastAPI, SQLAlchemy, PostgreSQL, Alembic |
| [`perga-docs`](https://github.com/getperga/perga-docs) | Installation and product documentation | Docusaurus |

## Get started

- **Want to explore first?** The [public demo](https://demo.getperga.me/) opens instantly and does not require sign-up. Its data is shared and reset regularly.
- **Want the simplest setup?** [Perga Cloud](https://getperga.me/) is hosted, maintained, and kept up to date for you.
- **Want full control?** Follow the [self-hosting guide](https://docs.getperga.me/docs/installation) to deploy Perga with Docker Compose.
- **Want to understand the components?** Read the [`perga-web`](https://github.com/getperga/perga-web#readme) and [`perga-api`](https://github.com/getperga/perga-api#readme) documentation.

## Open source

The Perga API and web client are available under the [MIT License](https://github.com/getperga/perga-api/blob/main/LICENSE).

<div align="center">
  <a href="https://getperga.me/">Website</a> ·
  <a href="https://demo.getperga.me/">Demo</a> ·
  <a href="https://docs.getperga.me/">Documentation</a> ·
  <a href="mailto:support@getperga.me">Support</a>
</div>
