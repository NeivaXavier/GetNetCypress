
# Título do Projeto

Uma breve descrição sobre o que esse projeto faz e para quem ele é
Cypress Test GetNet
Este projeto é uma automação de teste de frontend utilizando Cypress. Ele inclui uma estrutura de testes organizada com o padrão Page Object Model (POM), scripts de limpeza de screenshots e configuração de variáveis de ambiente.

Estrutura do Projeto
arduino
Copiar código
projeto-get/
├── cypress/
│   ├── e2e/
│   │   └── getnet.cy.js
│   ├── fixtures/
│   ├── pages/
│   │   ├── CentralDeAjudaPage.js
│   │   └── CentralDeAjudaElements.js
│   ├── screenshots/
│   └── support/
│       ├── commands.js
│       ├── constants.js
│       └── e2e.js
├── scripts/
│   └── clearScreenshots.js
├── .env
├── cypress.config.js
└── package.json
Pré-requisitos
Node.js (versão 12 ou superior)
npm (gerenciador de pacotes do Node.js)
Cypress
Instalação
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/seu-repositorio.git
Navegue até o diretório do projeto:

bash
Copiar código
cd projeto-get
Instale as dependências:

bash
Copiar código
npm install
Configuração
Variáveis de Ambiente
Crie um arquivo .env na raiz do projeto e defina a URL base:

arduino
Copiar código
CYPRESS_BASE_URL=https://site.getnet.com.br
Limpeza de Screenshots
Um script foi incluído para limpar a pasta de screenshots antes de cada execução de teste. O script clearScreenshots.js está localizado na pasta scripts.

Executando os Testes
Abrir o Cypress Test Runner
Para abrir o Cypress Test Runner:

bash
Copiar código
npm run test
Executar os Testes em Modo Headless
Para rodar os testes em modo headless:

bash
Copiar código
npm run test:run

