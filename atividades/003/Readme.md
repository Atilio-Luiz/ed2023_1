## Função para calcular número de Euler

![](cover.jpg)

## Motivação

O número de Euler $(2,71828182846...)$ pode ser aproximado pela série abaixo:

$$E = 1 + \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \cdots + \frac{1}{N!}$$

Faça uma função que retorna o fatorial de um número inteiro positivo $n$ passado como parâmetro, ou seja, retorna $1 * 2 * 3 * ... * (n-1) * n$. Chame esta função de `fatorial`.

O valor retornado, e a variável que armazena o fatorial, devem ser do tipo **double**, pois esta função cresce muito rápido. Uma variável do tipo **int** só é capaz de armazenar até $12!$.

Em seguida, crie uma função chamada `euler` que recebe um inteiro $N$ e retorna o valor da série

$$E = 1 + \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \cdots + \frac{1}{N!}$$

A função `euler` deve chamar a função `fatorial`.

A função `main` lê o inteiro $N$ e imprime o valor de `euler(N)`.


### Entrada
- 3 lados em float, um por linha

### Saída
- Área com duas casas decimais.

## Exemplos

```
>>>>>>>>
4
3
5
========
6.00
<<<<<<<<

>>>>>>>>
10
12
16
========
59.92
<<<<<<<<
```
