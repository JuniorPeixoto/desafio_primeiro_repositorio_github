### Adiciona nome usuario na configuracao local 
git config --local user.name "<nome_usuario>"

### Adiciona email na configuracao local
git config --local user.email "<email>"

### Remove propriedade da configuracao local
git config --local --unset <propriedade>

### Adiciona arquivo a area de staging
git add <nome do arquivo>

### Adiciona todos os arquivos na area de staging
git add .

### Realiza um commit 
git commit -m "<messagem do commit>"

### Remove um arquivo da area de staging 
git restore --staged <arquivo>

### Remove o ultimo commit mantendo mudancas na area de staging 
git reset --soft HEAD~1


### Remove o ultimo commit descartando todas as mudancas 
git reset --hard HEAD~1

### Mostra o ultimo commit 
git log --oneline --graph --decorate -5

### Mostra o status atual
git status

### Mostra mudancas em staged
git diff --staged

### Mostra mudancas em unstaged
git diff
