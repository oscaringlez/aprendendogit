## Branchs (ramificações)

### Criando um novo branch
    
**Local**    

    git branch nomedobranch

**Remoto**

    git push origin nomedobranch


### Alterar diretorio (branch ou master)
    git checkout nomedobranch

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

    git push origin :nomedobranch



### Resolver merge entre os branches
    git merge nomedobranch
>Para realizar o merge, é necessário estar no branch que deverá receber as alterações. O merge pode automático ou manual. 

**Caso seja merge entre master e nomedobranch**

    git checkout master
    git merge nomedobranch


>O merge automático será feito em arquivos textos que não sofreram alterações nas mesmas linhas, já o merge manual será feito em arquivos textos que sofreram alterações nas mesmas linhas.

### Listar branches
    git branch