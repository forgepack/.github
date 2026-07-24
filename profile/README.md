# _ForgePack_

Bibliotecas e produtos reutilizáveis para back-end, front-end e infraestrutura.

produtos ou componentes (repositórios cujo objetivo é serem reutilizados por outros projetos)
O README.md de cada produto possui uma seção de links para componentes relacionados.

## Repositories
- FRAMEWORK (component)
    - INFRA (library, backend)
        - [forgepack-utils](https://github.com/forgepack/forgepack-utils): utilitários gerais
        - [forgepack-common](https://github.com/forgepack/forgepack-common): código compartilhado entre módulos
    - back-end (library, backend)
        - [forgepack-core](https://github.com/forgepack/forgepack-core): exceptions, DTOs, Helpers, Configurações
        - [forgepack-auth](https://github.com/forgepack/forgepack-auth): autenticação
        - [forgepack-security](https://github.com/forgepack/forgepack-security): JWT, OAuth, Login, Roles, Spring Security
        - [forgepack-inventory](https://github.com/forgepack/forgepack-inventory)
        - [forgepack-stock](https://github.com/forgepack/forgepack-stock): WMS - Warehouse Management System
        - [forgepack-loan](https://github.com/forgepack/forgepack-loan)
        - [forgepack-pdv](https://github.com/forgepack/forgepack-pdv): registrar vendas, controlar o estoque e emitir notas fiscais
        - [forgepack-erp](https://github.com/forgepack/forgepack-erp): compras, faturamento, financeiro
        - [forgepack-tms](https://github.com/forgepack/forgepack-tms): Gerencia a frota, calcula o custo do frete, define as melhores rotas e rastreia as entregas
        - [forgepack-sinal](https://github.com/forgepack/forgepack-sinal)
        - [forgepack-research](https://github.com/forgepack/forgepack-research)
    - front-end (library, backend)
        - [forgepack-ui](https://github.com/forgepack/forgepack-ui): botões, tabelas, formulários, modais
        - [forgepack-react](https://github.com/forgepack/forgepack-react): componentes react, hooks, providers
- PRODUCTS
    - stickers(FIFA|NFL|NBA)
        - [stickers-api](https://github.com/forgepack/stickers-api)
        - [stickers-web](https://github.com/forgepack/stickers-web)
    - barcode
        - [barcode-api](https://github.com/forgepack/barcode-api)
        - [barcode-web](https://github.com/forgepack/barcode-web)
    - scrum
        - [barcode-api](https://github.com/forgepack/scrum-api)
        - [barcode-web](https://github.com/forgepack/scrum-web)
    - risk
        - [barcode-api](https://github.com/forgepack/risk-api)
        - [barcode-web](https://github.com/forgepack/risk-web)
    - weather
        - [weather-api](https://github.com/forgepack/weather-api)
        - [weather-web](https://github.com/forgepack/weather-web)
- EXAMPLE (products)
    - [forgepack-example-barcode-api](https://github.com/forgepack/forgepack-example-barcode-api)
    - [forgepack-example-barcode-web](https://github.com/forgepack/forgepack-example-barcode-web)
- DOCS
    - [forgepack-site](https://github.com/forgepack/forgepack-site): site institucional
    - [forgepack-architecture](https://github.com/forgepack/forgepack-architecture): arquitetura, diagramas de dependência entre módulos

#### About → Topics
Buscando repositórios, ex.: https://github.com/orgs/forgepack/repositories?q=topic:library

#### Settings → Template repository
- forgepack-template-library: README, componentes relacionados, pom.xml/package.json, licença, CI básico
- forgepack-template-product: api, web, libs consumidas

Library:
Não têm interface para o usuário final.
Não fazem sentido isoladamente.
São publicados como bibliotecas ou módulos.
São dependências de outros repositórios.
