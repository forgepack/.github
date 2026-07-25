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
| [library](https://github.com/forgepack/library) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/library)](https://central.sonatype.com/artifact/dev.forgepack/library) | Utilitários gerais | [`infra`](https://github.com/orgs/forgepack/repositories?q=topic:backend,library) |
| [forgepack-utils](https://github.com/forgepack/forgepack-utils) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-utils)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-utils) | Utilitários gerais | [`infra`](https://github.com/orgs/forgepack/repositories?q=topic:infra) |
| [forgepack-common](https://github.com/forgepack/forgepack-common) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-common)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-common) | Código compartilhado entre módulos | [`infra`](https://github.com/orgs/forgepack/repositories?q=topic:infra) |
| [forgepack-core](https://github.com/forgepack/forgepack-core) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-core)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-core) | Exceptions, DTOs, Helpers, Configurações | [`backend`](https://github.com/orgs/forgepack/repositories?q=topic:backend) |
| [forgepack-auth](https://github.com/forgepack/forgepack-auth) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-auth)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-auth) | Autenticação | [`backend`](https://github.com/orgs/forgepack/repositories?q=topic:backend) |
| [forgepack-security](https://github.com/forgepack/forgepack-security) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-security)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-security) | JWT, OAuth, Login, Roles, Spring Security | [`backend`](https://github.com/orgs/forgepack/repositories?q=topic:backend) |

### Front-end · NPM

| Library | Versão | Descrição | Topic |
|---|---|---|---|
| [forgepack-ui](https://github.com/forgepack/forgepack-ui) | [![npm](https://img.shields.io/npm/v/@forgepack/ui)](https://www.npmjs.com/package/@forgepack/ui) | Botões, tabelas, formulários, modais | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [forgepack-react](https://github.com/forgepack/forgepack-react) | [![npm](https://img.shields.io/npm/v/@forgepack/react)](https://www.npmjs.com/package/@forgepack/react) | Componentes React, hooks, providers | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [leaflet](https://github.com/forgepack/leaflet) | [![npm](https://img.shields.io/npm/v/@forgepack/react)](https://www.npmjs.com/package/@forgepack/leaflet) | Componentes React, hooks, providers | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |
| [request](https://github.com/forgepack/request) | [![npm](https://img.shields.io/npm/v/@forgepack/react)](https://www.npmjs.com/package/@forgepack/react) | Componentes React, hooks, providers | [`frontend`](https://github.com/orgs/forgepack/repositories?q=topic:frontend) |

---

## 📦 Products

| Produto | API | Web | Topic | Descrição |
|---|---|---|---|---|
| WMS | [wms-api](https://github.com/forgepack/wms-api) | [wms-web](https://github.com/forgepack/wms-web) | [`wms`](https://github.com/orgs/forgepack/repositories?q=topic:wms) | Warehouse Management System |
| PDV | [pdv-api](https://github.com/forgepack/pdv-api) | [pdv-web](https://github.com/forgepack/pdv-web) | [`pdv`](https://github.com/orgs/forgepack/repositories?q=topic:pdv) | Registrar vendas, controlar estoque e emitir notas fiscais |
| ERP | [erp-api](https://github.com/forgepack/erp-api) | [erp-web](https://github.com/forgepack/erp-web) | [`erp`](https://github.com/orgs/forgepack/repositories?q=topic:erp) | Compras, faturamento, financeiro |
| TMS | [tms-api](https://github.com/forgepack/tms-api) | [tms-web](https://github.com/forgepack/tms-web) | [`tms`](https://github.com/orgs/forgepack/repositories?q=topic:tms) | Gerencia a frota, calcula custo de frete, define rotas e rastreia entregas |
| Stickers | [stickers-api](https://github.com/forgepack/stickers-api) | [stickers-web](https://github.com/forgepack/stickers-web) | [`stickers`](https://github.com/orgs/forgepack/repositories?q=topic:stickers) | Álbum de figurinhas multi-tema (FIFA, NFL, NBA como dados/conteúdo, não repos separados) |
| Barcode | [barcode-api](https://github.com/forgepack/barcode-api) | [barcode-web](https://github.com/forgepack/barcode-web) | [`barcode`](https://github.com/orgs/forgepack/repositories?q=topic:barcode) | Leitura de código de barras |
| Scrum | [scrum-api](https://github.com/forgepack/scrum-api) | [scrum-web](https://github.com/forgepack/scrum-web) | [`scrum`](https://github.com/orgs/forgepack/repositories?q=topic:scrum) | Gerenciamento de projetos em equipes |
| Risk | [risk-api](https://github.com/forgepack/risk-api) | [risk-web](https://github.com/forgepack/risk-web) | [`risk`](https://github.com/orgs/forgepack/repositories?q=topic:risk) | Análise de risco |
| Weather | [weather-api](https://github.com/forgepack/weather-api) | [weather-web](https://github.com/forgepack/weather-web) | [`weather`](https://github.com/orgs/forgepack/repositories?q=topic:weather) | Registro de observações meteorológicas |
| Signal | [signal-api](https://github.com/forgepack/signal-api) | [signal-web](https://github.com/forgepack/signal-web) | [`signal`](https://github.com/orgs/forgepack/repositories?q=topic:signal) | — |
| Research | [research-api](https://github.com/forgepack/research-api) | [research-web](https://github.com/forgepack/research-web) | [`research`](https://github.com/orgs/forgepack/repositories?q=topic:research) | — |

**Produto sem split api/web (⚠️ estrutura ainda a decidir):**
[forgepack-loan](https://github.com/forgepack/forgepack-loan) · `topic: loan`

---

## 🧪 Examples

Repositórios de referência mostrando como consumir os frameworks acima.

- [forgepack-example-barcode-api](https://github.com/forgepack/forgepack-example-barcode-api)
- [forgepack-example-barcode-web](https://github.com/forgepack/forgepack-example-barcode-web)

---

## 📚 Docs

- [forgepack-site](https://github.com/forgepack/forgepack-site) — site institucional
- [forgepack-architecture](https://github.com/forgepack/forgepack-architecture) — arquitetura, diagramas de dependência entre módulos

---

## 🚀 Como usar

**Maven** (`pom.xml`)
```xml
<dependency>
    <groupId>dev.forgepack</groupId>
    <artifactId>forgepack-core</artifactId>
    <version><!-- ver badge acima --></version>
</dependency>
```

**npm**
```bash
npm install @forgepack/ui
```

---

## 🔍 Navegando pela organização

- **Todos os frameworks:** [`topic:library`](https://github.com/orgs/forgepack/repositories?q=topic:library)
- **Todos os produtos de um domínio:** ex. [`topic:barcode`](https://github.com/orgs/forgepack/repositories?q=topic:barcode)
- **Templates para novos repositórios** (Settings → Template repository):
  - `forgepack-template-library` — README, componentes relacionados, `pom.xml`/`package.json`, licença, CI básico
  - `forgepack-template-product` — api, web, libs consumidas

<div align="center">

**Made by [ForgePack](https://github.com/forgepack)** · **[forgepack.dev](https://forgepack.dev)**

</div>
