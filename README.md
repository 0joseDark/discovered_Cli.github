# discovered_Cli.github
em windows baixar https://cli.github.com/´ , e instalar o msi
 commands_Cli.github
 eu preferir usar um ficheiro para login  https://cli.github.com/manual/gh_auth_login
 assim pode gerar a chave em https://github.com/settings/tokens
 na pasta documentos, onde está a pasta  githud fazer o ficheiro token.txt com a chave dentro
 abrir o power shell do windows
# Start interactive setup
$ gh auth login

# Authenticate against github.com by reading the token from a file
$ gh auth login --with-token < token.txt

# https://cli.github.com/manual/

# gh auth status

PS C:\Users\jose\Documents\GitHub> gh auth login
? What account do you want to log into? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Paste an authentication token
Tip: you can generate a Personal Access Token here https://github.com/settings/tokens
The minimum required scopes are 'repo', 'read:org', 'workflow'.
? Paste your authentication token: ****************************************
- gh config set -h github.com git_protocol https
✓ Configured git protocol
unable to find git executable in PATH; please install Git for Windows before retrying
PS C:\Users\jose\Documents\GitHub> gh gist ls --public
no gists found
PS C:\Users\jose\Documents\GitHub> gh auth status
github.com
  ✓ Logged in to github.com account 0joseDark (keyring)
  - Active account: true
  - Git operations protocol: https
  - Token: ghp_************************************
  
  eu preferir usar o GitHub Desktop https://desktop.github.com/download/ 
  
resumo de aguns dos comandos basicos do Cli.githu: 
Clonar um repositório do GitHub para o seu computador local:
# gh repo clone owner/repository-name
Exemplo:
# gh repo clone 0joseDark/browser
Criar um novo repositório
# gh repo create my-new-repo --public
ou
# gh repo create my-private-repo --private
Listar repositórios
# gh repo list username
Exemplo:
# gh repo list 0joseDark
...etc

