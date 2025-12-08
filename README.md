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

## Resources

Common resources (files) used across al Data Positioning projects.

| Name                                          | File                                                                 |
| --------------------------------------------- | -------------------------------------------------------------------- |
| ESLint rules                                  | [eslint.config.ts](eslint.config.ts)                                 |
| Git path attributes                           | [.gitattributes](.gitattributes)                                     |
| Git ignore rules for published repositories   | [resources/.gitignore](resources/.gitignore)                         |
| Git ignore rules for unpublished repositories | [.gitignore](.gitignore)                                             |
| LICENSE                                       | [LICENSE](LICENSE)                                                   |
| Markdown lint rules                           | [.markdownlint.json](.markdownlint.json)                             |
| VS Code key bindings                          | [resources/vsCodeKeyBindings.json](resources/vsCodeKeyBindings.json) |

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

| Name                                         | Notes                                 |
| -------------------------------------------- | ------------------------------------- |
| [BadgeApp](https://www.bestpractices.dev/en) | OpenSSF best practices badge program. |
| [Boxy SVG Editor](https://boxy-svg.com/)     | SVG image editor.                     |
| [Draw.io](https://drawio-app.com/)           |                                       |
| [GitGuardian](https://www.gitguardian.com/)  | Security management.                  |
| [GitHub](https://github.com/home)            | Source code management.               |
| [npm](https://www.npmjs.com/)                | Package deployment                    |
| [Shields.io](https://shields.io/)            | Badges.                               |
| [Tolgee](https://tolgee.io/)                 | Language translation.                 |

| Product/Vendor                                       |                                   | Notes                                                |
| ---------------------------------------------------- | --------------------------------- | ---------------------------------------------------- |
| [Blockly](<(https://developers.google.com/blockly)>) | blockly visual programming editor |                                                      |
| [Cytoscape.js](https://js.cytoscape.org/)            |                                   |                                                      |
| Hanko                                                | hanko frontend sdk                | [@teamhanko/hanko-frontend-sdk]()                    |
| Micromark                                            | micromark parser                  | [micromark](https://www.npmjs.com/package/micromark) |
|                                                      | micromark gfm table extension     | [micromark-extension-gfm-table ]()                   |
| Nanoid                                               | nanoid                            | [nanoid()]                                           |
| Nuxt (Vue)                                           | nuxt                              | [nuxt]()                                             |
|                                                      | nuxt fonts                        | [@nuxt/fonts]()                                      |
|                                                      | nuxt i18n                         | [@nuxtjs/i18n]()                                     |
|                                                      | nuxt pinia                        | [@pinia/nuxt]()                                      |
|                                                      | nuxt security                     | [nuxt-security]()                                    |
|                                                      | nuxt ui                           | [nuxt/ui]()                                          |
|                                                      | nuxt vueuse                       | [@vueuse/nuxt]()                                     |
|                                                      | nuxt vueuse router                | [@vueuse/router]()                                   |
|                                                      | vue                               | [vue]()                                              |
|                                                      | vue router                        | [vue-router]()                                       |
|                                                      | vue unhead                        | [@unhead/vue]()                                      |
| Speed Highlight                                      | @speed highlight core             | [@speed-highlight/core ]()                           |
| TanStack Virtual                                     | tanstack vue virtual              | [@tanstack/vue-virtual]()                            |

| Name |     | Notes |
| ---- | --- | ----- |
| git  |     |       |
| node |     |       |
| npm  |     |       |

| Product/Vendor          |                               | Notes                                                                                                                                 |
| ----------------------- | ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| ESLint                  | eslint                        | [eslint](https://eslint.org/)                                                                                                         |
|                         | eslint nuxt                   | [@nuxt/eslint]()                                                                                                                      |
|                         | eslint typescript parser      | [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser)                                                  |
|                         | eslint typescript plugin      | [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@typescript-eslint/eslint-plugin)                                    |
|                         | eslint config datapos         | [eslint-datapos-import](https://www.npmjs.com/package/@datapos/eslint-config-datapos)                                                 |
|                         | eslint plugin import          | [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)                                                            |
|                         | eslint plugin security        | [eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security),                                                       |
|                         | eslint plugin security types  | [@types/eslint-plugin-security](https://www.npmjs.com/package/@types/eslint-plugin-security)                                          |
|                         | eslint plugin sonarjs         | [eslint-plugin-sonarjs](https://www.npmjs.com/package/eslint-plugin-sonarjs)                                                          |
|                         | eslint plugin unicorn         | [eslint-plugin-unicorn](https://www.npmjs.com/package/eslint-plugin-unicorn)                                                          |
| Icônes                  | Lucide                        | [Lucide by Lucide Contributors](https://icones.js.org/collection/lucide)                                                              |
|                         | Pictogrammers                 | [Material Design Icons by Pictogrammers](https://icones.js.org/collection/mdi)                                                        |
|                         | Streamline                    | [Ultimate Free Icons by Streamline](https://icones.js.org/collection/streamline-ultimate)                                             |
| jiti                    | jiti                          | [jiti]()                                                                                                                              |
| License Report          | license report                | [license-report]()                                                                                                                    |
|                         | license report check          | [license-report-check]()                                                                                                              |
|                         | license report recursive      | [license-report-recursive]()                                                                                                          |
| Nanoid                  | nanoid                        | [nanoid()]                                                                                                                            |
| Node                    | node types                    | [@types/node]()                                                                                                                       |
| npm                     | npm check updates             | [npm-check-updates](npm-check-updates)                                                                                                |
| Nuxt (Vue)              | nuxt test utils               | [@nuxt/test-utils]()                                                                                                                  |
| OWASP Dependency Check  | owasp dependency check        | [owasp-dependency-check]()                                                                                                            |
| Prettier                | prettier                      | [prettier](https://prettier.io/)]                                                                                                     |
|                         | prettier tailwind plugin      | [prettier-plugin-tailwindcss]()                                                                                                       |
| Rust                    |                               |                                                                                                                                       |
| Tailwind                |                               | ?Where is this being referenced from? Would be could to include for doco purposes even if nuxt/ui or something else is installing it. |
| TypeScript (JavaScript) | typescript                    |                                                                                                                                       |
|                         | type fest                     | [type-fest](https://www.npmjs.com/package/type-fest)                                                                                  |
| Vite                    | vite                          | [vite](https://vite.dev/)                                                                                                             |
|                         | vite dts plugin               | [vite-plugin-dts](https://www.npmjs.com/package/vite-plugin-dts)                                                                      |
|                         | vite pwa assets generator     | [@vite-pwa/assets-generator]()                                                                                                        |
|                         | vite visualizer rollup plugin | [rollup-plugin-visualizer]()                                                                                                          |
|                         | vitest                        | [vitest](https://vitest.dev/)                                                                                                         |
| wrangler                |                               | See datapos-api.                                                                                                                      |

## Tasks

[Configure Development Computer](<./documents/Configure Laptop.md>)
