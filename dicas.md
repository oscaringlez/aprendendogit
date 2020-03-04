# Dicas

### Ordem das coisas

` 1. Adicionar (add) 2. Comentar (commit) 3. Enviar (push) `

## Configurações

### Setar usuário
    git config --global user.name "Leonardo Comelli"
### Setar email
    git config --global user.email leonardo@software-ltda.com.br
### Setar editor
    git config --global core.editor XXX
**Substitua XXX por:**
>Vim = vim
Atom = "atom --wait"
Sublime = "'C:/Program Files (x86)/sublime text 3/subl.exe' -w"
Visual code = "code --wait"
Notepad++ = "'C:/Program Files (x86)/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"

### Ignorar arquivos

#### Criar arquivo .gitignore (via bash)

    echo "" > .gitignore

> Veja algumas especificações no arquivo .gitignore


###Tags

**Criando uma tag leve**

    git tag vs-1.1
**Criando uma tag anotada**

    git tag -a vs-1.1 -m "Minha versão 1.1"

## Comandos avulsos
- Verificar situação do git » `git status`
- Verificar sua conexao » ` git remote -v `