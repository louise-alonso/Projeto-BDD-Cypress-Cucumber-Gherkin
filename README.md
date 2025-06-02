# Projeto de Testes com Cypress, Cucumber e Gherkin

Este projeto implementa testes automatizados utilizando a metodologia BDD (Behavior Driven Development) com Cypress, Cucumber e Gherkin. O objetivo é garantir a qualidade do software através de testes que simulam o comportamento real do usuário, descritos em uma linguagem natural e compreensível.

## Sobre o Projeto

Este projeto foi desenvolvido utilizando três tecnologias principais:

1. **Cypress**: Framework moderno para automação de testes end-to-end
2. **Cucumber**: Ferramenta que implementa a metodologia BDD
3. **Gherkin**: Linguagem de especificação que permite escrever testes em formato legível

### Principais Funcionalidades
- Testes automatizados de interface do usuário
- Validação de fluxos de usuário
- Testes de regressão
- Relatórios de execução de testes
- Integração com CI/CD
- Documentação viva através dos cenários de teste

## Colaboradores

- Louise Afonso Lemos Alonso
- Maria Fernanda Lima Nogueira
- Calvin Almeida
- Tarcyla Kauanne

## Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/louise-alonso/Projeto-BDD-Cypress-Cucumber-Gherkin.git
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

## Executando os Testes

Para abrir o Cypress Test Runner:
```bash
npx cypress open
```

Para executar os testes em modo headless:
```bash
npx cypress run
```

## Estrutura do Projeto

```
cypress/
├── e2e/
│   ├── features/    # Arquivos .feature com os cenários em Gherkin
│   └── steps/       # Implementação dos passos dos testes
├── fixtures/        # Dados de teste
├── support/         # Arquivos de suporte
└── reports/         # Relatórios de execução
    ├── cucumber-html/
    └── cucumber-ndjson/
```

## Tecnologias Utilizadas

- Cypress (Framework de automação)
- Cucumber (Framework BDD)
- Gherkin (Linguagem de especificação)
- JavaScript/TypeScript
- Node.js
- npm/yarn

## Licença

Este projeto está sob a licença MIT. 
