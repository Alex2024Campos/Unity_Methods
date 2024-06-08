## Métodos Matemáticos do Unity

# Mathf.Abs:
 O Mathf.Abs consegue receber dois tipos de dados: Int e Float, sendo os números inteiros, positivos ou negativos, e os números decimais. A sua função é receber um valor e retornar o seu valor absoluto, ou seja, retornará o mesmo valor só que positivo pois ele irá analisar a distância entre esse número (negativo e positivo) em relação ao ponto zero. De exemplo: Debug.Log(Mathf.Abs(-10)), essa linha de código apresentará o valor 10 para o usuário.

# Mathf.Approximately: 
 Recebendo valores float, ou seja, decimais, o Mathf.Approximately fará a comparação de dois valores impostos pelo usuário, retornando assim verdadeiro ou falso conforme o resultado. Se forem semelhantes, será assim retornado "true" e se contrário, "false"". Exemplo: if (Mathf.Approximately (1.0f, 10.0f / 10.0f)){
 print("Os valores são aproximadamente iguais");
}, esse código fará a análise dos valores dentro de seus parâmetros e caso seja "true", retornará uma mensagem conforme feita no caso.
 
# Mathf.ClosestPowerOfTwo:
 Esse método recebe somente valores inteiros, assim utilizando-os para fazer o seguinte cálculo: ele irá pegar o valor inserido pelo usuário e retornará assim o valor da potência de dois mais próximo do número fornecido. De exemplo: Debug.Log(Mathf.ClosestPowerOfTwo(7)), retornará 8, pois é a potência de dois mais próxima do parâmetro.

# Mathf.IsPowerOfTwo:
 Mathf.IsPowerOfTwo receberá somente valores inteiros (Int) como pârametro, pegando assim esse valor e analisando se o mesmo é o resultado de uma potência de dois, retornando "true" no caso do número realmente ser uma potência de dois ou "false" se o contrário. Como exemplo, utilizaremos o 7 e 2: Debug.Log(Mathf.IsPowerOfTwo(7));, esse código retornará "false".
Debug.Log(Mathf.IsPowerOfTwo(32)), esse retornará "true".

# Mathf.Log:
 O Mathf.Log consegue receber como pârametro dados do tipo Float e Int, utilizando-os tanto para o cálculo quanto para retornar o valor final de tudo. Agora, sobre o método em si, será necessário fornecer dois valores numéricos que serão utilizados para descobrir o Logaritmo, será então necessário fornecer um valor específico e um valor para a base. Também tem como fornecer somente o valor específico e nesse caso será retornado o logaritmo natural do número. Exemplos, respectivamente: Debug.Log (Mathf.Log(6,2));, logaritmo de 6 na base 2, o resultado será: 2.584963, um número decimal (float).
Debug.Log (Mathf.Log(100));, será retornado o logaritmo natural de 100 e o resultado do cálculo que é: 4.60517.

# Mathf.Log10:
 Segue as mesmas propriedades do anterior, conseguindo receber valores float e int, tendo a única diferença de ter uma base fixa para o cálculo e sendo somente necessário fornecer o valor que será descoberto o logaritmo, e assim será retornado o resultado.

# Mathf.Max:
 O Mathf.Max, como já é de se pensar pelo seu nome, irá aceitar de um à mais valores numéricos e após serem inseridos, o maior deles será retornado. Aceita dados do tipo Int e Float, também conseguindo utilizar de valores negativos para as suas operações: nesse caso, o número mais próximo de zero será o maior. Vamos para um exemplo: Debug.Log (Mathf.Max (1,2));, 2 seria retornado.
Debug.Log (Mathf.Max(-1,-0.2));, -0.2 seria o valore retornado por está mais próximo de zero. 

# Mathf. Min:
 Ele atua como o inverso do Mathf.Max, recebendo os mesmos tipos de dados e quantidade de valores numéricos, mas retornando o menor valor dentre os que foram inseridos no seu parâmetro. Por exemplo: Debug.Log (Mathf.Max (1,2));, 1 seria retornado por ser o menor valor.
Debug.Log (Mathf.Max(-1,-0.2));, nesse caso o -1 seria retornado por ser o menor valor.


# Mathf.NextPowerOfTwo:

# Mathf.RoundToInt:
