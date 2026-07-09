# OKALM HQ

OKALM HQ is a Cameroon-based software organization building practical, high-quality digital products for Africa and the world.

We design, ship, and operate mobile apps, web platforms, and backend systems with a focus on reliability, clarity, and long-term maintainability.

## What We Build

- Mobile applications with Expo / React Native
- Web portals and marketing surfaces with modern frontend stacks
- Backend APIs, admin tools, and operational dashboards
- Release automation, documentation, and product infrastructure

## Petit Market

Our flagship marketplace platform is split into focused repositories:

| Repository | Role |
| --- | --- |
| [petit-market-mobile](https://github.com/APPS-CM/petit-market-mobile) | Production mobile app (iOS & Android) |
| [petit-market-mobile-test](https://github.com/APPS-CM/petit-market-mobile-test) | Test consumer app wired to the shared base package |
| [petit-market-web](https://github.com/APPS-CM/petit-market-web) | Public web portal |
| [petit-market-backend](https://github.com/APPS-CM/petit-market-backend) | PocketBase API, schema, and admin tools |
| [mobile-marketplace-base](https://github.com/APPS-CM/mobile-marketplace-base) | Shared mobile marketplace package |

## All Repositories

| Repository | Description |
| --- | --- |
| [petit-market-mobile](https://github.com/APPS-CM/petit-market-mobile) | Mobile app for Petit Market |
| [petit-market-mobile-test](https://github.com/APPS-CM/petit-market-mobile-test) | Test mobile app consuming `mobile-marketplace-base` |
| [petit-market-web](https://github.com/APPS-CM/petit-market-web) | Web app for Petit Market |
| [petit-market-backend](https://github.com/APPS-CM/petit-market-backend) | Backend services, PocketBase schema, Docker assets, and internal tools |
| [mobile-marketplace-base](https://github.com/APPS-CM/mobile-marketplace-base) | Reusable mobile marketplace base package |
| [agra-mobile](https://github.com/APPS-CM/agra-mobile) | Private Agra mobile application |
| [sample-repo](https://github.com/APPS-CM/sample-repo) | Sample repository |
| [.github](https://github.com/APPS-CM/.github) | Organization profile and shared community files |

Most repositories are private. If you have access to the organization, they appear in the [repositories tab](https://github.com/orgs/APPS-CM/repositories) as well.

## How We Work

- One repository per platform or responsibility
- `dev` → `beta` → `main` branch flow for active products
- Versioning with `VERSION`, `CHANGELOG.md`, and release automation
- Documentation and operational checklists live next to the code
- Shared logic is extracted only when it is stable enough to reuse

## Tech Stack

- **Mobile:** Expo, React Native, TypeScript, Zustand, EAS
- **Web:** Astro, React, TypeScript
- **Backend:** PocketBase, Go, Docker
- **Infra:** GitHub Actions, Coolify, AWS S3

## Contact & Collaboration

Use repository issues and pull requests for product work. For access to private repositories, contact an organization owner.
