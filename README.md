# Hey, I'm Óscar 👋

~9 years across full stack and backend roles. I care about well-modeled domains, clear boundaries between modules, and code that communicates intent.

Currently building **[myCQRS](https://github.com/oscaruiz/myCQRS)**, a CQRS framework from scratch in Java, exploring hexagonal architecture, domain event modeling, and read/write segregation.

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## Featured Projects

### [myCQRS](https://github.com/oscaruiz/myCQRS)
Personal CQRS framework built from scratch in Java 21. Framework-agnostic core published as three Maven artifacts (`mycqrs-core` + Spring Boot and Micronaut integration modules) on GitHub Packages. Portability proven by three independent consumers running on Spring Boot, plain Java, and Micronaut (the latter in a separate repository). Implements outbox pattern, hexagonal architecture, DDD, and ArchUnit-enforced boundaries. The Spring Boot demo is the flagship implementation — production-shaped, with PostgreSQL + MongoDB + outbox poller — and is **deployed live at [mycqrs.onrender.com](https://mycqrs.onrender.com)**.

- **[myCQRS-micronaut](https://github.com/oscaruiz/myCQRS-micronaut)**: external Micronaut consumer of `mycqrs-core` and `mycqrs-micronaut`, in a separate repository. Implements a Subscription bounded context with hexagonal architecture and in-memory adapters; depends only on the published Maven artifacts to prove portability without monorepo conveniences.

`Java 21` `Spring Boot 3` `Micronaut 4` `CQRS` `DDD` `Hexagonal Architecture` `Outbox Pattern` `GitHub Packages`

### [Playas Cantabria](https://github.com/oscaruiz/playas-cantabria)
Web and mobile app showing real-time conditions for every beach in Cantabria: waves, wind, temperature, tides, and Red Cross flag status. Backend built in TypeScript with Express and a hexagonal architecture, scraping multiple public sources (including AEMET) with custom encoding handling. Frontend in React + Ionic with Leaflet maps, packaged for mobile via Capacitor. Deployed on Render and Firebase.

`TypeScript` `Node.js` `Express` `Hexagonal Architecture` `React` `Ionic` `Leaflet` `Capacitor`

### Motorsport Hubs
Started as Python Telegram bots ([f1spainbot](https://github.com/oscaruiz/f1spainbot), [motogpbot](https://github.com/oscaruiz/motogpbot)) and grew into full web applications built with Next.js:

- **[F1 Hub](https://f1-hub-telegram.vercel.app/)**: driver and constructor standings, race calendar, live session results, and Telegram session alerts. Built on Next.js App Router with `next-intl` (ES/EN) and grammY for the bot.
- **[MotoGP Hub](https://motogp-hub-telegram.vercel.app/en)**: MotoGP schedules, standings, and race results. Also built with Next.js.

`Next.js` `TypeScript` `Vercel` `Python`

### Other
- **[One Dimension](https://nanashigames.itch.io/one-dimension)**: arcade game for Android, co-developed with a friend (500+ downloads).

  `C#` `Unity` `Android`

---

📍 Cantabria, Spain · [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%C3%B3scar-ruiz-fern%C3%A1ndez/)

_Read this in other languages: [Español](README.es.md)_
