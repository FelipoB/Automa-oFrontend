# Frontend Automation with Cypress

Este repositório contém minhas automações de frontend utilizando Cypress para os projetos **Cypress Heroes** e **Real World App**. O objetivo principal é garantir a qualidade e a funcionalidade dessas aplicações através de testes automatizados.

## Índice

- [Visão Geral](#visão-geral)
- [Cypress Heroes](#cypress-heroes)
  - [Descrição](#descrição)
  - [Estrutura dos Testes](#estrutura-dos-testes)
  - [Como Executar](#como-executar)
- [Real World App](#real-world-app)
  - [Descrição](#descrição-1)
  - [Estrutura dos Testes](#estrutura-dos-testes-1)
  - [Como Executar](#como-executar-1)
- [Conclusão](#conclusão)

## Visão Geral

Este repositório contém testes automatizados de frontend utilizando **Cypress**. Meu objetivo é aprimorar a qualidade das aplicações através de testes end-to-end. O **Cypress** é uma ferramenta robusta que permite escrita, execução e depuração de testes para aplicações web de forma eficiente.

---

## Cypress Heroes

### Descrição

O **Cypress Heroes** é um projeto de exemplo utilizado para testar funcionalidades de uma aplicação baseada em heróis. O projeto demonstra como escrever testes de interface para interações comuns e fluxos de usuário.

### Estrutura dos Testes

Os testes estão organizados da seguinte forma:

- `cypress/integration/` - Contém os arquivos de teste.
- `cypress/fixtures/` - Contém dados estáticos utilizados nos testes.
- `cypress/support/` - Contém comandos customizados e configurações.

### Como Executar

1. Clone o repositório:
   ```sh
   git clone https://github.com/SeuUsuario/cypress-heroes.git
   cd cypress-heroes
   ```
2. Instale as dependências:
   ```sh
   npm install
   ```
3. Execute os testes:
   ```sh
   npx cypress open
   ```
   ou para execução em modo headless:
   ```sh
   npx cypress run
   ```

---

## Real World App

### Descrição

O **Real World App** é um projeto mais complexo que simula uma aplicação de banco digital. Utilizei **Cypress** para automatizar testes de diversas funcionalidades críticas, garantindo que a aplicação funcione conforme esperado.

### Estrutura dos Testes

Os testes estão organizados da seguinte forma:

- `cypress/integration/` - Contém os arquivos de teste.
- `cypress/fixtures/` - Contém dados estáticos utilizados nos testes.
- `cypress/support/` - Contém comandos customizados e configurações.

### Como Executar

1. Clone o repositório:
   ```sh
   git clone https://github.com/SeuUsuario/real-world-app.git
   cd real-world-app
   ```
2. Instale as dependências:
   ```sh
   npm install
   ```
3. Execute os testes:
   ```sh
   npx cypress open
   ```
   ou para execução em modo headless:
   ```sh
   npx cypress run
   ```

---

## Conclusão

Meus estudos com **Cypress** me permitiram criar automações robustas para garantir a qualidade das aplicações frontend. Se você tiver alguma dúvida ou sugestão, fique à vontade para abrir uma *issue* ou entrar em contato.

FelipoB
