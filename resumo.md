# Variáveis

"É um espaço reservado na memória do computador usado para armazenar dados (valores) que podem ser manipulados e alterados durante a execução de um programa". Em outras palavras, uma variável nada mais é do quê um local designado para determinada informação.

## Definindo uma variável

``` 
nome_da_variável = dados 
```

* **nome_da_variável** => O nome da variável é o rótulo da mesma, ele é definido pelo programador e é usado para identificar e acessar o valor armazenado na memória.

* **dados** => O dado é o valor a ser definido na variável.

## Características das variáveis no python

* **Tipagem dinâmica:** Ao contrário de outras linguagens de programação, o python "detecta" automaticamente o tipo da variável conforme o dado inserido nela.

* **Substituição de valor:** O python, ao contrário de linguagens como o Java, ele aceita sobreposição de valores em variáveis, o que significa que é possível "apagar" um valor de uma variável e "por outra por cima".

## Tipos de variáveis

### Variáveis de texto

* **String(str):** Nativamente no python há apenas um tipo de variável de texto, as strings, que não possuem limite de caracteres e aceitam todos os tipos de símbolos.

    ```
    minha_string1 = "Assim se define uma variável!"
    minha_string2 = str(3.14)
    ```

### Variáveis numéricas

* **Inteiros(int):**  As variáveis inteiras podem armazenar todos os números naturais(1, 2, 3...), seus opostos negativos(-1, -2, -3...) e o zero(0).

* **Floats(float):**  Em python uma variável de ponto flutuante(float) representa um número decimal, qualquer número com casas decimais(0.1, 0.01, 0.001...)

    ```
    # Números inteiros
    meu_inteiro1 = 10
    meu_inteiro2 = int("180")

    # Números de ponto flutuante
    meu_float1 = 3.14
    meu_float2 = float("3.14")
    ```


### Variáveis booleanas

* **Booleans(bool):** Variáveis booleanas também só tem um integrante os "bools", que podem ter apenas dois valores, "True" ou "False", que são usados quase exclusivamente em estruturas condicionais.

    ```
    meu_bool1 = True
    meu_bool2 = False
    ```
# Operadores no Python

## Operadores aritmétrios

Operadores aritméticos são símbolos utilizados em linguagens de programação e matemática para realizar cálculos numéricos básicos

* **Adição(+):** Soma dois valores

    ` num = 5 + 2 # Resultado: 7 `

* **Subtração(-):** Subtrai o segundo valor do primeiro

    ` num = 5 - 2 # Resultado: 3 `

* **Multiplicação(*):** Multiplica dois valores

    ` num = 5 * 2 # Resultado: 10 `

* **Divisão(/):** Divide o primeiro valor pelo segundo (x / y)

    ` num = 5 / 2 # Resultado: 2.5 `

* **Módulo/Resto(%):** Retorna o resto de uma divisão inteira (x % y)

    ` num = 5 % 2 # Resultado: 1 `

* **Divisão Inteira(//):** Retorna apenas o número inteiro de uma divisão (x // y)

    ` num = 5 // 2 # Resultado: 2 `

* **Exponencial(\*\*):** Eleva um número à potência de outro (x ** y)

    ` num = 5 ** 2 # Resultado: 25 `


## Operadores de atribuição

peradores de atribuição são usados em programação para definir ou atualizar o valor de uma variável

* **Definição(=):** Usado para definir variáveis

    ```
    num = 5
    ```

* **Adição(+=):** Define a variável como a soma da variável com o número

    ```
    # Estes dois são equivalentes
    num = num + 1
    num += 1
    ```

* ***Subtração(-=):*** Define a variável como a subtração da variável com o número

    ```
    # Estes dois são equivalentes
    num = num - 1
    num -= 1
    ```

* ***Multiplicação(\*=):*** Define a variável como o produto da variável com o número

    ```
    # Estes dois são equivalentes
    num = num * 2
    num *= 2
    ```

* ***Divisão(/=):*** Define a variável como o quociente(divisão) da variável com o número

    ```
    # Estes dois são equivalentes
    num = num / 2
    num /= 2
    ```

* ***Módulo/resto(%=):*** Define a variável como o resto de uma divisão inteira da variável com o número

    ```
    # Estes dois são equivalentes
    num = num % 2
    num %= 2
    ```

* ***Divisão inteira(//=):*** Define a variável como uma divisão inteira da variável com o número

    ```
    # Estes dois são equivalentes
    num = num // 2
    num //= 2
    ```

* ***Exponencial(\*\*=):*** Define a variável como a potência da variável com o número

    ```
    # Estes dois são equivalentes
    num = num ** 2
    num **= 2
    ```

## Operadores de comparação
