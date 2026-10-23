# 🎭 Playwright Learning



> Um repositório focado no aprendizado e na construção de testes automatizados de ponta a ponta (E2E) modernos, rápidos e confiáveis utilizando o framework Playwright.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Você tem o **Git** instalado para clonar o repositório.
* Você tem o **Node.js** e um gerenciador de pacotes (como npm ou yarn) instalados.
* Você tem um editor de código (como o VS Code) devidamente configurado.

## 🚀 Instalando o Playwright Learning

Para configurar o ambiente de automação de testes na sua máquina, siga estas etapas:

**Linux, macOS e Windows:**

```bash
# Clone o repositório
git clone https://github.com/leonard0antonio/playwright-learning.git

# Acesse a pasta do projeto
cd playwright-learning

# Instale as dependências do projeto
npm install

# Instale os navegadores necessários para o Playwright (Chromium, Firefox e WebKit)
npx playwright install

```

## ☕ Usando o Projeto

Para executar os testes automatizados e visualizar os relatórios, utilize os comandos abaixo no seu terminal:

```bash
# Executa todos os testes em modo headless
npx playwright test

# Executa os testes com a interface gráfica do Playwright (UI Mode)
npx playwright test --ui

# Gera e abre o relatório HTML dos últimos testes executados
npx playwright show-report

```

> **Nota:** Navegue pela pasta raiz e de testes para consultar os cenários E2E, interações com elementos da página e asserções aplicadas aos projetos de estudo.

## 📫 Contribuindo para o Projeto

Contribuições são o que fazem a comunidade open source ser um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

Para contribuir:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature ou Teste (`git checkout -b feature/NovoCenarioDeTeste`)
3. Faça o Commit de suas mudanças seguindo o padrão **Conventional Commits** (`git commit -m 'test: adiciona automação de fluxo de login'`)
4. Faça o Push para a Branch (`git push origin feature/NovoCenarioDeTeste`)
5. Abra um Pull Request
