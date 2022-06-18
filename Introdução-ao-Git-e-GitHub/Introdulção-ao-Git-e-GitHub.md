 # Introdução ao Git
 #### O que é o Git:

 Git é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

 #### O que é o Git:

 Git é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

# Navegação via command line interface e instalação

#### Navegação e Interação:

 Para navegar pelo Git que tem interface CLI por linhas de comando, é necessário alguns tipos de comandos específicos, EXP: dir, ls, mkdir, git init, etc...

#### Instalação: 

Para instalar o Git é necessário acessar o site do Git na WEB. [Download Git](https://git-scm.com/downloads).

# Entendendo como o Git funciona por baixo dos panos

O Git pode ser usado em todo e qualquer projeto que tenha arquivos de diferentes tipos, podendo ser código, texto, imagens, vídeos, áudios, entre outros. O objetivo principal é permitir o controle de histórico e versão desses projetos, melhorar o trabalho em time e o fluxo de trabalho, proporcionar a segurança dos seus arquivos, usando o ssh o git cria um codigo sha1 para cada blop, tree e commit dentro do seu repositório.

# Primeiros comandos com Git

Os comandos são a única forma de trabalhar com o Git, sendo assim cada um exerce uma função diferente e variando de sistema para sistema.
Alguns comandos estão nessa [lista](https://gist.github.com/leocomelli/2545add34e4fec21ec16).

# Ciclo de vida dos arquivos no Git

![Sem título](https://user-images.githubusercontent.com/107049157/174415439-776f36d3-b524-4146-9170-60f59d4256f9.jpg)

 A imagem acima já explica por si só o ciclo de um arquivo no Git, o arquivo ao ser adicionado a pasta do repositório ele é untrackad, pois o Git ainda não tem conhecimento dele, mas ao aplicar o comando git add ele automaticamente reconhece o arquivo como unmodifield, assim gerando seu sha1, e ao modificarmos o arquivo ele já reconhece o outro sha1 alterando seu estagio para modifield, e aplicando outro git add ele já muda de estagio para staged esperando ser commitado, após essa ação e volta para unmodifield, para ser modificado novamente.

# Introdução ao GitHub

#### O que é o GitHub:

O **GitHub** é o maior repositório de dados compartilhado do mundo, com 28 milhões de usuários atualmente. É uma plataforma majoritariamente usada por desenvolvedores, pois permite uma hospedagem prática de código-fonte e arquivos em nuvem.

#### Como se cadastrar:

Basta acessar o [site](https://github.com/signup).

#### Como criar uma repositório:

Depois de cadastrado basta ir no perfil>your repositories>new e pronto, agora é só adicionar um nome, colocar uma descrição, deixa-lo publico ou privado e escolher criar um README.md ou não.

# Resolvendo Conflitos

Os conflitos no Git,a grosso modo, são quando dois usuários do mesmo arquivo modificam mas mesma linha e a deixa diferente  e ao commitarem em horários diferentes e dar o push o git vai perceber a alteração e informar o conflito, mas para resolver basta dar um git pull para que o Git reveja qual o arquivo "prioritário" ou de certa forma "correto" e permitir o commit novamente e o push para o GitHub.

