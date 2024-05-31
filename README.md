Este código LaTex calcula a composição de duas funções, `f(x)` e `g(x)`, especificamente `f(g(x))`, que é denotado como `fof(x)`.

## **Funções**

* `f(x) = 2x - 3`: Esta função representa uma relação linear, onde a saída (`y`) é obtida multiplicando a entrada (`x`) por 2 e subtraindo 3.
* `g(x) = x^2 - 1`: Esta função representa uma relação quadrática, onde a saída (`y`) é elevada ao quadrado e então 1 é subtraído.

## **Cálculo de composição**

O código calcula `fof(x)`, que envolve a aplicação de `f` à saída de `g(x)`. Passo a passo do processo:

1. **Função interna** (`g(x)`): Primeiro avaliamos `g(x)` com a entrada `x`. Isso nos dá `x ^ 2 - 1`.
2. **Função Externa** (`f(x)`):** Pegamos então o resultado de `g(x)` (que é `x^2 - 1`) e o substituímos em `f(x)` . Então, temos `f(x^2 - 1)`.
3. **Simplificação:** Finalmente, simplificamos `f(x^2 - 1)` de acordo com a definição de `f(x)`. Isso envolve multiplicar `x ^ 2 - 1` por 2 e subtrair 3. A expressão resultante é `4x - 9`.

## **Resultado**

A composição de `f` e `g`, `fof(x)`, é igual a `4x - 9`. Isso significa que se você aplicar `f` à saída de `g(x)`, você obterá esta expressão linear.

## **Imagem**

