###### Integração Continua

- GCP Cloud Build com acionador configurado
  - Configuração
    - Dispara a partir de uma branch no Github (ex: google-dev ou google-prod)
    - Executa os comandos do cloudbuild.yaml
- Permissões (IAM)
  - Usuário
    - [ID]@cloudbuild.gserviceaccount.com
  - Papeis
    - Conta de serviço do Cloud Build
    - Usuário da conta de serviço
    - Administrador do Cloud Run

###### Garantia de padrão de código

- Combinação de ESLint, Prettier, .editorconfig e .vscode/settings.json
- Para o EditorConfig funcionar é necessario instalar a extensão no VSCode e o package do NPM - NPM: npm install -g editorconfig
