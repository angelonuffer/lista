# Projeto Lista

Este projeto fornece implementações personalizadas das funções `mapear` (map) e `juntar` (join) para listas.

## Função `mapear`

A função `mapear` aplica uma função transformadora a cada elemento de uma lista e retorna uma nova lista com os elementos transformados.

**Parâmetros:**

*   `lista2`: A lista de entrada a ser mapeada.
*   `mapeador`: A função que será aplicada a cada elemento da `lista2`.

**Retorno:**

*   Uma nova lista contendo os elementos da `lista2` após a aplicação da função `mapeador`.

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

*   `lista2`: A lista de entrada cujos elementos serão juntados.
*   `delimitador`: A string que será inserida entre cada elemento da lista na string resultante.

**Retorno:**

*   Uma string representando a concatenação dos elementos da `lista2`, separados pelo `delimitador`.

**Exemplo de Uso:**

```
palavras = ["Olá", "mundo", "!"]
frase = lista.juntar(palavras " ")
// frase será "Olá mundo !"
```

## Testes

O projeto utiliza uma biblioteca de testes personalizada chamada `uniteste` para verificar a corretude das funções `mapear` e `juntar`. Os arquivos de teste específicos para cada função podem ser encontrados no diretório `testes/`.

Para executar os testes, presume-se a existência de um interpretador para a linguagem `.0` e a execução do arquivo `testes.0`.
