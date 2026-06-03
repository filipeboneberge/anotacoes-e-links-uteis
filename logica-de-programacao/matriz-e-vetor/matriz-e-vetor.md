# MATRIZ E VETOR


### Matriz
 - Coleção de [variáveis](../variaveis/variaveis.md) do mesmo tipo, acessíveis com um único nome e armazenamento na memória. Dividido em linha e colunas. A individualização de cada variável é feito através do uso de índices.

### Exemplo
```
// Declara uma matriz com 2 linhas e 3 colunas
        inteiro tabela[2][3]

        // Atribuindo valores
        tabela[0][0] = 10 // Linha 0, Coluna 0
        tabela[0][1] = 20 // Linha 0, Coluna 1
        tabela[0][2] = 30 // Linha 0, Coluna 2
        
        tabela[1][0] = 40 // Linha 1, Coluna 0
        tabela[1][1] = 50 // Linha 1, Coluna 1
        tabela[1][2] = 60 // Linha 1, Coluna 2

        // Lendo o valor da 2ª linha (índice 1) e 3ª coluna (índice 2)
        escreva("O valor é: ", tabela[1][2]) // Imprime 60
```

### Vetor
 - São Matriz de uma só dimenção. Dividido somente em colunas.

### Exemplo
```
// Declara um vetor de 3 posições (0, 1 e 2)
        real notas[3]

        // Atribuindo valores diretamente aos índices
        notas[0] = 7.5
        notas[1] = 8.0
        notas[2] = 9.5

        // Lendo um valor da 2ª posição
        escreva("A nota do índice 1 é: ", notas[1])
    }
```



