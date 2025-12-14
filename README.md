# miniprojeto-API
Trabalho de pratica

O que são dependências npm do node.js
Dependências- são bibliotecas externas que não vêm com o Node.js e que o projeto precisa para funcionar.
No nosso projeto usamos principalmente:
    • express → servidor HTTP
    • sequelize → ORM (acesso ao banco)
    • sqlite3 → banco de dados
    • sequelize-cli → migrations e organização do banco

Abrir o terminal na pasta do projeto
Primeiro, é fundamental estar na pasta onde ficará o projeto.
Exemplo:
cd Documents/api-gestao-academica


Instalação das dependências do projeto
1️⃣ Abrir o terminal na pasta do projeto
Antes de tudo, é necessário estar na pasta raiz do projeto, onde ficará o arquivo package.json.

2️⃣ Inicializar o projeto Node.js
Executa-se o comando:

npm init -y

O que esse comando faz:
    • Cria o arquivo package.json
    • Define as configurações iniciais do projeto
    • Permite que o npm gerencie as dependências

3️⃣ Instalar as dependências principais
As dependências principais são aquelas necessárias para o funcionamento da aplicação.
🔹 Express

npm install express
Função: criar o servidor e gerenciar rotas HTTP.


🔹 Sequelize 

npm install sequelize
Função: realizar o mapeamento objeto-relacional (ORM) e acessar o banco de dados.


🔹 SQLite 

npm install sqlite3
Função: banco de dados utilizado no projeto.


Após esses comandos, o npm:
    • Cria a pasta node_modules
    • Atualiza o arquivo package.json
    • Gera o arquivo package-lock.json

4️⃣ Instalar dependência de desenvolvimento
Algumas bibliotecas são usadas apenas durante o desenvolvimento.
🔹 Sequelize CLI

npm install --save-dev sequelize-cli
Função: criar e executar migrations, models e seeders

5️⃣ Conferir se as dependências foram instaladas
Para verificar se deu tudo certo, use:

npm list --depth=0
As bibliotecas instaladas devem aparecer na lista.

6️⃣ Estrutura criada após a instalação
project/
├── node_modules/
├── package.json
├── package-lock.json
└── src/
7️⃣ Conclusão
As dependências do projeto foram instaladas utilizando o gerenciador de pacotes npm, garantindo a inclusão das bibliotecas necessárias para o desenvolvimento da API, como Express, Sequelize e SQLite, além do Sequelize CLI para gerenciamento do banco de dados.
