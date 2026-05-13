<details><summary> <h1>Variáveis</h1> </summary>

Uma variável é um espaço reservado na memória do computador usado para armazenar dados que podem ser manipulados e alterados durante a execução de um programa. Em outras palavras, uma variável nada mais é do que um local designado para determinada informação.

## Definindo uma variável

```python
nome_da_variável = dados
```

- **nome_da_variável** — O rótulo da variável, definido pelo programador, usado para identificar e acessar o valor armazenado na memória.
- **dados** — O valor a ser armazenado na variável.

## Características das variáveis no Python

- **Tipagem dinâmica:** Ao contrário de outras linguagens, o Python detecta automaticamente o tipo da variável conforme o dado inserido nela.
- **Substituição de valor:** O Python aceita sobreposição de valores em variáveis, o que significa que é possível substituir o valor de uma variável a qualquer momento.

## Tipos de variáveis

### Variáveis de texto

- **String (`str`):** Nativamente no Python há apenas um tipo de variável de texto — as strings, que não possuem limite de caracteres e aceitam todos os tipos de símbolos.

    ```python
    minha_string1 = "Assim se define uma string!"
    minha_string2 = str(3.14)
    ```

### Variáveis numéricas

- **Inteiros (`int`):** Armazenam números naturais (1, 2, 3...), seus opostos negativos (-1, -2, -3...) e o zero (0).

    ```python
    meu_inteiro1 = 10
    meu_inteiro2 = int("180")
    ```

- **Ponto flutuante (`float`):** Representa números decimais, ou seja, qualquer número com casas decimais (0.1, 0.01, 0.001...).

    ```python
    meu_float1 = 3.14
    meu_float2 = float("3.14")
    ```

### Variáveis booleanas

- **Booleano (`bool`):** Pode ter apenas dois valores — `True` ou `False` — usados principalmente em estruturas condicionais.

    ```python
    meu_bool1 = True
    meu_bool2 = False
    ```

</details>

<details><summary> <h1>Operadores no Python</h1> </summary>

## Operadores aritméticos

Operadores aritméticos são símbolos utilizados para realizar cálculos numéricos básicos.

- **Adição (`+`):** Soma dois valores.

    ```python
    num = 5 + 2  # Resultado: 7
    ```

- **Subtração (`-`):** Subtrai o segundo valor do primeiro.

    ```python
    num = 5 - 2  # Resultado: 3
    ```

- **Multiplicação (`*`):** Multiplica dois valores.

    ```python
    num = 5 * 2  # Resultado: 10
    ```

- **Divisão (`/`):** Divide o primeiro valor pelo segundo.

    ```python
    num = 5 / 2  # Resultado: 2.5
    ```

- **Módulo/Resto (`%`):** Retorna o resto de uma divisão inteira.

    ```python
    num = 5 % 2  # Resultado: 1
    ```

- **Divisão inteira (`//`):** Retorna apenas a parte inteira de uma divisão.

    ```python
    num = 5 // 2  # Resultado: 2
    ```

- **Exponenciação (`**`):** Eleva um número à potência de outro.

    ```python
    num = 5 ** 2  # Resultado: 25
    ```

## Operadores de atribuição

Operadores de atribuição são usados para definir ou atualizar o valor de uma variável.

- **Definição (`=`):** Cria ou redefine uma variável.

    ```python
    num = 5
    ```

- **Adição (`+=`):** Incrementa a variável pelo valor dado.

    ```python
    # Estes dois são equivalentes
    num = num + 1
    num += 1
    ```

- **Subtração (`-=`):** Decrementa a variável pelo valor dado.

    ```python
    # Estes dois são equivalentes
    num = num - 1
    num -= 1
    ```

- **Multiplicação (`*=`):** Multiplica a variável pelo valor dado.

    ```python
    # Estes dois são equivalentes
    num = num * 2
    num *= 2
    ```

- **Divisão (`/=`):** Divide a variável pelo valor dado.

    ```python
    # Estes dois são equivalentes
    num = num / 2
    num /= 2
    ```

- **Módulo/Resto (`%=`):** Define a variável como o resto da divisão pelo valor dado.

    ```python
    # Estes dois são equivalentes
    num = num % 2
    num %= 2
    ```

