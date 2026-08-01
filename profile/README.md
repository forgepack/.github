<div align="center">

# _ForgePack_

Bibliotecas e produtos reutilizáveis para back-end, front-end e infraestrutura.

<p>
  <a href="https://central.sonatype.com/namespace/dev.forgepack"><img src="https://img.shields.io/badge/Maven%20Central-dev.forgepack-C71A36?logo=apachemaven&logoColor=white"></a>
  <a href="https://www.npmjs.com/org/forgepack"><img src="https://img.shields.io/badge/npm-%40forgepack-CB3837?logo=npm&logoColor=white"></a>
  <a href="https://forgepack.dev"><img src="https://img.shields.io/badge/site-forgepack.dev-000000"></a>
</p>

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
| [forgepack-core](https://github.com/forgepack/forgepack-core) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-core)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-core) | Framework CRUD genérico, auditoria JPA, cache, HATEOAS e tratamento de exceções | [`backend,core`](https://github.com/orgs/forgepack/repositories?q=topic:backend,core) |
| [forgepack-validation](https://github.com/forgepack/forgepack-validation) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-validation)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-validation) | Constraints Bean Validation customizados (`@HasDigit`, `@HasLetter`, `@Unique`, etc.) | [`backend,validation`](https://github.com/orgs/forgepack/repositories?q=topic:backend,validation) |
| [forgepack-utils](https://github.com/forgepack/forgepack-utils) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-utils)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-utils) | Criptografia E2EE (AES), geração de QR Code e envio de e-mail | [`backend,utils`](https://github.com/orgs/forgepack/repositories?q=topic:backend,utils) |
| [forgepack-security](https://github.com/forgepack/forgepack-security) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-security)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-security) | JWT, rate limiting, CORS, security headers e filtros Spring Security | [`backend,security`](https://github.com/orgs/forgepack/repositories?q=topic:backend,security) |
| [forgepack-authentication](https://github.com/forgepack/forgepack-authentication) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-authentication)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-authentication) | Login, logout, refresh token e autenticação TOTP/2FA | [`backend,authentication`](https://github.com/orgs/forgepack/repositories?q=topic:backend,authentication) |
| [forgepack-authorization](https://github.com/forgepack/forgepack-authorization) | [![Maven Central](https://img.shields.io/maven-central/v/dev.forgepack/forgepack-authorization)](https://central.sonatype.com/artifact/dev.forgepack/forgepack-authorization) | RBAC: gestão de User, Role e Privilege com Spring Security UserDetails | [`backend,authorization`](https://github.com/orgs/forgepack/repositories?q=topic:backend,authorization) |

### Front-end · NPM

| Library | Versão | Descrição | Topic |
|---|---|---|---|
| [leaflet](https://github.com/forgepack/leaflet) | [![npm](https://img.shields.io/npm/v/@forgepack/leaflet)](https://www.npmjs.com/package/@forgepack/leaflet) | Componentes React, e hooks | [`frontend,leaflet`](https://github.com/orgs/forgepack/repositories?q=topic:frontend,leaflet) |
| [request](https://github.com/forgepack/request) | [![npm](https://img.shields.io/npm/v/@forgepack/request)](https://www.npmjs.com/package/@forgepack/request) | Componentes Leaflet, e hooks | [`frontend,request`](https://github.com/orgs/forgepack/repositories?q=topic:frontend,request) |
| [io](https://github.com/forgepack/io) | [![npm](https://img.shields.io/npm/v/@forgepack/io)](https://www.npmjs.com/package/@forgepack/io) | Input, Select, QR and Barcode | [`frontend,io`](https://github.com/orgs/forgepack/repositories?q=topic:frontend,io) |
| [ui](https://github.com/forgepack/ui) | [![npm](https://img.shields.io/npm/v/@forgepack/ui)](https://www.npmjs.com/package/@forgepack/ui) | Botões, tabelas, formulários, modais | [`frontend,ui`](https://github.com/orgs/forgepack/repositories?q=topic:frontend,ui) |
| [react](https://github.com/forgepack/react) | [![npm](https://img.shields.io/npm/v/@forgepack/react)](https://www.npmjs.com/package/@forgepack/react) | Componentes React, hooks, providers | [`frontend,react`](https://github.com/orgs/forgepack/repositories?q=topic:frontend,react) |

---

## 📦 Products

| Produto | Descrição | API | Web | Topic |
|---|---|---|---|---|
| WMS | Warehouse Management System | [wms-api](https://github.com/forgepack/wms-api) | [wms-web](https://github.com/forgepack/wms-web) | [`wms,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:wms,core,request,io) |
| PDV | Registrar vendas, controlar estoque e emitir notas fiscais | [pdv-api](https://github.com/forgepack/pdv-api) | [pdv-web](https://github.com/forgepack/pdv-web) | [`pdv,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:pdv,core,request,io) |
| CRM | Gestão de Relacionamento com o Cliente| [crm-api](https://github.com/forgepack/crm-api) | [crm-web](https://github.com/forgepack/crm-web) | [`crm,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:crm,core,request,io) |
| ERP | Compras, faturamento, financeiro | [erp-api](https://github.com/forgepack/erp-api) | [erp-web](https://github.com/forgepack/erp-web) | [`erp,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:erp,core,request,io) |
| TMS | Gerencia a frota, calcula custo de frete, define rotas e rastreia entregas | [tms-api](https://github.com/forgepack/tms-api) | [tms-web](https://github.com/forgepack/tms-web) | [`tms,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:tms,core,request,io) |
| Loan | Gerencia trocas e empréstimos de bens | [loan-api](https://github.com/forgepack/loan-api) | [loan-web](https://github.com/forgepack/loan-web) | [`loan,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:loan,core,request,io) |
| Stickers | Álbum de figurinhas multi-tema (FIFA, NFL, NBA como dados/conteúdo, não repositórios separados) | [stickers-api](https://github.com/forgepack/stickers-api) | [stickers-web](https://github.com/forgepack/stickers-web) | [`stickers,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:stickers,core,request,io) |
| Scrum | Gerenciamento de projetos em equipes | [scrum-api](https://github.com/forgepack/scrum-api) | [scrum-web](https://github.com/forgepack/scrum-web) | [`scrum,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:scrum,core,request,io) |
| Risk | Análise de risco | [risk-api](https://github.com/forgepack/risk-api) | [risk-web](https://github.com/forgepack/risk-web) | [`risk,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:risk,core,request,io) |
| Weather | Registro de observações meteorológicas | [weather-api](https://github.com/forgepack/weather-api) | [weather-web](https://github.com/forgepack/weather-web) | [`weather,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:weather,core,request,io) |
| Signal | — | [signal-api](https://github.com/forgepack/signal-api) | [signal-web](https://github.com/forgepack/signal-web) | [`signal,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:signal,core,request,io) |
| Research | — | [research-api](https://github.com/forgepack/research-api) | [research-web](https://github.com/forgepack/research-web) | [`research,core,request,io`](https://github.com/orgs/forgepack/repositories?q=topic:research,core,request,io) |
---

## 🧪 Examples

Repositórios de referência mostrando como consumir os frameworks acima.

- [example-api](https://github.com/forgepack/example-api)
- [example-web](https://github.com/forgepack/example-web)

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
  - [`template-maven-library`](https://github.com/forgepack/template-maven-library) — README, componentes relacionados, `pom.xml`, licença, CI básico
  - [`template-npm-library`](https://github.com/forgepack/template-npm-library) — README, componentes relacionados, `package.json`, licença, CI básico
  - `template-api` — api, libs consumidas
  - `template-web` — web, libs consumidas

<div align="center">

**Made by [ForgePack](https://github.com/forgepack)** · **[forgepack.dev](https://forgepack.dev)**

</div>
