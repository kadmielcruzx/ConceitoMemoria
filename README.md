# ConceitoMemoria

# Ram
sigla "RAM" vem de "Random Access Memory", ou "memória de acesso aleatório", indicando a principal característica da memória RAM, que é o fato de permitir o acesso direto a qualquer um dos endereços disponíveis e de forma bastante rápida.
Ao carregar um programa, ele é lido no HD (ou outra mídia de armazenamento) e é transferido para a memória RAM, para só então ser executado pelo processador. A memória RAM oferece tempos de acesso brutalmente mais baixos que o HD e trabalha com taxas de transferência muito mais altas, mas possui a desvantagem de perder os dados armazenados quando o micro é desligado, daí a necessidade de salvar os arquivos periodicamente.


# rom
ROM é uma sigla em inglês que se refere ao termo “Read Only Memory” ou “Memória de Apenas uma Leitura”. Trata-se de uma memória de semicondutor que facilita a conservação da informação que pode ser lida, mas que não pode ser destruída. Diferentemente da memória RAM, os dados contidos em uma memória ROM não são destruídos nem perdidos em caso de interrupção da energia elétrica, por isso, é chamada de “memória não volátil”.

... Artigo http://queconceito.com.br/memoria-rom

Basicamente, essa é a função da memória ROM: oferecer dados apenas para leitura. Normalmente, a ROM é utilizada para armazenar firmwares, pequenos softwares que funcionam apenas no hardware para o qual foram desenvolvidos e que controlam as funções mais básicas do dispositivo.

# swap
Memória Swap é uma memória "virtual". Significa que ela não tem um suporte físico como a memória RAM. A memória virtual criada pelo sistema operacional, utilizando o espaço livre no disco rígido, de forma a complementar a memória RAM. A memória swap deverá ser uma memória sobresalente, em situações em que a memória RAM não é suficiente para armazenar dados de uma determinada aplicação.

# memoria paginada
A paginação permite que o programa possa ser espalhado por áreas não contíguas de memória. Com isso, o espaço de endereçamento lógico de um processo é dividido em páginas lógicas de tamanho fixo e a memória física é dividida em páginas com tamanho fixo, com tamanho igual ao da página lógica. Nisso, o programa é carregado página a página, cada página lógica ocupa uma página física e as páginas físicas não são necessariamente contíguas. O endereço lógico é inicialmente dividido em duas partes : um número de página lógica (usado como índice no acesso a tabela de páginas, de forma a obter o número da página física correspondente) e um deslocamento dentro da página.

A transferência das páginas de processo podem ser transferidas para a memória por demanda, levando apenas o que é necessário para a execução do programa ou por paginação antecipada, onde o sistema tenta prever as páginas que serão necessárias à execução do programa.
