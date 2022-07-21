# Santander Bootcamp Fullstack Developer - Roteiro de Cursos

## MODULO I     Conteúdo de Abertura

### Curso 2 - Introdução ao Git e ao GitHub

1. Introdução ao Git

- Entendendo o que é Git e sua importância

2. Navegação via command line interface e instalação

- Comandos básicos para um bom desempenho no terminal

- Realizando a instalação do GIT

3. Entendendo como o Git funciona por baixo dos panos

- Tópicos fundamentais para entender o funcionamento do Git

- Objetos internos do Git 

- Chave SSH e Token

4. Primeiros comandos com Git

- Iniciando o Git e criando um commit: 

  > - Um repositório nada mais é que uma área de trabalho criada para se trabalhar um arquivo/programa/algoritmo
  > - Este repositório é criado localmente, ou seja, no computador pessoal ou do trabalho

  - **git init:** *inicializa/cria um repositório dentro de uma pasta local, onde vão ser trabalhados os objetos do Git*
  - **git add *:** *adiciona um arquivo desse repositório criado para a área de stage, indicando que este está pronto para ser commitado* 
  - **git config --global user.email "virgiliocezarcarvalho@gmail.com":** *configura o email que vai estar vinculando a máquina com o GitHub, de forma que todos os arquivos commitados terão esse atributo*
  - **git config --global --unset user.email:** *exclui o email que está configurado; geralmente usado quando é feito com um diferente do que está configurado no GitHub; então, executa-se novamente o comando anterior*
  - **git config --global user.name "virgiliocezar":** *configura o nome/apelido que vai estar vinculando a máquina com o GitHub, de forma que todos os arquivos commitados terão esse atributo*
  - **git config --global --unset user.name:** *exclui o nome que está configurado; geralmente usado quando é feito com um diferente do que está configurado no GitHub; então, executa-se novamente o comando anterior*
  - **git commit -m "*texto explicativo do objeto*":** *cria-se um objeto contendo o arquivo e alguns atributos de identificação do usuário, como o nome, tamanho, código*
  - **git status:** *verifica o status do(s) arquivo(s), confirmando que todos estão commitados e prontos para serem empurrados ao GitHub*

5. Ciclo de vida dos arquivos no GiT

- Passo a passo no ciclo de vida

6. Introdução ao GitHub

- Trabalhando com o GitHub

  > - E para que o(s) arquivo(s) criado(s) possa(m) ser visualizado(s) por outros Dev's, ele(s) deve(m) ser enviado(s) para o GitHub
  > - Para isso, deve-se criar também um repositório lá no GitHub, chamado de repositório remoto (é criado automaticamente um tipo de URL)
  > - E então vincular ambos os repositórios, o remoto e o local 

  - **git remote add *origin URL*:** *adiciona/vincula o repositório remoto ao repositório local; a palavra origin é apenas um apelido para que, em comandos que precisem dessa URL, não seja necessário digitá-lo inteiro, mas apenas o apelido***
  - **git remote -v:** *consulta a lista de repositórios cadastrados no repositório local**
  - **git push *origin master*:** *empurra o arquivo commitado para o Git, para que ele possa ser visualizaddo e/ou manipulado por outros Dev's; onde origin é o apelido dado para a URL do repositório remoto do GitHub e master é a branch criada do repositório local*

7. Resolvendo conflitos

- Como os conflitos acontecem no GitHub e como resolvê-los

  > - Os conflitos ocorrem quando um mesmo arquivo está sendo manipulado por dois ou mais usuários, e ambos editam a mesma linha de código
  > - Em certo momento, um deles vai atualizar o GitHub com a sua edição
  > - Com isso, as versões que todos os outros usuários estiverem usando estarão obsoletas; e quando tentarem atualizar no GitHub, o conflito vai ser acusado pela plataforma
  > - Para resolver o conflito, o usuário que se deparou com o conflito vai ter que, ele mesmo e manualmente, fazer a verificação no arquivo atualizado e unificar ou não suas alterações
  > - E por último, não seria um conflito, mas sim uma aplicação do que o GitHub propõe, que é a manipulação de vários códigos de diversos Dev's, os códigos abertos
  > - Para isso, é necessário baixar o código/repositório do GitHub para o próprio computador pessoal ou de trabalho, para que esse código possa ser trabalhado/estudado. Diz-se que esse repositório vai ser *clonado* no seu computador

  - **git pull *origin master*:** *puxa o arquivo do GitHub para a sua máquina, ou seja, do remoto para o local, para que seja feita a verificação das alterações manualmente pelo usuário*
  - **git add *:** *para adicionar o agora arquivo editado para a área de staging, para que ele possa ser commitado*
  - **git commit -m "texto explicativo do objeto":** *commita o arquivo para que ele possa ser novamente empurrado para o GitHub*
  - **git push *origin master*:** *e por fim, empurra o arquivo editado para o GitHub, com todas as alterações feitas, ou não, por todos os usuários*
  - **git clone *URL*:** *clona-se o repositório tal qual ele está no GitHub, podendo ser manipulado com o objetivo de agregar conhecimento*
  - **ls:** *faz-se a consulta do conteúdo da pasta para onde o clone foi colocado*
  - **cd *repositório clonado*:** *entra-se no repositório clonado para constatar que no seu conteúdo existe um arquivo ".git"*
  - **ls -a:** *lista os arquivos ocultos da pasta, como é o caso do ".git" do repositório clonado; todo repositório criado ou clonado, possui um arquivo ".git", que é oculto*

### Curso 3 - Desafio de projeto

1. Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso

- Introdução e apresentação do projeto

- Git e GitHub: Relembrando algumas coisinhas

- Desafio de projeto