# Chave SSH

1. Abra Git Bash

2. Substitua seu email do github abaixo

` ssh-keygen -t rsa -b 4096 -C "seuemail@dominio.com.br" `

3. De **enter** e depois vai ser perguntado a senha, não aconselho. 

> A senha será criada em: (/c/Users/you/.ssh/id_rsa.pub)

4. Copie e cole com ajuda de bloco de notas os numeros e letras do arquivo acima

5. Vá até [Configurações Github](https://github.com/settings/keys) e clique em New SSH

6. Feito..quando for se conectar escolha SSH em seu repositorio
