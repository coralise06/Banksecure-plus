# Banksecure-plus
Plateforme bancaire sécurisée - projet professionnel
# BankSecure+

Plateforme bancaire sécurisée permettant aux clients de gérer leurs comptes et transactions en toute confiance, avec détection automatique de fraude et traçabilité complète des actions sensibles.

## 🎯 Contexte

Une banque doit répondre à deux besoins simultanés et différents :

- **Le client** veut consulter son solde, effectuer des transactions et être notifié en cas d'anomalie ou de fraude sur son compte, sans avoir à surveiller lui-même chaque opération.
- **La banque** doit détecter automatiquement les comportements suspects, permettre à un agent d'intervenir sur les cas signalés, et garder une traçabilité complète de toute action sensible — une exigence réglementaire incontournable dans le secteur bancaire.

BankSecure+ répond à ces deux besoins avec un backend sécurisé, un moteur de détection de fraude basé sur des règles, et un système d'audit intégré à l'architecture.

## 🚧 Statut du projet

En développement — **Sprint 0 : cadrage** (architecture, modélisation, mise en place du dépôt).
Aucune fonctionnalité n'est encore implémentée à ce stade.

## 🛠️ Stack technique prévue

- **Backend** : Java 21, Spring Boot 3, Spring Security, Spring Data JPA
- **Base de données** : PostgreSQL
- **Authentification** : JWT (Refresh Token en fonctionnalité avancée)
- **Documentation API** : Swagger / OpenAPI
- **Tests** : JUnit 5, Mockito, Testcontainers
- **CI/CD** : GitHub Actions
- **Conteneurisation** : Docker, docker-compose

## ✅ Fonctionnalités prévues

### MVP (obligatoire)
- Authentification JWT et gestion des rôles (Client / Administrateur)
- Gestion des comptes (création, consultation, clôture)
- Gestion des transactions (virement, historique)
- Moteur de détection de fraude basé sur des règles
- Journal d'audit des actions sensibles (Audit Log)
- Documentation API via Swagger/OpenAPI
- Modèle analytique (OLAP) et endpoints de reporting

### Optionnel (si le MVP est terminé et solide)
- Dashboard analytics web
- Refresh Token
- Authentification à deux facteurs (2FA)
- Espace agent bancaire dédié
- Export PDF des relevés de compte

## 🗺️ Roadmap

Le détail des sprints et l'avancement sont suivis dans [`docs/roadmap.md`](docs/roadmap.md).

## 📐 Architecture et décisions techniques

- Documentation d'architecture : [`docs/architecture.md`](docs/architecture.md)
- Sécurité : [`docs/security.md`](docs/security.md)
- Modèle de données : [`docs/database.md`](docs/database.md)
- Justification des choix techniques : [`ARCHITECTURE_DECISIONS.md`](ARCHITECTURE_DECISIONS.md)