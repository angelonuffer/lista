# Lista.0

Esta biblioteca fornece implementações de funções úteis para manipulação de listas.

## Função `mapear`

A função `mapear` aplica uma função transformadora a cada elemento de uma lista e retorna uma nova lista com os elementos transformados.

**Parâmetros:**

A função recebe um objeto de configuração com as seguintes propriedades:

*   `lista`: A lista de entrada a ser mapeada.
*   `função`: A função que será aplicada a cada elemento da `lista`.

**Exemplo de Uso:**

```
lista.mapear({
  lista: [1 2 3 4]
  função: n => n * 2
})
// [2 4 6 8]
```

## Função `reduzir`

A função `reduzir` combina todos os elementos de uma lista em um único valor, aplicando uma função de redução.

**Parâmetros:**

A função recebe um objeto de configuração com as seguintes propriedades:

*   `lista`: A lista de entrada a ser reduzida.
*   `função`: A função que será aplicada a pares de elementos.

**Exemplo de Uso:**

```
lista.reduzir({
  lista: [1 2 3 4]
  função: args => args[0] + args[1]
})
// 10
```

## Função `planificar`

A função `planificar` combina múltiplas listas em uma única lista nivelada.

**Parâmetros:**

*   `lista_de_listas`: Uma lista contendo outras listas que serão combinadas. Este é o único parâmetro da função, passado diretamente (não como parte de um objeto de configuração).

**Exemplo de Uso:**

```
lista.planificar([[1 2] [3 4] [5 6]])
// [1 2 3 4 5 6]
```

## Testes

Os testes estão disponíveis no diretório `testes/`. Execute-os com:

```bash
$ node 0/0_node.js testes/0 node | node
```