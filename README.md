# Unity_Methods
Abs: O método Abs retorna o valor absoluto de, no caso do exemplo, F. F irá receber um valor como parâmetro e assim poderá ser utilizado para calculos ou outros. Em resumo, ele receberá o valor de F (no caso) e irá retorna-lo igual foi inserido.

Approximly: Recebe os valores inseridos pelo usuário e os compara, retornando "true" se forem próximos, de exemplo: se ambos os valores inseridos forem 1, o programa retornará "true".

Log: Ele irá receber dois valores, os quais são o valor e a sua base respectivamente. De exemplo: (6,2), 6 na base 2 e depois retornará o logaritmo do número escrito de uma base exata. Caso não dê a base e somente o primeiro valor, irá receber o mesmo e devolver o valor natural (base e) do número dado.

Max: Ele recebe dois ou mais valores e retorna o maior valor numérico desse conjunto dado e se for comparado valores negativos, irá retornar o mais próximo de zero. De exemplo (1,2), ele irá retornar o segundo termo dentro desse parâmetro, pois ele é o maior e se fosse -1,-2, ele iria retornar -1 por ser o mais próximo a zero.

Min: Ele irá receber dois ou mais valores e devolverá o termo de menor valor dentro do parâmetro, por exemplo: (1,2), nesse caso ele retornará 1. 

Ping Pong: Irá receber F e irá eleva-lo a um valor P.

-----------------------------------------------------------------------------

Abs: O abs é um método estático, logo, terá algo como se fosse um prefixo do C# sempre que utilizado: Math.abs(). Agora, sobre o Math.abs, o mesmo recebe um valor numérico e o retorna o mesmo valor, em outras palavras o valor absoluto passado. De exemplo: Math.abs (1) ---> Retornará 1. Ele aceita valores negativos, positivos e o próprio zero. Abs não aceita uma string, valor nenhum, colchetes ou mais de um valor, aceitando somente um valor numérico nos seus parâmetros. Sobre o valor nenhum, é no caso dos parenteses estarem literalmente vazios. ("") Representa zero.

Log: O Mathf.Log irá receber dois valores numéricos, sendo respectivamente o valor e a sua base, como por exemplo: (6,2), nisso será calculado o Logaritmo de 6 na base 2 e assim será retornado o valor resultante desse cálculo. Caso não seja fornecido a base e somente o primeiro valor, poderá ainda sim fazer um cálculo e descobrir o valor natural (base), o retornando também. Recebe de parâmetro de 1 a 2 números.
