# Atividade Prática do Curso de TADS - IFPR Cascavel - Programação WEB II

Prática para API node com rotas para GET e POST

# Requisitos da API Criada:
Node JS
sudo apt install nodejs
node --version = 12.22.9

Yarn
npm install --global yarn
yarn --version = 1.22.19

Curl
sudo apt install curl
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -

Insomnia
https://insomnia.rest/download

# Bibliotecas:
yarn add express
npm i nodemon -D	/permite recomplar automaticamente o servidor ao alterar o código (npm run dev)
npm i express		/Framework para o desenvolvimento de aplicações utilizando o Node e gerenciamento de rotas
npm install uuid	/Utilizado para gerar ID único para cada aluno cadastrado

# Como funciona:
- Os arquivos do repositório (zip) devem estar em uma única pasta
- Abrir pasta via VSCODE e o arquivo index.js. Iniciar o servidor pelo terminal vscode usando: npm run dev
- Com o servidor iniciado, deve-se utilizar o Insomnia para realizar os cadastros através de requisições 
- Junto ao diretório existem imagens das requisições com Cadastro, Busca e Atualização dos dados pelo Insomnia
