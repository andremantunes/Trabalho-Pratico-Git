# Trabalho-Pratico-Git
Trabalho final prático de GIT

# Indice
- [Grilo](#Grilo)
## Grilo

Incialmente Configurei o token para o projeto.
Depois adicionei as pastas principais do projeto e fiz commit para o github para a branch "main".

Criei a branch "Grilo" onde irei fazer as minhas alterações.

![alt text](assets/Grilo/grilo_branch.png)

### Merge

Começei por criar um script chamado  "script_grilo.py" que é um script para calcular a area de um triangulo.

![alt text](assets/Grilo/script_grilo.png)

Depois fiz git commit de todas as alterações e irei realizar o git merge para juntar a branch "Grilo" para o "main".
De seguida fiz o push para o github para a branch "main" 

![alt text](assets/Grilo/git_log.png)

![alt text](<assets/Grilo/git merge.png>)

### Rebase
Entrei na branch Grilo fiz as alterações ao README.md.

Primeiro fiz um commit onde alterei o README.md, depois voltei a branch main e fiz o rebase.
Basicamente o rebase server para fazer com que os commits "pareçam que venham da branch main" e não da branch Grilo

![alt text](assets/Grilo/rebase.png)

### Cherry-pick e Tags

Primeiro fiz um commit onde alterei o README.md e depois fiz outro commit onde corrigi o bug do "script_grilo.py"

Adicionei tambem uma tag ao commit onde corri o bug onde meti "tag 1.0"

![alt text](assets/Grilo/tag.png)

Depois voltei para a branch main e fiz cherry-pick apenas do commit "Bug fix in script_grilo.py" 

![alt text](<assets/Grilo/git cherrypick.png>)

## Abreu

Inicialmente criei um script em python em que o erro se situa na linha 6 em que o numero2 está registado como 0, sendo impossivel a divisão.

![alt text](assets/Abreu/img_script_abreu.png)

De seguida criei uma branch, nomeadamente "branch_abreu" onde vou começar a trabalhar.

![alt text](assets/Abreu/img_branch_abreu.png)

Dei git merge para juntar a branch "abreu_branch" para o main".

![alt text](assets/Abreu/img_merge_abreu.png)

Corrigi o script 

![alt text](assets/Abreu/script_corrigido.png)

Vou criar este texto de modo a mudar o conteúdo do ficheiro e fazer o primeiro commit para dar inicio ao cherry pick

![alt text](assets/Abreu/primeiro_commit.png)

Śegundo commit

![alt text](assets/Abreu/segundo_commit.png)

De seguida tive um erro em que tive que mudar para a branch "main" para fazer o cherry-pick

![alt text](assets/Abreu/mudar_main.png)

Mudei então para a main

![alt text](assets/Abreu/main.png)

E fiz a cherry-pick

![alt text](assets/Abreu/git_cherry_pick.png)

Fiz git status

![alt text](assets/Abreu/git_status.png)

Git rebase

![alt text](assets/Abreu/rebase.png)

Dei push para o Git Hub

![alt text](assets/Abreu/push.png)

Dei push para enviar as informações para o nosso github.

![alt text](assets/Abreu/img_push_abreu.png)

E enviei as informações de novo a partir do comando git push.

![alt text](assets/Abreu/img_push_abreu.png)