- **Divisão inteira (`//=`):** Define a variável como a divisão inteira pelo valor dado.

    ```python
    # Estes dois são equivalentes
    num = num // 2
    num //= 2
    ```

- **Exponenciação (`**=`):** Eleva a variável à potência do valor dado.

    ```python
    # Estes dois são equivalentes
    num = num ** 2
    num **= 2
    ```

## Operadores de comparação

Operações de comparação são operações que comparam dois valores e retornam um resultado lógico

- **Igual a (`==`):** Retorna `True` se os dois valores forem iguais e `False` se forem diferentes.

    ```python
    5 == 5          # Retorna: True
    3.14 == 3.14    # Retorna: True
    3.14 == 3       # Retorna: False
    "Oi" == "Oi"    # Retorna: True
    "Oi" == "Ei"    # Retorna: False
    "Oi" == "oi"    # Retorna: False
    ```

- **Diferente de (`!=`):** Retorna `True` se os dois valores forem diferentes e `False` se forem iguais.

    ```python
    5 != 5          # Retorna: False
    3.14 != 3.14    # Retorna False
    3.14 != 3       # Retorna True
    "Oi" != "Oi"    # Retorna: False
    "Oi" != "Ei"    # Retorna: True
    "Oi" != "oi"    # Retorna: True
    ```

- **Maior que (`>`):** Retorna `True` se o primeiro valor for maior que o segundo e `False` se ele for menor.

    ```python
    5 > 3           # Retorna: True
    5 > 5           # Retorna: False
    3.14 > 3        # Retorna: True
    1.41 > 3.14     # Retorna: False
    ```

- **menor que (`<`):** Retorna `True` se o primeiro valor for menor que o segundo e `False` se ele for maior.

    ```python
    5 < 3           # Retorna: False
    5 < 5           # Retorna: False
    3.14 < 3        # Retorna: False
    1.41 < 3.14     # Retorna: True
    ```

- **maior ou igual a (`>=`):** Retorna `True` se o primeiro valor for maior ou igual a o segundo e `False` se ele for menor.

    ```python
    5 >= 3           # Retorna: True
    5 >= 5           # Retorna: True
    3.14 >= 3        # Retorna: True
    1.41 >= 3.14     # Retorna: False
    ```

- **menor ou igual a (`<=`):** Retorna `True` se o primeiro valor for menor ou igual a o segundo e `False` se ele for maior.

    ```python
    5 <= 3           # Retorna: False
    5 >= 5           # Retorna: True
    3.14 <= 3        # Retorna: False
    1.41 <= 3.14     # Retorna: True
    ```

## Operadores lógicos

Operadores lógicos são operadores usados para combinar ou inverter condições booleanas.

- **Operador "e"(`and`):** Retorna `True` se as duas condições forem verdadeiras.

    ```python
    5 == 3 and 5 >= 5       # (False and true) Retorna: False
    6 < 7 and 3.14 <= 3     # (True and False) Retorna: False
    10 != 10 and 8 < 3      # (False and False) Retorna: False
    3.14 > 3 and 5 != -8    # (True and True) Retorna: True
    ```

- **Operador "ou"(`and`):** Retorna `True` se pelo menos uma das duas condições forem verdadeiras.

    ```python
    5 == 3 and 5 >= 5       # (False and True) Retorna: True
    6 < 7 and 3.14 <= 3     # (True and False) Retorna: True
    10 != 10 and 8 < 3      # (False and False) Retorna: False
    3.14 > 3 and 5 != -8    # (True and True) Retorna: True
    ```

- **Operador "não"(`not`):** Inverte a saída da condição, se a condição retornou `True` ele volta `False`, e se a condição retornou `False` o resultado será `True`

    ```python
    not 5 == 3              # (not False) Retorna: True
    not 6 < 7               # (not True) Retorna: False
    ```

## Ordem de execução dos operadores

1. `()`
2. `**`
3. `*`, `/`, `//`, `%`
4. `+`, `-`
5. `==`, `!=`, `>`, `>=`, `<`, `<=`
6. `not`
7. `and`
8. `or`

</details>