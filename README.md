# Data Positioning (.github)

A collection of Data Positioning top level project documentation and resources.

## Project (repository) Schematic

![](Project%20Dependencies.svg 'Project Dependencies')

| Category    | Name                                   | Type                   | Notes                                                                       |
| ----------- | -------------------------------------- | ---------------------- | --------------------------------------------------------------------------- |
|             | .github                                | documentation          | This repository.                                                            |
| development | datapos-development                    | utilities (node)       | A library of utilities for managing the Data Positioning repositories.      |
|             | eslint-config-datapos                  | eslintConfig           | Base ESLint configuration used by all Data Positioning (@datapos) projects. |
| production  | datapos-api \*                         | api                    |                                                                             |
|             | datapos-app-nuxt \*                    | app                    |                                                                             |
|             | datapos-engine \*                      | engine                 |                                                                             |
|             | datapos-resources \*                   | assets                 |                                                                             |
|             | datapos-shared                         | declarations/utilities |                                                                             |
|             | datapos-connector-application-emulator | connector              |                                                                             |
|             | datapos-connector-dexie-js             | connector              |                                                                             |
|             | datapos-connector-file-store-emulator  | connector              |                                                                             |
|             | datapos-connector-rxdb                 | connector              |                                                                             |
|             | datapos-context-default                | context                |                                                                             |
|             | datapos-presenter-default              | presenter              |                                                                             |
|             | datapos-tool-highcharts                | tool                   |                                                                             |
|             | datapos-tool-presenter                 | tool                   |                                                                             |

## Software & Services

Services used to support the production environment:

| Name                                       | Notes                                                                       |
| ------------------------------------------ | --------------------------------------------------------------------------- |
| Alby Chat                                  |                                                                             |
| [Checkly](https://www.checklyhq.com/)      | Response and uptime monitoring.                                             |
| [Cloudflare](https://www.cloudflare.com/)  | Domain registration, application hosting, file storage and state messaging. |
| [Cronitor](https://cronitor.io/)           | Uptime monitoring.                                                          |
| [Hanko](https://www.hanko.io/)             | Authentication and user management.                                         |
| [Honeybadger](https://www.honeybadger.io/) | Error logging and uptime monitoring.                                        |
| [Namecheap](https://www.namecheap.com/)    | Email hosting.                                                              |

Services used to support the development environment:

| Name                                        | Notes                   |
| ------------------------------------------- | ----------------------- |
| [GitGuardian](https://www.gitguardian.com/) | Security management.    |
| [GitHub](https://github.com/home)           | Source code management. |
| [npm](https://www.npmjs.com/)               | Package deployment      |
| [Tolgee](https://tolgee.io/)                | Language translation.   |

| Name                                       | Notes                                                                                        |
| ------------------------------------------ | -------------------------------------------------------------------------------------------- |
| BadgeApp                                   |                                                                                              |
| Blockly                                    |                                                                                              |
| Boxy SVG Editor                            |                                                                                              |
| Cytoscape.js                               |                                                                                              |
| [Draw.io](https://app.diagrams.net/)       |                                                                                              |
| ESLint                                     | [eslint](https://eslint.org/)                                                                |
|                                            | [eslint-plugin-import]()                                                                     |
|                                            | [eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security),              |
|                                            | [@types/eslint-plugin-security](https://www.npmjs.com/package/@types/eslint-plugin-security) |
|                                            | [eslint-plugin-sonarjs](https://www.npmjs.com/package/eslint-plugin-sonarjs)                 |
|                                            | [eslint-plugin-unicorn](https://www.npmjs.com/package/eslint-plugin-unicorn)                 |
|                                            | [@typescript-eslint/eslint-plugin]()                                                         |
|                                            | [@typescript-eslint/parser]()                                                                |
|                                            | []()                                                                                         |
|                                            | []()                                                                                         |
|                                            | []()                                                                                         |
| Icônes (Lucide, Pictogrammers, Streamline) |                                                                                              |
| Micromark                                  |                                                                                              |
| Nuxt / Vue                                 |                                                                                              |
| Prettier                                   | [prettier](https://prettier.io/)]                                                            |
| Rust                                       |                                                                                              |
| Tailwind                                   |                                                                                              |
| TanStack Virtual                           |                                                                                              |
| TypeScript (JavaScript)                    |                                                                                              |
| Vite                                       | [vite](https://vite.dev/)                                                                    |
|                                            | [vite-bundle-visualizer](https://www.npmjs.com/package/vite-bundle-visualizer)               |
|                                            | [vite-plugin-dts](https://www.npmjs.com/package/vite-plugin-dts)                             |
|                                            | [vitest](https://vitest.dev/)                                                                |

## Tasks

[Configure Development Computer](<./Configure Laptop.md>)
