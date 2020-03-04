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

## Ignorar arquivos

#### Criar arquivo .gitignore (via bash)

    echo "" > .gitignore

> Veja algumas especificações no arquivo .gitignore

## Clonar

#### Clonar um repositório remoto já existente
    git clone git@github.com:USUARIO/REPOSITORIO.git

## Tags

**Criando uma tag**

    git tag NOMEDATAG

**Criando uma tag anotada**

    git tag -a NOMEDATAG -m "Seu comentario"

**Remover local e remoto**

    git tag -d NOMEDATAG
    git push --delete NOMEDATAG

## Comandos avulsos
- Verificar situação do git » `git status`
- Verificar sua conexao » ` git remote -v `
- Ver log de alterações » `git log`
- Setar url local -> remoto » `git remote set-url origin git://url`
- Adicionar arquivo e commitar » `git commit -am "add tudo"`
