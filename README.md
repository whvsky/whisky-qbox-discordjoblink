# whisky-qbox-discordjoblink  
Discord → Qbox/QBCore job linking for name tags.

[![Join Whisky Dev Discord](https://img.shields.io/badge/Discord-Support%20Server-5865F2?logo=discord&logoColor=white)](https://discord.gg/6FQtJdBXMk)
[![Repo Views](https://komarev.com/ghpvc/?username=whvsky&repo=whisky-qbox-discordjoblink&style=flat)](https://github.com/whvsky/whisky-qbox-discordjoblink)

Link Discord ACE permissions / roles directly to your **Qbox/QBCore jobs**, so your job-based **name tags, scoreboards, and duty systems** stay synced with Discord automatically.

---

## What you asked for

- Departments like:
  - `group.lspd`
  - `group.bcso`
  - `group.sahp`
- Each department maps to an in-game job with **grade 0** by default (fully editable in config).
- Blank scaffolding for **Discord role IDs** so you can paste your own.
- Optional ACE → department mapping if you want to drive permissions as well as jobs.
- Designed to power:
  - Job-based **name tags**  
  - Scoreboards / UI that rely on the player’s job  
  - Any “on-duty” systems tied to Qbox/QBCore jobs

---

## Looking for help, or custom integrations?

[![Join Whisky Dev Discord](https://img.shields.io/badge/Discord-Support%20Server-5865F2?logo=discord&logoColor=white)](https://discord.gg/6FQtJdBXMk)

---

## Install

1. Add dependencies and this resource in your `server.cfg`:

   ```cfg
   ensure Badger_Discord_API
   ensure whisky-qbox-discordjoblink
