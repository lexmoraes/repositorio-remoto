# Repositório remoto
Repositório para prática dos conceitos e comandos do GIT
<div>
<a href="https://app.capacities.io/home/1cfd4619-aff1-4a3f-a08d-51625aa5fa9b" target="_blank">Minhas notações sobre conceitos de versionamento clicando aqui</a>.
</div>

### Passos para utilização do projeto.

- Passo 1: Crie as credenciais do github;
  1. Usuário;
      ```bash
      git config --global user.name "Nome-de-usuário"
      ```
  2. Email;
      ```bash
      git config --global user.email nome@example.com
      ```
- Passo 2: Crie o repositório local.
- Passo 3: Inicialize o monitoramento do repositório;
  ```bash
  git init
  ```
- Passo 4: Conectar repositório local com repositório remoto;
  ```bash
  git remote add origin link_do_repositorio
  ```

### Execuções mais utilizadas:

- Criar uma nova branch afim de finalizar uma task sem alterar a branch principal *(main/master)*
  ```bash
  git branch nome_da_nova_brach
  ```
- Checar qual branch está selecionada para desenvolver:
  ```bash
  git branch
  ```
- Sair da branch atual e entrar em outra:
  ```bash
  git checkout nome-da-branch-para-entrar
  ```
- Mandar uma branch local para a remota:
  ```Bash
  git push -u origin nome_da_branch
  ```
- Considerar mudanças feitas em um arquivo modificado;
  ```bash
  git add nome_do_arquivo.extensão
  ```
- Considerar todas as modificações do diretório;
  ```bash
  git add .
  ```
- Verificar modificações não commitadas;
  ```bash
  git status
  ```
- Confirmar modificações com commit;
  ```bash
  git commit -m "mensagem de commit aqui"
  ```
- Mesclar branches (recomendado estar na branch que originou a branch a ser mesclada):
  ```bash
  git merge nome_da_branch_para_mesclar
  ```
- Atualizar a branch selecionada com todo o conteúdo da *main/master*:
  ```bash
  git rebase
  ```
- Visualizar todos os commits feitos nas branch;
  ```bash
  git log
  ```
- Verificar quais branchs estão atualizadas ou desatualizadas;
  ```bash
  git fetch
  ```
- Pegar atualizações remotas para a local selecionada;
  ```Bash
  git pull
  ```
  
