# Inicializando git Local

Primeiro confira se o git está instalado:



```bash
git --version
```
Segundo é necessário abrir uma pasta do git, e logo após criar e abrir uma nova pasta

```bash
cd Documents
```

```bash
mkdir notas
```

```bash
cd notas
```
Terceiro passo é Criar uma conta.

```bash
git config --global user.name "seunome"
```

```bash
git config --global user.email "seuemail"
```

o Quarto passo é criar um reporsitório.

```bash
git init
```

Após você pode abrir o vscode.

```bash
code .
```

Portanto na proxíma aula vamos aprender:

```bash
git status
```

```bash
git add <filename ou.>
```

```bash
git git restore --staged <filename ou.>
```

```bash
git branch <branchname>
```

```bash
git checkout <branchname>
```

```bash
git checkout -b <branchname>
```

```bash
git commit -m "<description>"
```

```bash
git push
```

```bash
git branch -D <branchname>
```

```bash
git fetch
```

```bash
git pull
```

19/06
Primeiro precisamos usar o código abaixo para ver se há alguma chave ssh.
```bash
ls -al ~/.ssh
```
e logo depos usar este código mais o email que uso para criar uma chave.
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

Depois tive que usar esses dois códigos para iniciar um agente e adicionar a chave ssh no agente.
```bash
eval "$(ssh-agent -s)"
```
```bash
ssh-add ~/.ssh/id_ed25519
```

Também usamos esse código para copiar a chave ssh.
```bash
clip < ~/.ssh/id_ed25519.pub
```

Então decidimos adicionar a chave ao GitHub com a chave que acabamos de copiar,para adicionar precisamos ir as configurações e ir em SSG and GPG keys e conseguimos colar lá.

Também testamos a conexão com este código, e acaba pedindo se temos certeza , logo digitamos yes.
```bash
ssh -T git@github.com
```


Logo depois abrimos o vs code com o git bash, e usamos o código abaixo para abrir as pastas ou arquivos que estam na pasta "notas".
```bash
ssh -T git@github.com
```


E usando com o código abaixo usamos para fazer nosso primeiro commit, com o nome do commit em "description" no exemplo.
```bash
git commit -m "<description>"
```

Depois conseguimos logar no GitHub e publicamos o commit.
---------------------------------------------------------------------------------------------------------------------------
21/08/23

Nestas últimas duas aulas aprendemos como o GitHub fornece suporte para sites estáticos gratuitamente.  
Primeiro acessamos o repositório e acessamos os settings, e logo após entramos em pages, selecionamos a branch para publicação e salvamos.

Baixamos o repositório e utilizamos o ssh com o comando: 
```bash
git clone (aqui o SSH)
```

Inicialimos o projeto react com este comando:
```bash
npx create-react-app
```

Também adicionamos o arquivo index.html ao projeto

Logo em seguida commitamos a página




```bash
```

```bash
```

```bash
```

```bash
```

```bash
```
