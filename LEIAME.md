# Lista.0

Esta biblioteca fornece implementações de funções úteis para manipulação de listas.

## Função `mapear`

A função `mapear` aplica uma função transformadora a cada elemento de uma lista e retorna uma nova lista com os elementos transformados.

**Parâmetros:**

*   `lista`: A lista de entrada a ser mapeada.
*   `mapeador`: A função que será aplicada a cada elemento da `lista`.

**Exemplo de Uso:**

```
lista.mapear({
  {1 2 3 4}
  n => n * 2
})
// {2 4 6 8}
```

## Função `reduzir`

A função `reduzir` combina todos os elementos de uma lista em um único valor, aplicando uma função de redução.

**Parâmetros:**

*   `lista`: A lista de entrada a ser reduzida.
*   `redutor`: A função que será aplicada a pares de elementos.

**Exemplo de Uso:**

```
lista.reduzir({
  {1 2 3 4}
  args => args[0] + args[1]
})
// 10
```

## Função `planificar`

A função `planificar` combina múltiplas listas em uma única lista nivelada.

**Parâmetros:**

*   `lista_de_listas`: Uma lista contendo outras listas que serão combinadas.

**Exemplo de Uso:**

```
lista.planificar({{1 2} {3 4} {5 6}})
// {1 2 3 4 5 6}
```

## Testes

Os testes estão disponíveis no diretório `testes/`. Execute-os com:

```bash
$ node 0/0_node.js testes/0
```