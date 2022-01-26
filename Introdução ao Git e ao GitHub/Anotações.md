[links para download do Git](https://git-scm.com/downloads)

O git Bash é um terminal extendido para otimizar o uso do Git

# Alguns comandos básicos e essenciais para não esquecer no Git! 

## Definir usuário

git config --global user.name "name" **(Mesmo usado no GitHub)**

## Definir e-mail

git config --global user.email ""email" **(Mesmo usado no GitHub)$$

# Repositório Local

## Novo criar recurso	

git init

## Verificar estado dos arquivos/diretórios

git status

## Adicionar todos os arquivos 

git add .

# Comitar arquivo/diretório

## Comitar vários arquivos

git commit meu_arquivo.txt meu_outro_arquivo.txt

## Comitar informando mensagem

git commit meuarquivo.txt -m "minha mensagem de commit"

# Remover arquivo/diretório

## Remover arquivo

git tm meu_arquivo.txt

## Remover pasta

git rm -r diretorio

# Enviar arquivos/diretórios para o remoto

## O primeiro push 

git push -u origin master

# Demais push 

git push