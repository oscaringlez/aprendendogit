# Aprendendo Github
- [x] Baixar -  [Git](http://git-scm.com/)
- [ ] Criar um projeto
- [ ] Abrir Git Bash
- [ ] Praticar 

## Etapas iniciais 

### Criar novo repositório

    git init

### Criar seu arquivo Readme (local)
    echo "# novorepositorio" >> README.md 

### Informar ao arquivo config adição de um arquivo (individual)
    git add README.md  

**ou adicionando todos arquivos**

    git add  

### Informar o que foi alterado nos arquivos ou adicionados
    git commit -m "sua observacao" 

## Conectar e enviar arquivos
### **Conectar via SSH:** _Para utilizar via ssh você precisará adicionar uma chave em [configurações](https://github.com/oscaringlez/aprendendogit/blob/master/Chaves.md)_
    git remote add origin “git@github.com:SEUUSUARIO/seurepositorio.git” 


### **Conectar via HTTP:**   _Em http será pedido seu usuario e senha github_
    git remote add origin https://github.com/SEUUSUARIO/seurepositorio.git” 



### Exibir os repositórios remotos
    git remote

    git remote -v

### Enviando os arquivos
    git push -u origin master 

**Os demais pushes não precisam dessa informação**

    git push 

### Atualizar repositório local de acordo com o repositório remoto
**Atualizar os arquivos no branch atual**

    git pull

**Buscar as alterações, mas não aplica-las no branch atual**
    
    git fetch


## Alterar arquivos e diretorios

### Adicionar um diretório em específico
    git add meu_diretorio

### Adicionar um arquivo em específico
	git add meu_arquivo.txt

### Mover arquivos (nome de arquivo ou pasta)
    git mv ORIGEM DESTINO

### Remover diretório
    git rm -r diretorio

### Remover arquivo
    git rm meu_arquivo.txt




### Desfazendo operações

**Desfazendo alteração local (working directory)**

Este comando deve ser utilizando enquanto o arquivo não foi adicionado na staged area.

    git checkout -- meu_arquivo.txt

**Desfazendo alteração local (staging area)**

Este comando deve ser utilizando quando o arquivo já foi adicionado na staged area.

    git reset HEAD meu_arquivo.txt

## Explicando visualmente

![explicacaovisual](https://user-images.githubusercontent.com/8312303/76108712-d972f680-5fb9-11ea-9db5-ec1e4d666636.png)





> **ARQUIVOS ACIMA SE COMPLEMENTAM - Branch, dicas e etc**
