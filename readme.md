# Passeio do Cavalo
![Alt Text](https://upload.wikimedia.org/wikipedia/commons/c/ca/Knights-Tour-Animation.gif)
![Alt Text](https://upload.wikimedia.org/wikipedia/commons/thumb/d/da/Knight%27s_tour_anim_2.gif/250px-Knight%27s_tour_anim_2.gif)

## Uma solução sequencial para o problema do passeio do cavalo.

[Problema do cavalo - Wikipédia](https://pt.wikipedia.org/wiki/Problema_do_cavalo) **__** [Knight's tour - Wikipedia](https://en.wikipedia.org/wiki/Knight%27s_tour) **__** [Passeio do Cavalo - RachaCuca](https://rachacuca.com.br/jogos/passeio-do-cavalo/)

* Os códigos devem ser feitos em **linguagem C padrão ANSI/ISO**, ou seja, devem ter somente funções e operações que possam ser compiladas em qualquer compilador de qualquer sistema operacional.
    * Para certificar que seu código-fonte está correto teste em compiladores do Windows e do GNU/Linux.

* Devem ser informados no programa dois inteiros *m* e *n* maiores que zero, representando o número de linhas e de colunas do tabuleiro, e uma posição inicial (L e C, onde 1 ≤ L,C ≤ n) representando a linha e a coluna inicial na qual o cavalo se encontra.

* No arquivo “cavalo.txt” deve haver a sequência do percurso do cavalo, mostrando o tabuleiro em cada movimento. O valor -1 significa casa vazia e um inteiro natural representa o número da jogada.
    * No final deste arquivo, deve-se escrever se uma solução foi ou não encontrada.

Para compilar:

`gcc cavaloSequencial.c -o cavaloSequencial.out`
