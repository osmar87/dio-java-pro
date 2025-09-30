## Tipos e Variaveis

## 🔹 Tipos Primitivos
Java possui **8 tipos primitivos**:

| Tipo      | Tamanho   | Exemplo de Valor  | Descrição |
|-----------|-----------|-------------------|------------|
| `byte`    | 8 bits    | `127`             | Números inteiros pequenos (-128 a 127). |
| `short`   | 16 bits   | `32000`           | Números inteiros (-32.768 a 32.767). |
| `int`     | 32 bits   | `100000`          | Inteiros mais usados. |
| `long`    | 64 bits   | `10000000000L`    | Inteiros grandes (necessita `L` no final). |
| `float`   | 32 bits   | `3.14f`           | Números decimais (usa `f` no final). |
| `double`  | 64 bits   | `3.14159`         | Números decimais mais precisos. |
| `char`    | 16 bits   | `'A'`             | Um caractere Unicode. |
| `boolean` | 1 bit     | `true` / `false`  | Valores lógicos. |


# ➕ Operadores em Java

Os **operadores** são símbolos que permitem realizar operações sobre variáveis e valores.

---

## 🔹 1. Operadores Aritméticos
Usados para operações matemáticas básicas.

| Operador | Descrição           | Exemplo         | Resultado |
|----------|---------------------|-----------------|-----------|
| `+`      | Adição              | `10 + 5`        | `15` |
| `-`      | Subtração           | `10 - 5`        | `5` |
| `*`      | Multiplicação       | `10 * 5`        | `50` |
| `/`      | Divisão             | `10 / 2`        | `5` |
| `%`      | Módulo (resto)      | `10 % 3`        | `1` |

---

## 🔹 2. Operadores Relacionais
Comparam dois valores e retornam um **boolean** (`true` ou `false`).

| Operador | Descrição              | Exemplo     | Resultado |
|----------|------------------------|-------------|------------|
| `==`     | Igual a                | `10 == 5`   | `false` |
| `!=`     | Diferente de           | `10 != 5`   | `true` |
| `>`      | Maior que              | `10 > 5`    | `true` |
| `<`      | Menor que              | `10 < 5`    | `false` |
| `>=`     | Maior ou igual         | `10 >= 5`   | `true` |
| `<=`     | Menor ou igual         | `10 <= 5`   | `false` |

---

## 🔹 3. Operadores Lógicos
Usados em expressões booleanas.

| Operador | Descrição            | Exemplo             | Resultado |
|----------|----------------------|---------------------|------------|
| `&&`     | E (AND lógico)       | `(10 > 5 && 5 < 8)` | `true` |
| `||`     | OU (OR lógico)       | `(10 > 5 || 5 > 8)` | `true` |
| `!`      | NÃO (NOT lógico)     | `!(10 > 5)`         | `false` |

---

## 🔹 4. Operadores de Atribuição
Usados para **atribuir valores** às variáveis.

| Operador | Exemplo     | Equivalente a   |
|----------|-------------|-----------------|
| `=`      | `x = 5`     | `x = 5` |
| `+=`     | `x += 3`    | `x = x + 3` |
| `-=`     | `x -= 2`    | `x = x - 2` |
| `*=`     | `x *= 4`    | `x = x * 4` |
| `/=`     | `x /= 2`    | `x = x / 2` |
| `%=`     | `x %= 3`    | `x = x % 3` |

---

## 🔹 5. Operadores Unários
Aplicados em apenas **uma variável**.

| Operador | Descrição             | Exemplo     | Resultado |
|----------|-----------------------|-------------|------------|
| `++`     | Incremento (soma 1)   | `x = 5; x++` → `6` |
| `--`     | Decremento (subtrai 1)| `x = 5; x--` → `4` |
| `+`      | Valor positivo        | `+x`        | `x` |
| `-`      | Valor negativo        | `-x`        | `-x` |

---

## 🔹 6. Operador Ternário
Uma forma curta de `if/else`.

```java
int idade = 18;
String status = (idade >= 18) ? "Maior de idade" : "Menor de idade";
System.out.println(status); // Saída: Maior de idade
