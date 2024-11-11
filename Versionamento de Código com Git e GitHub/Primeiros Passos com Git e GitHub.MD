# Primeiros Passos com Git e GitHub

**Do primeiro repositório á manipulação de branches.**

## Criando e Clonando Repositórios

**Existem duas formas de obter um repositório Git na sua máquina:**

- Transformando um diretório local que não esta sob controle de versão, num repositório Git;

- Clonando um repositório Git existente.

## Clonando um Repositório

**Para clonar um repositório no Git, acesse seu repositório no GitHub e siga os próximos passos:**

**1 -** Em "**Code**", copie o código **HTTPS** ou **SSH** (**a depender de como autenticou sua conta**) do repositório no GitHub;

**2 -** Abra o **GitBash**, insira o comando "***`git clone`***" e cole o conteúdo copiado para cloná-lo.

**Exemplo:** 

***`git clone https://github.com/username/nome-do-repositório.`***

## Criando um Repositório Remoto

**Acesse a sua conta do GitHub, clique no "+" no canto superior direito, e em "new repository"**.

**1 -** Insira um nome (**obrigatório**), e a descreção (**opcional**);

**2 -** Coloque uma breve descrição sobre o projeto, essa etapa é opicional;

**3 -** Defina se o acesso será público ou privado;

**4 -** Escolha como deseja inicializar seu repositório (**se quiser vazio, deixe as opções desmarcadas**);

**5 -** Clique em "**Create Repository**", e pronto!

## Salvando Alterações no Repositório local

**Como criar um** ***`commit`***:

**1 -** Adicione o conteúdo que deseja inserir no ***`commit`***:

***`git add`***

**2 -** Crie um ***`commit`*** e adicione uma menssagem descritiva:

***`git commit -m Exemplo`***

## Desfazendo Alterações no Repositório local

**1 -** Como alterar a mensagem do último ***`commit`***

***`git commit --amend`***

**Alterando mensagem sem abrir o editor:**

***`git commit --amend -m Exemplo`***

**2 -** Como desfazer um ***`commit`***

***`git reset`***

***`git reset --soft`***

***`git reset --mixed`***

***`git reset --hard`***

## Enviando Alterações para o Repositório Remoto

**Como enviar alterações do repositório local para o remoto:**

***`git push`***

"**Puxar**" as alterações do repositório remoto para o local (**busca e mescla**)

***`git pull`***

## Trabalhando com *`Breanches`*

De maneira simplista, uma ***`branch`*** (**em tradução "Ramo"**), é uma ramificação do seu projeto.

- É um ponteiro móvel para um ***`commit`*** no histórico do repositório;

- Quando você cria uma nova ***`branch`*** a partir de outra existente, a nova se inicia apontando para o mesmo ***`commit`*** da ***``branch*** que estava quando foi criada.

***`git branch`***

- Troca de ***`branch`*** e criar uma nova:

***`git checkout -b nova-branch`***

- Deletar uma ***`branch`***:

***`git branch -d nome-da-branch`***

- Ver o ultimo ***`commit`*** de cada ***`branch`***:

***`git branch -v`***


