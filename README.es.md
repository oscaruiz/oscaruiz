# ¡Hola, soy Óscar! 👋

~9 años en roles full stack y backend. Me interesan los dominios bien modelados, los límites claros entre módulos y el código que comunica intención.

Actualmente desarrollando **[myCQRS](https://github.com/oscaruiz/myCQRS)**, un framework CQRS desde cero en Java, que explora arquitectura hexagonal, modelado de eventos de dominio y segregación entre lectura y escritura.

## Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## Proyectos destacados

### [myCQRS](https://github.com/oscaruiz/myCQRS)
Framework personal de CQRS construido desde cero en Java 21. Core agnóstico al framework publicado como tres artefactos Maven (`mycqrs-core` + módulos de integración para Spring Boot y Micronaut) en GitHub Packages. Portabilidad demostrada por tres consumidores independientes que corren sobre Spring Boot, Java sin framework, y Micronaut (este último en un repositorio separado). Implementa outbox pattern, arquitectura hexagonal, DDD, y límites arquitectónicos verificados por ArchUnit. La demo de Spring Boot es la implementación principal —estructura de producción, con PostgreSQL + MongoDB + outbox poller— y está **desplegada en vivo en [mycqrs.onrender.com](https://mycqrs.onrender.com)**.

- **[myCQRS-micronaut](https://github.com/oscaruiz/myCQRS-micronaut)**: consumidor externo de `mycqrs-core` y `mycqrs-micronaut` sobre Micronaut, en un repositorio separado. Implementa un bounded context de Subscription con arquitectura hexagonal y adaptadores en memoria; depende únicamente de los artefactos Maven publicados, demostrando la portabilidad sin las comodidades del monorepo.

`Java 21` `Spring Boot 3` `Micronaut 4` `CQRS` `DDD` `Arquitectura Hexagonal` `Outbox Pattern` `GitHub Packages`

### [Playas Cantabria](https://github.com/oscaruiz/playas-cantabria)
Aplicación web y móvil que muestra las condiciones en tiempo real de todas las playas de Cantabria: olas, viento, temperatura, mareas y estado de la bandera de Cruz Roja. Backend en TypeScript con Express y arquitectura hexagonal, con scraping de varias fuentes públicas (incluida AEMET) gestionando codificaciones de caracteres a medida. Frontend en React + Ionic con mapas Leaflet, empaquetado para móvil con Capacitor. Desplegado en Render y Firebase.

`TypeScript` `Node.js` `Express` `Arquitectura Hexagonal` `React` `Ionic` `Leaflet` `Capacitor`

### Motorsport Hubs
Empezaron como bots de Telegram en Python ([f1spainbot](https://github.com/oscaruiz/f1spainbot), [motogpbot](https://github.com/oscaruiz/motogpbot)) y crecieron hasta convertirse en aplicaciones web completas con Next.js:

- **[F1 Hub](https://f1-hub-telegram.vercel.app/)**: clasificaciones de pilotos y constructores, calendario de carreras, resultados en vivo y alertas de sesiones por Telegram. Construido sobre Next.js App Router con `next-intl` (ES/EN) y grammY para el bot.
- **[MotoGP Hub](https://motogp-hub-telegram.vercel.app/en)**: calendarios de MotoGP, clasificaciones y resultados de carreras. También con Next.js.

`Next.js` `TypeScript` `Vercel` `Python`

### Otros
- **[One Dimension](https://nanashigames.itch.io/one-dimension)**: juego arcade para Android, desarrollado junto a un amigo (500+ descargas).

  `C#` `Unity` `Android`

---

📍 Cantabria, España · [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%C3%B3scar-ruiz-fern%C3%A1ndez/)

_Léelo en otros idiomas: [English](README.md)_
