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

#### Conceitos
*Tags*: Uma referência específica a um commit, geralmente usada para marcar versões estáveis.
*Releases*: Utiliza uma tag como base e é uma forma mais organizada de marcar as versões, pode-se adicionar uma descrição da versão com arquivos e imagens. Mantém o controle do código com detalhes.
*GitHub Gist*: Repositório Git mínimo, geralmente usado para compartilhar pedaços de código e é totalmente colaborativo.
*Issues (Problemas)*: Rastreamento de tarefas, melhorias ou bugs em um repositório. São usadas para dar sugestões e colaborar com outros projetos utilizando fotos, descrições e arquivos.Quando o proprietário solucionar o problema apontado pela issue, é utilizada a palavra reservada 'fixed' seguida por sequilha e o id da issue para que a issue seja fechada durante o commit com as alterações.
*Wiki*: Fazem parte dos repositórios e há uma sessão onde podemos hospedar as documentações. Podemos usar o wiki do repositório para compartilhar conteúdos ao decorrer do nosso projeto. Com as wikis podemos fornecer documentação adicional.
