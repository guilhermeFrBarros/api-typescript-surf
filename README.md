# API de Melhores Locais para Surfar 🏄‍♂️

Este projeto é uma API construída com Node.js, Express e TypeScript que fornece informações sobre os melhores locais para surfar.

## Começando 🚀

Estas instruções fornecerão uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento e teste.

### Pré-requisitos 📋

O que você precisa para instalar o software:

- Node.js
- npm

### Instalação 🔧

1. Clone o repositório
   ```bash
   git clone https://github.com/guilhermeFrBarros/api-typescript-surf.git

Instale as dependências
npm install

Compile o TypeScript
npm run build

Inicie o servidor
npm start

Uso 🖥️
Após iniciar o servidor, você pode fazer solicitações para http://localhost:3000 para acessar a API.

Testes ⚙️
Para executar os testes automatizados para este sistema, use:

npm test

Construído com 🛠️
Node.js - Ambiente de execução JavaScript
Express - Framework web
TypeScript - Superset JavaScript com tipos estáticos
Autores ✒️
Seu Nome - Trabalho Inicial - SeuUsuario
Licença 📄
Este projeto está sob a licença MIT - veja o arquivo LICENSE.md para detalhes.


Lembre-se de substituir "seuusuario" e "seuprojeto" pelos nomes de usuário e projeto corretos no GitHub. Além disso, você pode querer adicionar mais detalhes sobre como usar a API, quais rotas estão disponíveis, etc. 😊



como mudar para main
Procurando por como mudar para main git

Gerando respostas para você…

Para mudar para a branch main no Git, você pode seguir os seguintes passos:

Renomeie sua branch local (se ela se chamar master, por exemplo):
git branch -m master main

Mude a branch rastreada:
git fetch -p origin
git branch -u origin/main main

Mude a branch local principal:
git remote set-head origin -a

Opcionalmente, remova a branch master, local e remotamente:
git branch -D master
git push origin :master

Estes comandos irão renomear sua branch local master para main, mudar a branch rastreada para origin/main, definir main como a branch principal local e, opcionalmente, remover a branch master1.

Se você quiser que o Git crie a branch main por padrão sempre que iniciar um novo repositório local, você pode adicionar a seguinte configuração:

git config --global init.defaultBranch main

Isso fará com que o Git crie a branch main por padrão sempre que você executar git init2.
