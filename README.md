# Conteúdo
- [Conteúdo](#conteudo)
- [Notas sobre este curso](#notas-sobre-este-curso)
- [Introdução](#introducao)
    - [O que é o Bash?](#o-que-e-o-bash)
    - [Relembrando alguns comandos](#relembrando-alguns-comandos)
- [Editores](#editores)
- [Tarefas para casa](#tarefas-para-casa)
- [Desafio](#desafio)

# Notas sobre este curso

Este programa foi criado para ensinar o básico de programação em bash para profissionais de TI que conhecem um pouco sobre o terminal do linux, mas não conehcem programação. O conteúdo disponível em Todo o curso pode ser distríbuído, desde que seja mencionado o fonte original, neste Github (https://github.com/fc-shell-scripting).

# Introdução
Bem vindo ao curso de shell scripting, para quem ainda não sabe programar. Este curso parte do princípio que você tem alguma experiência em uso do terminal do linux, mas ainda não conseguiu começar a fazer seus próprios programas usando bash (ou outro interpretador). Antes de iniciar a criar um script e ver ele ser executado, vamos repassar alguns comandos do terminal, e entender como o interpretador funciona ao ser aberto um prompt novo.

Não se preocupe se alguns termos forem confusos ou estranhos no começo. Isso é normal!

> Se deseja Instalar Uma máquina Virtual para realizar testes e poder fazer todos os scripts sem medo de causar danos permanentes a lguma máquina ou servidor, você pode ver o meu [post](http://blog.czetta.com/Criando-uma-maquina-virtual/) onde explico como montar uma vm do ubuntu no vmware workstation player (gratuito).

## O que é o Bash?
Bash é um interpretador de comandos que são executados. Existem diversos interpretadores diferentes, e noeste curso vamos ver o bash, por ser o que geralmente vem instalado em ambientes linux. Cada interpretador tem suas particularidades e diferenças. Se o seu Interpretador não for o bash, você pode encontrar diferenças nas sintaxes e formas de execução.
O papel do interpretador é fazer o computador agir de acordo com o que foi escrito pelo programador. O programador pode usar palavras chave para executar determinadas tarefas, e pode chamar outros programas para criar um programa mais robusto. Pense no shell como uma caixa de lego cheio de peecinhas que podem ser encaixadas. Nessa metáfora o papel do programador é montar as peças para que elas formem o programa desenhado pelo programador. Os comandos que você já usa no terminal fazem parte deste pacote de peças que o interpretador pode usar. No início vai parecer que você está digitando os comandos que faria manualmente, mas com o tempo eles vão ficar mais complexos

## Relembrando alguns comandos
Os comandos desta lista são alguns dos mais comuns, e você já deve usar a maioria deles no dia a dia. Se ainda não os usa, provavelmente há algo que você faz hoje que pode ser simplificado e agilizado. Outros comandos funcionam como root, e por este motivo, pode ser que você não tenha conhecimento sobre ele. por este motivo, recomendo que você crie uma máquina virtual para poder testar e brincar com a linha de comando e scripting:

- ls
    - Lista arquivos e diretórios
- cd
    - Faz a navegação, ou seja, permite a troca de diretórios
- pwd
    - Printa o diretório onde o usuário está
- man
    - Abre o manual de um programa
    - Exemplo: man ls
- mkdir
    - Cria diretórios
- touch
    - Cria arquivos vazios>
- rm
    - Remove arquivos e diretórios
- date
    - Mostra a data
    - Permite editar a data do sistema
- cal
    - Mostra o calendário
- which
    - Identifica o caminho de um comando
- cat
    - Concatena os arquivos (de cima para baixo)
- tac
    - Concatena  o arquivos (de baixo para cima)
- head
    - Carrega as 10 primeiras linhas do arquivo
- tail
    - Carrega as 10 últimas linhas do arquivo
- login
    - Abre a tela de login, solicitando usuário e senha
- logout
    - Finaliza a sessão do usuário
- exit
    - Sai do shell atual (não finaliza a sessão, se houver um shell pai)
- reboot
    - Reinicia o servidor
- halt
    - Desliga o servidor
- grep
    - Usado para filtrar linhas, usando expressão regular
- ln
    - Cria links no sistema
- clear
    - Limpa o terminal
- sleep
    - Aguarda n segundos
- usleep
    - Aguarda n milisegundos
- write
    - Escreve para o terminal de um usuário
- more
    - Faz a paginação do resultado
- less
    - Faz a paginação como o more, mas premite alguns recursos a mais, como pesquisa e voltar as linhas
- join
    - Une dois arquivos com um campo em comum
- wc
    - Realiza a contagem de linhas, colunas e caracteres de um arquivo
- nl
    - Realiza a contagem de linhas de um arquivo
- expand
    - Troca tabs por espaços
- tr
    - Faz a substituição de caracteres de um arquivo ou texto
- sort
    - Ordena os dados do arquivo
- uniq
    - Executado após o sort, remove os campos duplicados
- cut
    - Seleciona e "corta" o texto passado
- diff
    - Mostra as diferenças entre arquivos
- tar
    - Empacota arquivos
    - Este comando, por padrão não compacta, apenas empacota os arquivos
- split
    - divide um arquivo em arquivos menores
- gzip/gunzip
    - Compacta/Descompacta arquivos

Além dos programas listaso, existem diversos outros que podem ser usados. Vale a pena gastar um tempo para identificar se existe um comando que resolva seu problema de forma rápida e eficiente!

# Editores

No linux, existem diversos editores de texto diferentes. Alguns são mais simples de usar e outros são mais complexos e robustos. Neste curso iremos usar o edito "VIM", que permite a execução de comandos e vem instalado em diversas distribuições linux.
Outras possíveis opções são: pico, emacs, e mcedit. Cada um deles tem sua própria forma de trabalhar, e permitem a interação de formas diferentes.

# Tarefas para casa

Pense em Tarefas do seu dia a dia que possam ser automatizadas.
Isso será importante para as próximas aulas.

# Desafio

Escolha alguns dos problemas da tarefa para casa, e coloque passo a passo como este processo é feito hoje. Ex: Se você compacta arquivos manualmente todo dia, escreva os comandos que são executados, e o que você precisa saber para poder executar os comandos.
