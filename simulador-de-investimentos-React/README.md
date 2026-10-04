# simulador-de-investimentos-React
simulador de investimentos React
Projeto de Aplicação React / Vite

Este projeto é uma aplicação web desenvolvida como parte da atividade acadêmica, utilizando Vite para empacotamento e execução rápida do ambiente de desenvolvimento.

📋 Sobre o Projeto e Comportamento Esperado

A aplicação tem como objetivo demonstrar a estruturação de um projeto moderno com React e Vite.

Comportamento Esperado:

Carregamento rápido de componentes e interface reativa.

Navegação ou interação funcional conforme os componentes desenvolvidos na pasta src/.

Atualização em tempo real das alterações feitas no código (Hot Module Replacement - HMR) durante o modo de desenvolvimento.

🚀 Como Executar o Projeto

Siga as instruções abaixo para clonar, instalar e executar a aplicação localmente.

Pró-requisitos

Certifique-se de ter o Node.js instalado em sua máquina.

1. Clonar o Repositório

git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO


2. Instalar as Dependências

Para instalar todas as dependências necessárias do projeto, execute:

npm install


3. Executar o Servidor de Desenvolvimento

Para iniciar o servidor local de desenvolvimento com Hot Reload:

npm run dev


Após executar o comando, o terminal exibirá o endereço local (geralmente http://localhost:5173/). Abra o link no seu navegador para interagir com a aplicação.

4. Gerar a Build de Produção

Para compilar e otimizar o projeto para ambiente de produção:

npm run build


Os arquivos otimizados serão gerados na pasta /dist.

📂 Estrutura do Projeto

.
├── public/          # Arquivos estáticos
├── src/             # Código-fonte da aplicação (componentes, estilos, logic)
├── index.html       # Ponto de entrada HTML
├── package.json     # Gerenciamento de dependências e scripts
└── vite.config.js   # Configurações do Vite
