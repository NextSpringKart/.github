    updated on: 14th June 2025, Saturday

<div align="center">
    <picture>
        <source media="(prefers-color-scheme: light)" srcset="client/src/app/favicon.ico" width="200">
        <source media="(prefers-color-scheme: dark)" srcset="client/src/app/favicon.ico" width="200">
        <img src="client/src/app/favicon.ico" width="200" alt="logo">
    </picture>
    <br/>
    <p style="font-family: roboto, calibri; font-size:12pt; font-style:italic">A sleek nextJS and SpringBoot web app</p>
    <a src="https://github.com/NextSpringKart/forks">
        <img alt="GitHub forks" src="https://img.shields.io/github/forks/NextSpringKart?style=for-the-badge&labelColor=black&logo=github" alt="forks">
    </a>
</div>

# [Next Spring Kart](https://github.com/NextSpringKart)

![line]

## Table of Contents

- [Introduction](#introduction)
- [Architecture Overview](#architecture-overview)
- [Tech Stack Used](#tech-stack-used)
- [Preview](#preview)
- [Best Contributors](#best-contributors)
- [License](#license)

![line]

## Introduction

- 🚀 NextSpringKart is a modern eCommerce web application built with Next.js for a lightning-fast, SEO-optimized frontend and Spring Boot for a robust, scalable backend.
- 🛒 It offers smooth product browsing, secure user authentication, and seamless cart and checkout functionality via RESTful APIs.
- 🔗 Designed with a decoupled architecture, it ensures flexibility, maintainability, and easy deployment across cloud platforms.

## Architecture Overview

```
┌─────────────────┐    ┌──────────────────┐
│   Next.js       │────│  API Gateway     │
│   Frontend      │    │  (Port: 8080)    │
└─────────────────┘    └──────────────────┘
                              │
                    ┌─────────┼─────────┐
                    │         │         │
          ┌─────────▼──┐ ┌────▼────┐ ┌──▼─────────┐
          │ User       │ │ Product │ │ Order      │
          │ Service    │ │ Service │ │ Service    │
          │ (8081)     │ │ (8082)  │ │ (8083)     │
          └────────────┘ └─────────┘ └────────────┘
                    │         │            │
          ┌─────────▼──┐ ┌────▼─────┐ ┌────▼─────────┐
          │ Payment    │ │ Inventory│ │ Notification │
          │ Service    │ │ Service  │ │   Service    │
          │ (8084)     │ │ (8085)   │ │   (8086)     │
          └────────────┘ └──────────┘ └──────────────┘
                              │
                    ┌─────────▼─────────┐
                    │ Service Discovery │
                    │ (Eureka - 8761)   │
                    └───────────────────┘
```

![line]

## Tech Stack Used

- Framework: NEXT.JS 15 [React 19]
- Styling: tailwindCSS
- UI Library: shadcn/ui
- Database: Postgres [Neon DB]
- SpringBoot [Kotlin] 
- More to go

![Next.JS 15](https://img.shields.io/badge/Next.js%2015-black?style=for-the-badge&logo=next.js&logoColor=white) ![React 19](https://img.shields.io/badge/react%2019-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Radix UI](https://img.shields.io/badge/radix%20ui-161618.svg?style=for-the-badge&logo=radix-ui&logoColor=white) ![shadcn/ui](https://img.shields.io/badge/Shadcn/ui-black?style=for-the-badge&logo=shadcnui&logoColor=white) ![Lucide](https://img.shields.io/badge/lucide-%23CC0000.svg?style=for-the-badge&logo=lucid&logoColor=white) ![Lucia](https://img.shields.io/badge/Lucia-5f57ff?style=for-the-badge&logo=lucia&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/prettier-1A2B34?style=for-the-badge&logo=prettier&logoColor=pink) ![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black) ![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white) ![Uploadthing](https://img.shields.io/badge/uploadthing-cc0000?style=for-the-badge) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![.env](https://img.shields.io/badge/dotenv-ECD53F?style=for-the-badge&logo=dotenv&logoColor=black) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Dependabot](https://img.shields.io/badge/dependabot-025E8C?style=for-the-badge&logo=dependabot&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Context-API](https://img.shields.io/badge/Context--Api-000000?style=for-the-badge&logo=react) ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)

![line]

## Preview

<picture align="center">
    <source media="(prefers-color-scheme: light)" srcset=".github/preview-light.png">
    <source media="(prefers-color-scheme: dark)" srcset=".github/preview-dark.png">
    <img src=".github/preview-light.png" alt="preview">
</picture>

![line]

## Best Contributors

<div align="center">
    <a href="https://github.com/NextSpringKart/graphs/contributors">
        <img src="https://contrib.rocks/image?repo=NextSpringKart" alt="contributors"/>
    </a>
</div>

![line]

## License

- See [LICENSE]

**Pritam Kundu, 2024**

![line]

## Thank you, everyone 💚

[icons]: https://icons8.com
[markdown-badges]: https://github.com/warmachine028/markdown-badges
[line]: https://user-images.githubusercontent.com/75939390/137615281-3a875960-92cc-407f-97fe-fd2319bdb252.png
[License]: https://github.com/NextSpringKart/blob/main/LICENSE

<!-- 14/06/25 -->
