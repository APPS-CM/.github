# OKALM HQ

OKALM HQ est une organisation logicielle basée au Cameroun. Nous concevons des produits numériques pratiques et de haute qualité pour l'Afrique et le monde.

Nous concevons, déployons et exploitons des applications mobiles, des plateformes web et des systèmes backend en privilégiant la fiabilité, la clarté et la maintenabilité à long terme.

## Ce que nous construisons

- Applications mobiles avec Expo / React Native
- Portails web et surfaces marketing avec des stacks frontend modernes
- API backend, outils d'administration et tableaux de bord opérationnels
- Automatisation des releases, documentation et infrastructure produit

## Petit Market

Notre plateforme marketplace phare est répartie en dépôts ciblés :

| Dépôt | Rôle |
| --- | --- |
| [petit-market-mobile](https://github.com/APPS-CM/petit-market-mobile) | Application mobile de production (iOS et Android) |
| [petit-market-mobile-test](https://github.com/APPS-CM/petit-market-mobile-test) | Application de test consommant le package de base partagé |
| [petit-market-web](https://github.com/APPS-CM/petit-market-web) | Portail web public |
| [petit-market-backend](https://github.com/APPS-CM/petit-market-backend) | API PocketBase, schéma et outils d'administration |
| [mobile-marketplace-base](https://github.com/APPS-CM/mobile-marketplace-base) | Package mobile marketplace partagé |

## Tous les dépôts

| Dépôt | Description |
| --- | --- |
| [petit-market-mobile](https://github.com/APPS-CM/petit-market-mobile) | Application mobile Petit Market |
| [petit-market-mobile-test](https://github.com/APPS-CM/petit-market-mobile-test) | Application mobile de test consommant `mobile-marketplace-base` |
| [petit-market-web](https://github.com/APPS-CM/petit-market-web) | Application web Petit Market |
| [petit-market-backend](https://github.com/APPS-CM/petit-market-backend) | Services backend, schéma PocketBase, assets Docker et outils internes |
| [mobile-marketplace-base](https://github.com/APPS-CM/mobile-marketplace-base) | Package de base marketplace mobile réutilisable |
| [agra-mobile](https://github.com/APPS-CM/agra-mobile) | Application mobile privée Agra |
| [sample-repo](https://github.com/APPS-CM/sample-repo) | Dépôt d'exemple |
| [.github](https://github.com/APPS-CM/.github) | Profil de l'organisation et fichiers communautaires partagés |

La plupart des dépôts sont privés. Si vous avez accès à l'organisation, ils apparaissent aussi dans l'[onglet Dépôts](https://github.com/orgs/APPS-CM/repositories).

## Notre façon de travailler

- Un dépôt par plateforme ou responsabilité
- Flux de branches `dev` → `beta` → `main` pour les produits actifs
- Versionnement avec `VERSION`, `CHANGELOG.md` et automatisation des releases
- Documentation et checklists opérationnelles à côté du code
- Extraction de logique partagée uniquement quand elle est suffisamment stable

## Stack technique

- **Mobile :** Expo, React Native, TypeScript, Zustand, EAS
- **Web :** Astro, React, TypeScript
- **Backend :** PocketBase, Go, Docker
- **Infra :** GitHub Actions, Coolify, AWS S3

## Contact et collaboration

Utilisez les issues et pull requests des dépôts pour le travail produit. Pour l'accès aux dépôts privés, contactez un propriétaire de l'organisation.
