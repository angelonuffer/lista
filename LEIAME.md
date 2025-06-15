# Lista.0

Esta biblioteca fornece implementações das funções `mapear` e `juntar` para listas.

## Função `mapear`

A função `mapear` aplica uma função transformadora a cada elemento de uma lista e retorna uma nova lista com os elementos transformados.

**Parâmetros:**

*   `lista`: A lista de entrada a ser mapeada.
*   `mapeador`: A função que será aplicada a cada elemento da `lista`.

**Retorno:**

*   Uma nova lista contendo os elementos da `lista` após a aplicação da função `mapeador`.

**Exemplo de Uso:**

```
numeros = [1, 2, 3, 4]
dobro = numero => numero * 2
numeros_dobrados = lista.mapear(numeros dobro)
// numeros_dobrados será [2, 4, 6, 8]
```

## Função `juntar`

A função `juntar` concatena todos os elementos de uma lista em uma única string, utilizando um delimitador especificado entre cada elemento.

**Parâmetros:**

*   `lista`: A lista de entrada cujos elementos serão juntados.
*   `delimitador`: A string que será inserida entre cada elemento da `lista` na string resultante.

**Retorno:**

*   Uma string representando a concatenação dos elementos da `lista`, separados pelo `delimitador`.

**Exemplo de Uso:**

```
palavras = ["Olá", "mundo", "!"]
frase = lista.juntar(palavras " ")
// frase será "Olá mundo !"
```

## Testes

Os arquivos de teste específicos para cada função podem ser encontrados no diretório `testes/`.

Para executar os testes, utilize o interpretador da linguagem 0 em Node.js:

``` bash
$ node 0/0_cli.js testes.0
```