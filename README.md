# Repositório de estudos Git e Github :speech_balloon:
Por meio da formação GitHub Certification, pude  aprender cada vez mais sobre o universo de possibilidades que é o GitHub e os principais conceitos e ferramentas foram incluídos neste repositório. Além disso, a linguagem markdown está sendo amplamente uilizada neste arquivo para exemplificar mais um ensinamento.

### >> Aprendizados da formação :heart_eyes_cat: <<

#### 1. Criar repositório local e adicioná-lo ao nosso GitHub - remoto;
Para isso foi preciso criar uma pasta localmente e depois criar um repositório remoto com o mesmo nome. Depois de adicionar arquivos e realizar alterações locais, utilizou-se os comandos abaixo para atualizar o repositório criado. 
```
git init 
git add .
git commit -m "Primeiro commit"
git branch -M main
git remote add origin (link do repositório remoto)
git push -u origin main
```

#### 2. Clonar um repositório remoto para o nosso computador local;
Na pasta de projetos, utilizou-se o comando `git clone` (link do repositório local) para clonar o repositório para a máquina local.

#### 3. Fazer alterações >> Adicionar | Commitar | Enviar arquivos;
Comandos utilizados:
```
git status
git add .
git commit -m "Realizando alterações"
git push origin main
```

#### 4. Criar uma nova Branch e Merge;
Para saber em qual branch estamos e quais temos: `git branch`
Para criar uma branch: `git branch nome_da_branch`
Para navegar entre as branchs: `git checkout nome_da_branch`
Para atrelar alterações feitas em uma ramificação para a principal ou qualquer outra: `git merge`

#### 5. Criar nosso primeiro Fork;
Entre o repositório que deseja realizar o fork e clique na aba de fork e automaticamente o projeto irá ficar nos seus repositórios.

#### 6. Realizar um Pull Request 
Depois de fazer um fork no projeto que deseja colaborar, 
realize as alterações que prefirir e faça um pull request descrevendo as alterações no projeto.
Após isso, o proprietário do projeto recebe o pull request e dá um merge pull request se aceitar as modificações feitas.

#### 7. Conceitos
- **Tags**: Uma referência específica a um commit, geralmente usada para marcar versões estáveis.
- **Releases**: Utiliza uma tag como base e é uma forma mais organizada de marcar as versões, pode-se adicionar uma descrição da versão com arquivos e imagens. Mantém o controle do código com detalhes.
- **GitHub Gist**: Repositório Git mínimo, geralmente usado para compartilhar pedaços de código e é totalmente colaborativo.
- **Issues (Problemas)**: Rastreamento de tarefas, melhorias ou bugs em um repositório. São usadas para dar sugestões e colaborar com outros projetos utilizando fotos, descrições e arquivos.Quando o proprietário solucionar o problema apontado pela issue, é utilizada a palavra reservada 'fixed' seguida por sequilha e o id da issue para que a issue seja fechada durante o commit com as alterações.
- **Wiki**: Fazem parte dos repositórios e há uma sessão onde podemos hospedar as documentações. Podemos usar o wiki do repositório para compartilhar conteúdos ao decorrer do nosso projeto. Com as wikis podemos fornecer documentação adicional.
> [!NOTE]
> Para fazer referência ao pull request, uma issue ou um commit é necessário usar '#' seguido pelo ID do objeto.