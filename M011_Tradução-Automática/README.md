# Respostas 9.5.7:

## 1

Função para execução dos testes foi desenvolvida no notebook anexado.

**Conclusão**: Os resultados mostram que tanto o vocabulário da língua de origem quanto o da língua de destino crescem com o aumento dos exemplos, e ambos atingem um ponto de estabilização. No entanto, o vocabulário da língua de destino cresce mais rapidamente antes de se estabilizar em um tamanho maior, enquanto o da língua de origem cresce de forma mais gradual e atinge uma estabilização em um tamanho de vocabulário menor.


## 2

A tokenização em nível de palavra não é ideal para idiomas como o chinês e o japonês, pois eles não possuem delimitadores claros, como espaços, para separar palavras. Além disso, a segmentação de palavras nesses idiomas é mais complexa, já que os mesmos caracteres podem ter significados diferentes dependendo do contexto. Assim, tentar tokenizar por palavras em idiomas sem delimitadores claros pode resultar em uma interpretação incorreta do significado do texto, dificultando a precisão em tarefas de processamento de linguagem natural.

Referências:

Schuster & Nakajima (2012) - Japanese and Korean Voice Search: Os autores exploram os desafios da tokenização em línguas como o japonês e propõem técnicas como o uso de modelos de subpalavras (Byte Pair Encoding) para superar a falta de separadores explícitos. (Disponível em https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37842.pdf)
