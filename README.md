movimentação do cursor com h(esquerda) j(cima) k(baixo) l(direita)

inserção de texto onde o cursor esta!
Adicção de texto  para inserir o texto no final da linha

saindo do arquivo sem salvar com :q!
saindo do arquivo + salvar com :wq

deletando letra com x puta que pariuu
deletando palavra com dw na primeira letra da palavra nao sei
deletando frase com d$
---> 

movimento + apagar com d
d -> movimento
w -> exclui ate o inicio da proxima palavra
e -> exclui até o final da palavra atual
$ -> exclui toda linha. e vai até o ultimo caractere da frase

podemos utilizar o movimento com contadores 
contador + movimento 
ex:
2w -> pula duas palavras de onde o cursor esta
2e -> avança para o final da segunda palavra
0 -> para pular para a ultima linha

podemos utilizar o contados + movimento + deletar
ex:
d2w -> irá deletar as duas palavras de onde o cursor esta

podemos deleta toda a linha com dd e podemos utilizar o contador para deletar varias linhas como 2dd

podemos desfazer a ação com u e voltar todas as alterações da linha com U
e voltar para o estado antes do undo com ctrl + r (ctrl +y)

utilizar o p para colar o que deletou com o dd.
utilizar o y para copiar e o p para colar e o v para entrar no modo visual e selecionar os textos
 
altere algum caracteres com r com o cursor em cima do caracter errado exempla

altere até o final da palavra com change o ce exemplo abacisxa, colocar o cursor em i e digitar ce e terminar a palavra

podemos alterar até o final da linha com c$

podemos ver em linha estamos com ctrl+g, G para mover ate o final do arquivos e gg para o começo e o numero da linha + G para ir até a linha indicada

para buscar uma palavra digitamos /, para buscar mais usamos a letra n, e para buscar para trás N. e ctrl + o para voltar onde estava  

para buscar por frase ?

**Para rodar comandos **
- :! em seguida o comando que preferir.
- Ex: :!ls


