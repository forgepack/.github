<div align="center">
    # _ForgePack_
</div>
    
Bibliotecas e produtos reutilizáveis para back-end, front-end e infraestrutura.

Produtos e/ou componentes (repositórios cujo objetivo é serem reutilizados por outros projetos)
O README.md de cada produto possui uma seção de links para componentes relacionados.

## Repositories
- FRAMEWORK (component): Repositórios que não têm interface para o usuário final, não fazem sentido isoladamente e são publicados como bibliotecas/módulos — dependências de outros repositórios.
    - INFRA ([library, backend](https://github.com/orgs/forgepack/repositories?q=topic:library,backend))
        -	[forgepack-utils](https://github.com/forgepack/forgepack-utils): utilitários gerais
        -	[forgepack-common](https://github.com/forgepack/forgepack-common): código compartilhado entre módulos
    - back-end (library, backend)
        -	[forgepack-core](https://github.com/forgepack/forgepack-core): exceptions, DTOs, Helpers, Configurações
        -	[forgepack-auth](https://github.com/forgepack/forgepack-auth): autenticação
        - [forgepack-security](https://github.com/forgepack/forgepack-security): JWT, OAuth, Login, Roles, Spring Security
    - front-end (library, backend)
        - [forgepack-ui](https://github.com/forgepack/forgepack-ui): botões, tabelas, formulários, modais
        - [forgepack-react](https://github.com/forgepack/forgepack-react): componentes react, hooks, providers

## Products
 
| Produto | API | Web | Topic | Descrição |
|---|---|---|---|---|
| WMS | [wms-api](https://github.com/forgepack/wms-api) | [wms-web](https://github.com/forgepack/wms-web) | `wms` | Warehouse Management System |
| PDV | [pdv-api](https://github.com/forgepack/pdv-api) | [pdv-web](https://github.com/forgepack/pdv-web) | `pdv` | Registrar vendas, controlar estoque e emitir notas fiscais |
| ERP | [erp-api](https://github.com/forgepack/erp-api) | [erp-web](https://github.com/forgepack/erp-web) | `erp` | Compras, faturamento, financeiro |
| TMS | [tms-api](https://github.com/forgepack/tms-api) | [tms-web](https://github.com/forgepack/tms-web) | `tms` | Gerencia a frota, calcula custo de frete, define rotas e rastreia entregas |
| Stickers | [stickers-api](https://github.com/forgepack/stickers-api) | [stickers-web](https://github.com/forgepack/stickers-web) | `stickers` | Álbum de figurinhas multi-tema (FIFA, NFL, NBA como dados/conteúdo, não repos separados) |
| Barcode | [barcode-api](https://github.com/forgepack/barcode-api) | [barcode-web](https://github.com/forgepack/barcode-web) | `barcode` | Leitura de código de barras |
| Scrum | [scrum-api](https://github.com/forgepack/scrum-api) | [scrum-web](https://github.com/forgepack/scrum-web) | `scrum` | Gerenciamento de projetos em equipes |
| Risk | [risk-api](https://github.com/forgepack/risk-api) | [risk-web](https://github.com/forgepack/risk-web) | `risk` | Análise de risco |
| Weather | [weather-api](https://github.com/forgepack/weather-api) | [weather-web](https://github.com/forgepack/weather-web) | `weather` | Registro de observações meteorológicas |
| Signal | [signal-api](https://github.com/forgepack/signal-api) | [signal-web](https://github.com/forgepack/signal-web) | `signal` | — |
| Research | [research-api](https://github.com/forgepack/research-api) | [research-web](https://github.com/forgepack/research-web) | `research` | — |

- EXAMPLE (products)
    - [forgepack-example-barcode-api](https://github.com/forgepack/forgepack-example-barcode-api)
    - [forgepack-example-barcode-web](https://github.com/forgepack/forgepack-example-barcode-web)
- DOCS
    - [forgepack-site](https://github.com/forgepack/forgepack-site): site institucional
    - [forgepack-architecture](https://github.com/forgepack/forgepack-architecture): arquitetura, diagramas de dependência entre módulos

### About → Topics
Buscando repositórios, ex.: `https://github.com/orgs/forgepack/repositories?q=topic:library`

### Settings → Template repository
- forgepack-template-library: README, componentes relacionados, `pom.xml`/`package.json`, licença, CI básico
- forgepack-template-product: api, web, libs consumidas

Library:
Não têm interface para o usuário final.
Não fazem sentido isoladamente.
São publicados como bibliotecas ou módulos.
São dependências de outros repositórios.

<div align="center">

**Made by [forgepack](https://github.com/forgepack)**
**Domain [forgepack.dev](https://forgepack.dev)**

</div>
