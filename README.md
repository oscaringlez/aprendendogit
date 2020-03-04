# Aprendendo Github
 Baixar -  GIT >> [http://git-scm.com/](http://git-scm.com/)
- Ir na pasta do projeto e abrir Git Bash - _clicando com direito do mouse_

## Etapas iniciais 

### Criar novo repositório

git init

### Criar seu arquivo Readme (local)
 echo "# aprendendogit" >> README.md 

### Informar ao arquivo config adição de um arquivo
 git add README.md  

**ou**

 git add * informa todos arquivos 

### Informar o que foi alterado nos arquivos ou adicionados
 git commit ###m "sua observacao" 

## Conectar e enviar arquivos
### **Conectar via SSH:** _Para utilizar via ssh você precisará adicionar uma chave em [configurações](https://github.com/oscaringlez/aprendendogit/blob/master/Chaves.md)_
git remote add origin “git@github.com:SEUUSUARIO/seurepositorio.git” 


### **Conectar via HTTP:**   _Em http será pedido seu usuario e senha github_
git remote add origin https://github.com/SEUUSUARIO/seurepositorio.git” 

## Enviando os arquivos
git push ###u origin master 

### Os demais pushes não precisam dessa informação
git push 

## Clonar 
git clone git@github.com:USUARIO/REPOSITORIO.git 

### Baixar (servidor -> local)
1. Conecte ao repositorio
2. Commit a alteração
git pull 


> ARQUIVOS ACIMA SE COMPLEMENTAM - Branch, dicas e etc




