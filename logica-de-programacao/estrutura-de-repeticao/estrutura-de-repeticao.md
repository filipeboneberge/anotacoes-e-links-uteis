# ESTRUTURA DE REPETIÇÃO
Permite executar mais de uma vez o mesmo comando ou conjunto de comandos de acordo com uma condição e um contador. Enquanto o comando for verdadeiro o comando irá se repetir até a condição se tornar falsa.  Existem três tipos principais: **para, enquanto e faca... enquanto**.

### Para (For)
 - Usada quando você sabe exatamente o número de vezes que o bloco deve repetir.

### Exemplo
```
inteiro i

// Repete 5 vezes
        para (i = 1; i <= 5; i++) {
            escreva("Número: ", i, "\n")
        }
```

### Enquanto (While)
 - Avalia uma condição antes de executar o bloco.

### Exemplo
```
inteiro contador = 1
        
        enquanto (contador <= 5) {
            escreva("Contagem: ", contador, "\n")
            contador++ // Atualiza a variável para evitar loop infinito
        }
```

### Faça... Enquanto (Do-While)
 - Garante que o bloco de código será executado pelo menos uma vez, pois a condição é verificada apenas no final.

### Exemplo
```
inteiro contador = 1
        
        faca {
            escreva("Executando pelo menos uma vez. Contador: ", contador, "\n")
            contador++
        }
```





