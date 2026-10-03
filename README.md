# Lucas Barros Bonine

**QA Automation | Testes de software | Java e JavaScript**

Sou desenvolvedor backend Java com experiência profissional e estou direcionando minha carreira para **QA Automation**. Curso uma pós-graduação em Automação de Testes de Software e venho aplicando esse aprendizado em testes de interfaces web, APIs e integração contínua.

Minha experiência em desenvolvimento é a base técnica dessa transição: compreender a implementação, as regras de negócio e a persistência de dados ajuda a definir o que testar e a investigar falhas. Meu foco atual é aprofundar a automação e a qualidade dos testes, com prática documentada nos repositórios abaixo.

## Automação na prática

Os projetos reúnem exercícios de cursos, trabalhos da pós-graduação e estudos sobre aplicações didáticas. Os forks são identificados para preservar o contexto de origem.

### Testes web e integração contínua

[pgats-automacao-web-2026](https://github.com/lucasbonine/pgats-automacao-web-2026) — projeto da pós-graduação com testes end-to-end em **Cypress e JavaScript** no site Automation Exercise.

- Cenários de cadastro, login com credenciais válidas e inválidas, logout e rejeição de e-mail já cadastrado, incluindo exclusão da conta no fluxo de login válido.
- Geração de dados com **Faker** e uma factory de usuários, com preparação de contas no `beforeEach` para os cenários que exigem cadastro prévio.
- Helpers reutilizáveis para cadastro e login, mantendo as validações de mensagens, visibilidade e navegação nos testes.
- Seletores CSS e configuração da URL do ambiente por **dotenv**, com execução interativa ou pelo terminal.

[pgats-ci](https://github.com/lucasbonine/pgats-ci) — estudo da pós-graduação a partir de um fork.

- Testes end-to-end com **Playwright e JavaScript**, incluindo fluxos de navegação e validação de restrições de altura.
- **GitHub Actions** com execução manual, encadeamento de workflows e pipeline que reúne análise estática, testes unitários e E2E.
- Relatórios HTML e JUnit, artefatos de execução, screenshots de falhas e traces nas novas tentativas.
- Testes com **Jest**, coleta de cobertura e configuração de testes de mutação com **Stryker**.

### Testes de APIs

[payment-control](https://github.com/lucasbonine/payment-control) — fork de uma API didática usado para praticar testes **GraphQL** com **Mocha, Chai e Supertest**, em Node.js.

- Mutations de login e cadastro de funcionários, com cenários de sucesso e erro.
- Requisições autenticadas com JWT, campos obrigatórios, tipos inválidos e regras de negócio, como CPF duplicado e salário negativo.
- Validação do conteúdo das respostas e dos erros GraphQL, além do status HTTP.
- Helpers reutilizáveis, preparação e limpeza dos dados de teste.

[gestao-de-alunos-api](https://github.com/lucasbonine/gestao-de-alunos-api) — fork utilizado no estudo de testes **REST**, com Mocha, Chai e Supertest. A suíte de autenticação verifica login válido, retorno de token e rejeição de senha incorreta.

### Automação com Java

[testes-automatizados-selenium-alura](https://github.com/lucasbonine/testes-automatizados-selenium-alura) — testes de aceitação com **Selenium WebDriver, JUnit e Maven**, organizados em **Page Objects**. Os cenários incluem login, acesso a páginas restritas e cadastro de leilões com dados válidos e inválidos.

[ponto-inteligente-api](https://github.com/lucasbonine/ponto-inteligente-api) — projeto de estudo com **Spring Boot**, que conecta desenvolvimento backend e testes: serviços com **Mockito**, endpoints com **MockMvc** e validações de persistência em repositórios com JUnit.

## Práticas que venho desenvolvendo

- Seleção de cenários positivos, negativos e de valores-limite.
- Organização dos testes em preparação, execução e verificação (**Arrange, Act, Assert**).
- Separação entre cenários, interação com páginas e funções auxiliares.
- Uso de mocks para controlar dependências e de hooks para preparar e encerrar os testes.
- Coleta de cobertura e estudo de testes de mutação para avaliar a qualidade das verificações.

Os exercícios [trabalho-conclusao-progamacao](https://github.com/lucasbonine/trabalho-conclusao-progamacao) e [desafio-prog](https://github.com/lucasbonine/desafio-prog) complementam essa prática com testes unitários em **JavaScript, Mocha e assert do Node.js**, cobrindo regras de pagamento e login.

## Base em desenvolvimento

Minha trajetória profissional está no backend Java. Nos projetos de estudo, essa base aparece em APIs REST com **Spring Boot**, persistência com **JPA/Hibernate** e organização de dependências com **Maven**. O [spring-boot-3-api-restful](https://github.com/lucasbonine/spring-boot-3-api-restful) também reúne validação de dados e autenticação JWT com Spring Security.

## Formação

- Bacharelado em Ciência da Computação — Universidade Federal de Pelotas (UFPel).
- Pós-graduação em Automação de Testes de Software — em andamento.

## Contato

[LinkedIn](https://www.linkedin.com/in/lucasbonine/) · [lucasbonine@live.com](mailto:lucasbonine@live.com)
