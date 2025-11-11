4-BIT-ADDER: <br>
Entradas: O 4-bit adder recebe 8 entradas, sendo elas -> 2 números de 4 bits.<br>
Saidas: Gera uma saída de 4 bits podendo ter um carry out também.<br>
Explicação: O 4-bit adder é um circuito feito para somar dois números binários de 4 bits.<br>
<br>
HALF SUBTRACTOR: <br>
Entradas: O half subtractor possui 2 entradas, representando o minuendo (A) e o subtraendo (B).<br>
Saídas: Gera 2 saídas — a diferença (D) e o borrow out (B_out).<br>
Explicação: O half subtractor é um circuito combinacional que realiza a subtração entre dois bits. Ele indica a diferença entre A e B e se foi necessário "pegar emprestado" (borrow) de um bit mais significativo.<br>
<br>
FULL SUBTRACTOR:<br>
Entradas: O full subtractor recebe 3 entradas — o minuendo (A), o subtraendo (B) e o borrow in (B_in), que vem da subtração anterior.<br>
Saídas: Fornece 2 saídas — a diferença (D) e o borrow out (B_out).<br>
Explicação: O full subtractor é um circuito que realiza a subtração completa de três bits, considerando o borrow de uma etapa anterior. Ele é formado pela combinação de dois half subtractors e uma porta OR, sendo essencial em operações de subtração em circuitos maiores, como o 4-bit subtractor.<br>
