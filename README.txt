# INTEGRAÇÃO COM O AVL

Arquivos necessários:
.avl -> configurações da geometria
.mass -> definição de unidades e distribuição de massa
.run -> parâmetros aerodinâmicos

Como o avl é baseado no sistema Unix é possível carregar os arquivos e comandos através de uma extensão .run, caso possua python em seu computador basta executar o arquivo AVL.py, caso não possua é possivel executar o aplicativo "avl.exe" e inserir os comandos manualmente no AVL para realizar testes.

::: Testando run cases direto no terminal do AVL ::: [com avl.exe]

load < path\arq.avl > -> carrega arquivo .avl no AVL 

mass < path\arq.mass > -> importa o arquivo de distribuição de massa 

case < path\arq.run > -> importa o run case 

? -> mostra opções de comandos 

oper -> carrega os run cases 

g -> plota a geometria 

x -> executar um run case [calcular a aerodinâmica] 

lo -> plotar geometria e ditrubuição de elevação 

t -> plota o plano de depressões [trefftz plane] 

enter -> volta um diretório 

ST < nome_arq.txt > -> gera um arquivo com as variáveis de estabilidade
