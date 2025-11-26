4-BIT-ADDER: <br>
Entradas: O 4-bit adder recebe 8 entradas, sendo elas -> 2 números de 4 bits.<br>
Saidas: Gera uma saída de 4 bits podendo ter um carry out também.<br>
Explicação: O 4-bit adder é um circuito feito para somar dois números binários de 4 bits.<br>
<br>
HALF SUBTRACTOR: <br>
Entradas: O half subtractor possui 2 entradas, representando o A e o subtraendo B.<br>
Saídas: Gera 2 saídas: a diferença (Diff) e o borrow out (B_out).<br>
Explicação: O half subtractor é um circuito que realiza a subtração entre dois bits. Ele indica a diferença entre A e B e se foi necessário "pegar emprestado" (borrow) de um bit mais significativo.<br>
<br>
FULL SUBTRACTOR:<br>
Entradas: O full subtractor recebe 3 entradas: A, B e o borrow in (B_in), que vem da subtração anterior.<br>
Saídas: Fornece 2 saídas — a diferença (Diff) e o borrow out (B_out).<br>
Explicação: O full subtractor é um circuito que realiza a subtração  de três bits. <br>

2-BIT MUX:<br>
Entradas: Um MUX de 2 bits recebe 4 entradas de dados (A, B, C, D), cada uma representando um possível valor que pode ser selecionado. Além disso, possui 2 entradas de seleção (C1 e C2), que determinam qual dos 4 dados será enviado para a saída.<br>
Saída: Gera 1 saída, que corresponde exatamente ao valor da linha de entrada escolhida pelas entradas de seleção.<br>
Explicação: O MUX de 2 bits funciona como um seletor. Ele escolhe uma entre quatro entradas possíveis com base nos bits de seleção C1 e C2. Cada combinação de C1C2 (00, 01, 10, 11) aponta para uma das entradas "A" a "D", encaminhando somente essa entrada para a saída.<br>
