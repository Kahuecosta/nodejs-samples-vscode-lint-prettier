###### Modelo de projeto Nodejs com padronização de código

- ESLint

  - Verificação de pardrão de escrita ECMAScript

- Prettier

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
