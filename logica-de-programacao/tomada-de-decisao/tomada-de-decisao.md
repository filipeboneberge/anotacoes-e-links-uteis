## TOMADA DE DECISÃO
É a necessidade de decidir o que fazer dependendo de alguma condição.
Direcionam o fluxo do algoritmo baseando-se em condições lógicas **verdadeiro** ou **falso**.

### Principais Estruturas de Decisão
 - **( se ) ( entao ) ( senao ):** Avalia uma expressão booleana. Se for verdadeira, executa o bloco entao; se falsa, executa o senao (opcional).

### Exemplo
```
se (idade >= 18) {
      escreva("Maior de idade.")
    } senao {
      escreva("Menor de idade.")
    }
```
 - **( se ) Encadeado:** Utilizado para múltiplas condições em sequência (se -> senao se -> senao).
 ### Exemplo
```
 se (idade < 12) {
      escreva("Infantil")
    } senao se (idade >= 12 e idade < 18) {
      escreva("Juvenil") // Este código será executado
    } senao {
      escreva("Adulto")
    }
```
  - **( escolha caso):** Verifica uma [variável](../variaveis/variaveis.md) contra vários valores específicos ( caso ), oferecendo um caso contrario ( padrão ) se nenhum for correspondido. 
 
 ### Exemplo
```
escreva("Escolha uma opção (1-3): ")
leia(opcao)
    
    escolha(opcao) {
      caso 1:
        escreva("Opção 1 selecionada.")
        pare
      caso 2:
        escreva("Opção 2 selecionada.")
        pare
      caso 3:
        escreva("Opção 3 selecionada.")
        pare
      caso contrario:
        escreva("Opção inválida.")
    }
``` 






