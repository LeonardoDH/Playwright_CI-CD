# 💻 Automação de Cadastro com Playwright

Este projeto realiza testes automatizados de cadastro no site [Automation Exercise](http://automationexercise.com) utilizando o framework **Playwright** com o padrão **Page Object Model (POM)**.

---

## 🚀 Tecnologias utilizadas

- [Playwright](https://playwright.dev/)
- [Faker](https://fakerjs.dev/) (para geração de dados fake)
- JavaScript (Node.js)

▶️ Como executar os testes
bash
Copiar
Editar
npx playwright test
Use npx playwright test --headed para ver o navegador rodando.

🔍 Sobre o teste
O teste realiza as seguintes ações:

Acessa o site

Preenche os dados de cadastro com informações geradas pelo Faker

Cria uma conta

Valida se o usuário está logado com sucesso (verificando a presença do item "Logout")