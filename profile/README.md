# qualidade-templates

Templates de qualidade de software para estudos e referência rápida.

## Repositórios

| Repositório | Ferramenta | Descrição |
|-------------|------------|-----------|
| [bruno-poc](https://github.com/qualidade-templates/bruno-poc) | Bruno | Collection `.bru` com request chaining e fluxo E2E ServeRest |
| [postman-poc](https://github.com/qualidade-templates/postman-poc) | Postman | Collection Native Git v3 com `pm.execution.runRequest`, CLI/CI |
| [insomnia-poc](https://github.com/qualidade-templates/insomnia-poc) | Insomnia | Collection YAML v5 com scripts e fluxo E2E ServeRest |
| [pactum-js-poc](https://github.com/qualidade-templates/pactum-js-poc) | PactumJS | Testes em TypeScript (DTO, factory, client) |
| [pytest-httpx-poc](https://github.com/qualidade-templates/pytest-httpx-poc) | Pytest + HTTPX | Testes em Python (DTO, factory, client) |

Todos cobrem o mesmo cenário na API [ServeRest](https://serverest.dev):

cadastrar usuário → login → cadastrar produto → adicionar ao carrinho.
