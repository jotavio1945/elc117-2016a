# Prática: Programação funcional em Haskell



## Orientações ([para entregar: T3](../../trabalhos/t3))

Para fazer os exercícios abaixo, consulte principalmente os slides [Condicionais, recursividade, listas e tuplas em Haskell](../../slides/slides-haskell-cond-repet-2016a.pdf). 

Os exercícios deverão ser entregues como [T3](../../trabalhos/t3).


## Exercícios



1. Defina uma função **recursiva** que receba uma lista de números inteiros e produza uma nova lista com cada número elevado ao quadrado.



2. Escreva uma função **recursiva** que receba uma lista de nomes e adicione a string "Sr. " no início de cada nome. 


3. Crie uma função **recursiva** que receba uma string e retorne o número de espaços nela contidos. 

4. Escreva uma função **recursiva** que, dada uma lista de números, calcule 3*n^2 + 2/n + 1 para cada número n da lista. 

5. Escreva uma função **recursiva** que, dada uma lista de números, selecione somente os que forem negativos.

6. Defina uma função **não-recursiva** que receba uma string e retire suas vogais, conforme os exemplos abaixo.

   ```
   > semVogais "andrea"
   "ndr"
   > semVogais "xyz"
   "xyz"
   > semVogais "ae"
   ""
   ```

7. Expresse uma solução **recursiva** para o exercício anterior.

8. Defina uma função **não-recursiva** que receba uma string, possivelmente contendo espaços, e que retorne outra string substituindo os demais caracteres por '-', mas mantendo os espaços. Exemplos:

   ```
   > codifica "Rio Grande do Sul"
   "--- ------ -- ---"
   > codifica ""
   ""
   ```

9. Defina uma função **recursiva** que resolva o mesmo problema do exercício anterior.

10. Crie uma função **recursiva** `charFound :: Char -> String -> Bool`, que verifique se o caracter (primeiro argumento) está contido na string (segundo argumento). Exemplos de uso da função: 

   ```
   > charFound 'a' ""  
   False  
   > charFound 'a' "uau"  
   True  
   ```
  
11. Defina uma função **recursiva** que receba uma lista de coordenadas de pontos 2D e desloque esses pontos em 2 unidades, conforme o exemplo abaixo:

   ```
   > translate [(0.1,0.2), (1.1,6), (2,3.1)]
   [(2.1,2.2),(3.1,8.0),(4.0,5.1)]
   ```

12. Defina uma função **recursiva** que receba 2 listas e retorne uma lista contendo o produto, par a par, dos elementos das listas de entrada. Exemplos:

   ```
   > prodVet [1,2,3] [4,5,6]
   [4,10,18]
   > prodVet [1,2,3] [4,5,6,7]
   [4,10,18]
   ```

13. Resolva o exercício anterior usando uma função de alta ordem, eliminando a necessidade de escrever código com recursão.

14. Defina uma função **recursiva** que receba um número n e retorne uma tabela de números de 1 a n e seus quadrados, conforme os exemplos abaixo:

   ```
   > geraTabela 5
   [(1,1),(2,4),(3,9),(4,16),(5,25)]
   > geraTabela 0
   []
   ```

