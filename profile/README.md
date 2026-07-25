<div align="center">

# _ForgePack_

Bibliotecas e produtos reutilizáveis para back-end, front-end e infraestrutura.

[![Maven Central](https://img.shields.io/badge/Maven%20Central-dev.forgepack-C71A36?logo=apachemaven&logoColor=white)](https://central.sonatype.com/namespace/dev.forgepack)
[![npm](https://img.shields.io/badge/npm-%40forgepack-CB3837?logo=npm&logoColor=white)](https://www.npmjs.com/org/forgepack)
[![Site](https://img.shields.io/badge/site-forgepack.dev-000000)](https://forgepack.dev)

**[Frameworks](#-frameworks-libraries)** · **[Products](#-products)** · **[Examples](#-examples)** · **[Docs](#-docs)** · **[Como usar](#-como-usar)**

</div>

---

## O que é o ForgePack

A ForgePack é um conjunto de bibliotecas e aplicações reutilizáveis para acelerar o desenvolvimento de sistemas.

-  🧱 **Frameworks**: bibliotecas reutilizáveis publicadas no Maven Repository e npm.
-  📦 **Products**: aplicações completas construídas utilizando os frameworks.
-  📚 **Documentation**: documentação, arquitetura e exemplos.

---

## 🧱 Frameworks (Libraries)

Repositórios de bibliotecas reutilizáveis que **não possuem interface própria** e normalmente são utilizadas como dependências de outros projetos.

### Backend · Maven Central

| Library | Versão | Descrição | Topic |
|---|---|---|---|
| [library](https://github.com/forgepack/library) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/library)](https://central.sonatype.com/artifact/dev.forgepack/library) | Pacote Completo | [`backend,library`](https://github.com/orgs/forgepack/repositories?q=topic:backend,library) |
| [utils](https://github.com/forgepack/utils) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/utils)](https://central.sonatype.com/artifact/dev.forgepack/utils) | Utilitários gerais. Código compartilhado entre módulos | [`infra`](https://github.com/orgs/forgepack/repositories?q=topic:infra) |
| [core](https://github.com/forgepack/core) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/core)](https://central.sonatype.com/artifact/dev.forgepack/core) | Exceptions, DTOs, Helpers, Configurações | [`backend,library`](https://github.com/orgs/forgepack/repositories?q=topic:backend) |
| [authentication](https://github.com/forgepack/authentication) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/authentication)](https://central.sonatype.com/artifact/dev.forgepack/authentication) | Autenticação | [`backend,library,authentication`](https://github.com/orgs/forgepack/repositories?q=topic:backend,library,authentication) |
| [authorization](https://github.com/forgepack/authorization) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/authorization)](https://central.sonatype.com/artifact/dev.forgepack/authorization) | JWT, OAuth, Login, Roles, Spring Security | [`backend,library,authorization`](https://github.com/orgs/forgepack/repositories?q=topic:backend,library,authorization) |

### Front-end · NPM

| Library | Versão | Descrição | Topic |
|---|---|---|---|
| [leaflet](https://github.com/forgepack/leaflet) | [![npm](https://img.shields.io/npm/v/@forgepack/leaflet)](https://www.npmjs.com/package/@forgepack/leaflet) | Componentes React, hooks, providers | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [request](https://github.com/forgepack/request) | [![npm](https://img.shields.io/npm/v/@forgepack/request)](https://www.npmjs.com/package/@forgepack/request) | Componentes Leaflet, hooks, providers | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [io](https://github.com/forgepack/io) | [![npm](https://img.shields.io/npm/v/@forgepack/io)](https://www.npmjs.com/package/@forgepack/io) | Input, Select | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [ui](https://github.com/forgepack/ui) | [![npm](https://img.shields.io/npm/v/@forgepack/ui)](https://www.npmjs.com/package/@forgepack/ui) | Botões, tabelas, formulários, modais | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [react](https://github.com/forgepack/react) | [![npm](https://img.shields.io/npm/v/@forgepack/react)](https://www.npmjs.com/package/@forgepack/react) | Componentes React, hooks, providers | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |

---

## 📦 Products

| Produto | Descrição | API | Web | Topic |
|---|---|---|---|---|
| WMS | Warehouse Management System | [wms-api](https://github.com/forgepack/wms-api) | [wms-web](https://github.com/forgepack/wms-web) | [`wms`](https://github.com/orgs/forgepack/repositories?q=topic:wms) |
| PDV | Registrar vendas, controlar estoque e emitir notas fiscais | [pdv-api](https://github.com/forgepack/pdv-api) | [pdv-web](https://github.com/forgepack/pdv-web) | [`pdv`](https://github.com/orgs/forgepack/repositories?q=topic:pdv) |
| ERP | Compras, faturamento, financeiro | [erp-api](https://github.com/forgepack/erp-api) | [erp-web](https://github.com/forgepack/erp-web) | [`erp`](https://github.com/orgs/forgepack/repositories?q=topic:erp) |
| TMS | Gerencia a frota, calcula custo de frete, define rotas e rastreia entregas | [tms-api](https://github.com/forgepack/tms-api) | [tms-web](https://github.com/forgepack/tms-web) | [`tms`](https://github.com/orgs/forgepack/repositories?q=topic:tms) |
| Loan | Gerencia trocas e empréstimos de bens | [loan-api](https://github.com/forgepack/loan-api) | [loan-web](https://github.com/forgepack/loan-web) | [`loan`](https://github.com/orgs/forgepack/repositories?q=topic:loan) |
| Stickers | Álbum de figurinhas multi-tema (FIFA, NFL, NBA como dados/conteúdo, não repositórios separados) | [stickers-api](https://github.com/forgepack/stickers-api) | [stickers-web](https://github.com/forgepack/stickers-web) | [`stickers`](https://github.com/orgs/forgepack/repositories?q=topic:stickers) |
| Barcode | Leitura de código de barras | [barcode-api](https://github.com/forgepack/barcode-api) | [barcode-web](https://github.com/forgepack/barcode-web) | [`barcode`](https://github.com/orgs/forgepack/repositories?q=topic:barcode) |
| Scrum | Gerenciamento de projetos em equipes | [scrum-api](https://github.com/forgepack/scrum-api) | [scrum-web](https://github.com/forgepack/scrum-web) | [`scrum`](https://github.com/orgs/forgepack/repositories?q=topic:scrum) |
| Risk | Análise de risco | [risk-api](https://github.com/forgepack/risk-api) | [risk-web](https://github.com/forgepack/risk-web) | [`risk`](https://github.com/orgs/forgepack/repositories?q=topic:risk) |
| Weather | Registro de observações meteorológicas | [weather-api](https://github.com/forgepack/weather-api) | [weather-web](https://github.com/forgepack/weather-web) | [`weather`](https://github.com/orgs/forgepack/repositories?q=topic:weather) |
| Signal | — | [signal-api](https://github.com/forgepack/signal-api) | [signal-web](https://github.com/forgepack/signal-web) | [`signal`](https://github.com/orgs/forgepack/repositories?q=topic:signal) |
| Research | — | [research-api](https://github.com/forgepack/research-api) | [research-web](https://github.com/forgepack/research-web) | [`research`](https://github.com/orgs/forgepack/repositories?q=topic:research) |
---

## 🧪 Examples

Repositórios de referência mostrando como consumir os frameworks acima.

- [example-barcode-api](https://github.com/forgepack/example-barcode-api)
- [example-barcode-web](https://github.com/forgepack/example-barcode-web)

---

## 📚 Docs

- [site](https://github.com/forgepack/site) — site institucional
- [architecture](https://github.com/forgepack/architecture) — arquitetura, diagramas de dependência entre módulos

---

## 🚀 Como usar

**Maven** (`pom.xml`)
```xml
<dependency>
    <groupId>dev.forgepack</groupId>
    <artifactId>core</artifactId>
    <version><!-- ver badge acima --></version>
</dependency>
```

**npm**
```bash
npm install @forgepack/ui
```

## 🔍 Navegando pela organização

- **Todos os frameworks:** [`topic:library`](https://github.com/orgs/forgepack/repositories?q=topic:library)
- **Todos os produtos de um domínio:** ex. [`topic:barcode`](https://github.com/orgs/forgepack/repositories?q=topic:barcode)
- **Templates para novos repositórios** (Settings → Template repository):
  - `template-library-maven` — README, componentes relacionados, `pom.xml`, licença, CI básico
  - `template-library-npm` — README, componentes relacionados, `package.json`, licença, CI básico
  - `template-api` — api, libs consumidas
  - `template-web` — web, libs consumidas

<div align="center">

**Made by [ForgePack](https://github.com/forgepack)** · **[forgepack.dev](https://forgepack.dev)**

</div>
