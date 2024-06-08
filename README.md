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
 O Mathf.Log consegue receber tanto valores decimais quanto valores inteiros, em resumo, ele pode utilizar de valores decimais (float) em seus cálculos. Agora, sobre o método em si, ele funciona para cálcular o logaritmo de um número específico em uma base específica, ambos impostos pelo programador e agora com isso em mãos ele fará os cálculos e irá retornar o logaritmo. Caso seja dado somente o número sem a sua base, ele fará o cálculo do logaritmo natural (base) do tal valor dado.
