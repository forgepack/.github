# _ForgePack_

Bibliotecas e produtos reutilizáveis para back-end, front-end e infraestrutura.

produtos ou componentes (repositórios cujo objetivo é serem reutilizados por outros projetos)
O README.md de cada produto possui uma seção de links para componentes relacionados.

## Repositories
- FRAMEWORK (component): Repositórios que não têm interface para o usuário final, não fazem sentido isoladamente e são publicados como bibliotecas/módulos — dependências de outros repositórios.
    - INFRA `topic: library, backend`
        - [forgepack-utils](https://github.com/forgepack/forgepack-utils): utilitários gerais
        - [forgepack-common](https://github.com/forgepack/forgepack-common): código compartilhado entre módulos
    - back-end `topic: library, backend`
        - [forgepack-core](https://github.com/forgepack/forgepack-core): exceptions, DTOs, Helpers, Configurações. (topic: core)
        - [forgepack-auth](https://github.com/forgepack/forgepack-auth): autenticação. (topic: auth)
        - [forgepack-security](https://github.com/forgepack/forgepack-security): JWT, OAuth, Login, Roles, Spring Security. (topic: security)
        - [forgepack-upload](https://github.com/forgepack/forgepack-upload). (topic: upload)
    - front-end `topic: library, backend`
        - [forgepack-ui](https://github.com/forgepack/forgepack-ui): botões, tabelas, formulários, modais
        - [forgepack-react](https://github.com/forgepack/forgepack-react): componentes react, hooks, providers
- PRODUCTS
    - forgepack-wms: WMS - Warehouse Management System. `topic: wms`
        - [wms-api](https://github.com/forgepack/wms-api)
        - [wms-web](https://github.com/forgepack/wms-web)
    - forgepack-pdv: registrar vendas, controlar o estoque e emitir notas fiscais. `topic: pdv`
        - [pdv-api](https://github.com/forgepack/pdv-api)
        - [pdv-web](https://github.com/forgepack/pdv-web)
    - forgepack-erp: compras, faturamento, financeiro. `topic: erp`
        - [erp-api](https://github.com/forgepack/erp-api)
        - [erp-web](https://github.com/forgepack/erp-web)
    - forgepack-tms: Gerencia a frota, calcula o custo do frete, define as melhores rotas e rastreia as entregas. `topic: tms`
        - [tms-api](https://github.com/forgepack/tms-api)
        - [tms-web](https://github.com/forgepack/tms-web)
    - [forgepack-loan](https://github.com/forgepack/forgepack-loan)
    - forgepack-signal:. `topic: signal`
        - [signal-api](https://github.com/forgepack/signal-api)
        - [signal-web](https://github.com/forgepack/signal-web)
    - forgepack-research:. `topic: research`
        - [research-api](https://github.com/forgepack/research-api)
        - [research-web](https://github.com/forgepack/research-web)
    - forgepack-stickers(FIFA|NFL|NBA). `topic: research`
        - [stickers-api](https://github.com/forgepack/stickers-api)
        - [stickers-web](https://github.com/forgepack/stickers-web)
    - forgepack-barcode: Leitura de código de barras. `topic: barcode`
        - [barcode-api](https://github.com/forgepack/barcode-api)
        - [barcode-web](https://github.com/forgepack/barcode-web)
    - forgepack-scrum: Gerenciamento de projetos em equipes. `topic: scrum`
        - [scrum-api](https://github.com/forgepack/scrum-api)
        - [scrum-web](https://github.com/forgepack/scrum-web)
    - forgepack-risk: Análise de risco. `topic: risk`
        - [barcode-api](https://github.com/forgepack/risk-api)
        - [barcode-web](https://github.com/forgepack/risk-web)
    - forgepack-weather: Registro de observações meteorológicas. `topic: weather`
        - [weather-api](https://github.com/forgepack/weather-api)
        - [weather-web](https://github.com/forgepack/weather-web)
- EXAMPLE (products)
    - [forgepack-example-barcode-api](https://github.com/forgepack/forgepack-example-barcode-api)
    - [forgepack-example-barcode-web](https://github.com/forgepack/forgepack-example-barcode-web)
- DOCS
    - [forgepack-site](https://github.com/forgepack/forgepack-site): site institucional
    - [forgepack-architecture](https://github.com/forgepack/forgepack-architecture): arquitetura, diagramas de dependência entre módulos

#### About → Topics
Buscando repositórios, ex.: `https://github.com/orgs/forgepack/repositories?q=topic:library`

#### Settings → Template repository
- forgepack-template-library: README, componentes relacionados, `pom.xml`/`package.json`, licença, CI básico.
- forgepack-template-product: api, web, libs consumidas.

Library:
Não têm interface para o usuário final.
Não fazem sentido isoladamente.
São publicados como bibliotecas ou módulos.
São dependências de outros repositórios.

<div align="center">
    Domínio: [forgepack.dev](https://forgepack.dev)
</div>
