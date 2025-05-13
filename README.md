# Desafio9

# questao 1
```java
package projetovetores;

import java.util.Scanner;

/**
 * 1. Crie um vetor de 10 elementos inteiros. Leia os valores e exiba quantos
 * deles são maiores que 100.
 *
 * @author henrique
 */
public class ProjetoVetores {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] v = new int[10];
        int i, cn100 = 0;

        for (i = 0; i < v.length; i++) {
            System.out.println("Digite um numero:");
            v[i] = ler.nextInt();
            if (v[i] > 100) {
                cn100++;
            }
        }
        System.out.println("O vetor possui:" + cn100 + " valores maiores que 100");
    }

}

```
# questao 2
```java
package projetovetores;

/**
 * 2. Crie um vetor de 10 elementos inteiros. Exiba a soma de todos os valores
 * armazenados no vetor.
 *
 * @author henrique
 */
public class ProjetoVetores {

    public static void main(String[] args) {
        int[] nInteiros = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        int soma = 0;
        for (int i = 0; i < nInteiros.length; i++) {
            soma += nInteiros[i];
        }
        System.out.println("a soma dos numeros dentro dos vetores é:" + soma);

    }

}
```
# questao 3
```java
package desafio9;

/**
 * 3. Crie um vetor de 10 elementos inteiros. Depois de preenchê-lo, mostre os
 * valores na ordem original e, em seguida, na ordem inversa.
 *
 * @author henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        int[] eInteiros = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        for (int elemento : eInteiros) {
            System.out.println(elemento);
        }
        for (int i = eInteiros.length - 1; i >= 0; i--) {
            System.out.println(eInteiros[i]);
        }
    }

}
```
# questao 4
```java
package desafio9;

import java.util.Scanner;

/**
 * 4. Leia um vetor de 10 posições com números inteiros e conte quantos números
 * são negativos.
 *
 * @author henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] nInteiros = new int[10];
        int i, cN = 0;

        for (i = 0; i < nInteiros.length; i++) {
            System.out.println("Digite um numero");
            nInteiros[i] = ler.nextInt();
            if (nInteiros[i] < 0) {
                cN++;
            }

        }
        System.out.println("A quantidade de numeros negativos é:" + cN);
    }

}
```
# questao 5
```java
package desafio9;

/**
 * 5. Crie um vetor de 10 elementos inteiros. Multiplique todos os elementos por
 * 2 e mostre o vetor resultante.
 *
 * @author henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        int[] nI = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        for (int i = 0; i < nI.length; i++) {
            System.out.println(nI[i] + "x" + 2 + " = " + (nI[i] * 2));
        }
    }

}
```
# questao 6
```java

```
