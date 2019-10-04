# Jantar dos filosofos

Formulado e resolvido por Dijkstra em 1965, este problema de sicronização tornou-se um dos mais conhecidos. 

Desde então, todos os que inventaram mais uma primitiva de sincronização sentiram-se obrigados a demonstrar quão maravilhosa é a nova primitiva exibindo quão elegantemente ela soluciona o problema do jantar dos filósofos.

O código mostrado aqui foi retirado do livro Sistemas Operacionais Modernos 3ª edição, com modificações para mostrar momentos onde há dois filosofos comendo simultâneamente.

compile com usando: $ gcc -o filosofos filosofos.c -pthread
execute com: $ ./filosofos