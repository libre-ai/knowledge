# `@libre-ai/knowledge`

Read-only TypeScript consumer for the deterministic public Knowledge Object projection.

The JSON Schemas and source objects under `ecosystem/` remain authoritative. Graph ingestion,
trust transitions and projection generation belong to `libre-ai-ecosystem-engine`; this package
only validates the generated projection, verifies its SHA-256 selection digest and exposes stable
queries.

It performs no network access, imports no Git history and never promotes draft or untrusted input.

## État du projet

<!-- libre-ai:project-status:begin -->
<!-- Section générée depuis project.v1.yaml — ne pas éditer à la main. -->

- Situation actuelle : Née verte en γ 3.4 (ex packages/knowledge). Construite et testée, zéro consommateur en aval à ce jour (recherche croisée sur les 34 dépôts de la flotte, 2026-08-18) — en attente d'activation.
- Maturité : usable
- Exposition : spec-published
- Confiance : medium
- Preuves vérifiées le : 2026-08-18
- Avancement : 0 % du périmètre actuellement déclaré

<!-- libre-ai:project-status:end -->

La fiche [`project.v1.yaml`](./project.v1.yaml) est l'autorité de l'état du projet ; cette section en est générée et le gate de flotte échoue si elles divergent.
