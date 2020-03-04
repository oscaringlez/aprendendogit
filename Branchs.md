## Branchs (ramificações)

### Criando um novo branch
    git branch nomedobranch

### Alterar diretorio (branch ou master)
    git checkout -b nomedobranch

**Voltar para o branch principal (master)**

    git checkout master

### Adicionar e comentar
    git add *
    git commit -m "novo branch"

### Enviar arquivos  
    git push -u nomedobranch 

### Remover 

**Local**

    git branch -d nomedobranch 
**Remoto**    

    git push origin:bug-123



### Resolver merge entre os branches
    git merge bug-123
>Para realizar o merge, é necessário estar no branch que deverá receber as alterações. O merge pode automático ou manual. O merge automático será feito em arquivos textos que não sofreram alterações nas mesmas linhas, já o merge manual será feito em arquivos textos que sofreram alterações nas mesmas linhas.

### Listar branches
    git branch