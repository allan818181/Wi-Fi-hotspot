<h1 align="center">Wi-Fi in Tanzania</h1>

<p align="center"><b>Find Wi-Fi hotspots across Tanzania and buy access vouchers online.</b></p>

<p align="center">![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?logo=framer&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)</p>

## Overview

React + TypeScript platform on Supabase to find Wi-Fi hotspots across Tanzania and buy access vouchers, with auth, a user dashboard and SQL migrations.

## Features

- Hotspot directory across Tanzanian cities
- Buy Wi-Fi vouchers, with purchase success and voucher pages
- Sign-up/sign-in and a personal dashboard of vouchers
- Supabase Postgres schema managed with migrations (`supabase/migrations`)
- Animated, responsive UI (Framer Motion, Tailwind)

## Tech stack

TypeScript · React · Vite · Tailwind CSS · Framer Motion · Supabase · GitHub Actions

## Getting started

```bash
npm install
npm run dev                     # http://localhost:8080 (or the port Vite prints)
npm run build                   # production build in dist/
```

The app talks to [Supabase](https://supabase.com) (auth + Postgres). Create a `.env` with your own project URL and anon key before running it; keys are never committed.

## Project structure

`src/pages` (Hotspots, Purchase, Vouchers, Dashboard, Auth) · `supabase/` config and migrations

---

<p align="center">Built by <a href="https://github.com/allan818181"><b>Allan Muganyizi Deus</b></a> · Full-Stack &amp; DevOps Engineer · Dar es Salaam, Tanzania<br/>
<a href="https://www.linkedin.com/in/allan-deus-4b888631a">LinkedIn</a> · <a href="mailto:allandeus014@gmail.com">Email</a></p>
