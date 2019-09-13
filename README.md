###### Modelo de projeto Nodejs com padronização de código e configuração de Docker e Google Cloud build

- ESLint

  - Instalar extensão do ESLint no VSCode
  - Verificação de pardrão de escrita ECMAScript

- Prettier
  Instalar extensão do Prettier no VSCode

  - Auxilia o ESLint na padronização

- Editorconfig

  - Configura tipo de identação, tamanho de identação, encode de arquivo e etc..
  - Necessário a instalação da extensão no VSCode
  - Rodar o comando npm install -g editorconfig
  - .editorconfig: Arquivo de configuração

- VSCode

  - vscode/settings.json: Configurações do editor do VSCode
    - eslint.autoFixOnSave roda a verificação de lint e prettier no arquivo
  - vscode/launch.json: Configurações de debug do VSCode

    - preparado para debugar junto com o nodemon configurado no package.json

  - Docker

    - Dockerfile configurado ara rodar um container com Nodejs e estartando a aplicação

  - Google Cloud Build
    - cloudbuild.yml: Configuração para buildar a aplicação

###### Após tudo configurado devemos rodar o npm install ou yarn
