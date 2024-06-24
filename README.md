# Repositório de estudos Git e Github
Desafio para testar conhecimentos em github

#### 1. Criar repositório local e adicioná-lo ao nosso GitHub - remoto;
Para isso foi preciso criar uma pasta localmente e depois criar um repositório remoto com o mesmo nome. Depois de adicionar arquivos e realizar alterações locais, utilizou-se os comandos abaixo para atualizar o repositório criado. 
- git init 
- git add .
- git commit -m "Primeiro commit"
- git branch -M main
- git remote add origin (link do repositório remoto)
- git push -u origin main

#### 2. Clonar um repositório remoto para o nosso computador local;
Na pasta de projetos, utilizou-se o comando git clone (link do repositório local) para clonar o repositório para a máquina local.

#### 3. Fazer alterações >> Adicionar | Commitar | Enviar arquivos;
Comandos utilizados:
- git status
- git add .
- git commit -m "Realizando alterações"
- git push origin main

#### Criar uma nova Branch e Merge;
Para saber em qual branch estamos e quais temos: git branch
Para criar uma branch: git branch nome_da_branch
Para navegar entre as branchs: git checkout nome_da_branch
Para atrelar alterações feitas em uma ramificação para a principal ou qualquer outra: git merge

