# Anotações sobre o GitHub
## Git &ne; GitHub
O Git é a ferramenta (software) usada para rastrear, salvar e restaurar o histórico de alterações do seu código. O GitHub é a plataforma online na nuvem que hospeda os seus repositórios Git.
## Como configurar o GitHub?
Temos duas formas com o git clone que usa quando você vai baixar pela primeira vez um repositório existente no GitHub ou em outro servidor ou o CCPACP quando já tem o clone na máquina e precisa só atualizar.
  ### git clone:
   Apenas escreva git clone URL_DO_REPOSITORIO.
  ### CCPACP:
   ⚠️Tem que fazer exatamente essa sequência se não vai dar erro!!!!
   
   git config --global/--local user.name 'nome'
   
   git config --global/--local user.email 'email'
   
   git Pull
   
   git add .
   
   git commit -m 'mensagem'
   
   Git push
   
   **Obs:** 
   - Use global quando for seu computador pessoal, já se for um que todos usam coloque --local, seu for seu computador não precisa colocar sempre os dois config já que já está salvo;
   - No user.name coloque o nome da sua conta;
   - git add o ponto tem que ter um espaço do add;
   - No git commit o nome do commit não pode ser pequeno demais nem grande demais tem que ser o necessário para você olhar e já saber o que foi feito;
## Principais comandos:
**explorer. -** entra na pasta em que o terminal está.

**cd "nome da pasta" -** entra na pasta específica dentro da pasta em que você está.

**seta para cima -** volta para os comandos que você já fez.

**clear -** limpa as pesquisas.

**code . -** abre no Vs code.

**git status -** vê o estado atual do git(se tem commit ou algo para fazer).

**git log -** vê seu histórico de alterações.

  - **git log --oneline** - resume o seu histórico de alterações aparecendo apenas o número da alterações e o nome do commit.

  - **git log --graph -** mostra o resumo do seu histórico com o caminho desenhando.
      Caminho:
      <img width="800" height="458" alt="git merge" src="https://github.com/user-attachments/assets/56eea144-d7be-4e1d-8350-251dbc947189" />
      <img src="LINK_DA_SUA_IMAGEM_AQUI" width="400">
      
      **Explicação**: O primeiro é o *master* onde iniciou o projeto, quando começar o deixe de lado e crie a *main*(linha principal) porque se ele de ruim ferrou. Os círculos são os *commits* e o conjunto desses commits se chama *braint*. 
      Como o --graph aparece:
    
      <img width="766" height="424" alt="git log graph" src="https://github.com/user-attachments/assets/c3c77628-b749-4ec2-87f0-69e47e985d57" />
      <img src="LINK_DA_SUA_IMAGEM_AQUI" width="400">
      
**git checkout ID_DO_COMMIT -** Viaja no tempo para a versão exata daquele commit (você pega o ID de 7 caracteres no git log --oneline).
**git switch main -** volta para a versão mais recente.

**git diff número da ID_ANTIGO e o ID_NOVO -** ele vai simplesmente comparar as duas versões.

            
