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
package desafio9;

import java.util.Scanner;

/**
 * 6. Crie um vetor com 10 números inteiros. Depois de preenchido, substitua
 * todos os números negativos por zero e mostre o vetor final.
 *
 * @author henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int i;
        int[] nI = new int[10];
        for (i = 0; i < nI.length; i++) {
            System.out.println("Digite um numero:");
            nI[i] = ler.nextInt();
            if (nI[i] < 0) {
                nI[i] = 0;
            }
        }
        System.out.println("Resultado");
        for (i = 0; i < nI.length; i++) {
            System.out.println(nI[i]);
        }
    }

}
```
# questao 7
```java
package desafio9;

import java.util.Scanner;

/**
 * 7. Crie um vetor com 10 elementos inteiros e calcule a média de todos os
 * elementos. Em seguida, mostre quais valores são maiores que a média.
 *
 * @author henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] nota = new int[10];
        int i, soma = 0, media;
        for (i = 0; i < nota.length; i++) {
            System.out.println("Digite a nota:" + (i + 1) + ":");
            nota[i] = ler.nextInt();
            soma += nota[i];
        }

        media = soma / nota.length;
        System.out.println("\nMedia das notas:" + media);

        System.out.println("As notas maiores que a media é");
        for (i = 0; i < nota.length; i++) {
            if (nota[i] > media) {
                System.out.println("nota " + (i + 1) + ":" + nota[i]);
            }
        }
    }

}
```
# questao 8
```java
package desafio9;

import java.util.Scanner;

/**
 * 8. Crie um vetor com 10 elementos inteiros e mostre quantas vezes o número 5
 * aparece no vetor.
 *
 * @author Henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] n = new int[10];
        int c = 0;
        for (int i = 0; i < n.length; i++) {
            System.out.println("Digite um número:");
            n[i] = ler.nextInt();

        }
        for (int i = 0; i < n.length; i++) {
            if (n[i] == 5) {
                c++;
            }
        }
        System.out.println("A quantidade de vezes que aparece o número 5 é:" + c);
    }

}
```
# questao 9
```java
package desafio9;

import java.util.Scanner;

/**
 * 9. Crie um vetor de 10 posições com números inteiros. Faça um novo vetor
 * contendo apenas os valores que são múltiplos de 3.
 *
 * @author Henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] n = new int[10];
        int[] multiploPorTres = new int[10];
        int c = 0;
        for (int i = 0; i < n.length; i++) {
            System.out.println("Digite um numero:");
            n[i] = ler.nextInt();
        }
        for (int i = 0; i < n.length; i++) {
            if (n[i] % 3 == 0) {
                multiploPorTres[c] = n[i];
                c++;
            }
        }
        System.out.println("Nùmeros múltiplos de 3:");
        for (int i = 0; i < c; i++) {
            System.out.println(multiploPorTres[i] + " ");
        }
    }

}
```
# questao 10
```java
package desafio9;

import java.util.Scanner;

/**
 * 10. Crie dois vetores A e B com 10 números inteiros. Gere um terceiro vetor C
 * contendo o maior valor entre A[i] e B[i] em cada posição.
 *
 * @author Henrique
 */
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] a = {2, 8, 9, 20, 58, 7, 60, 10, 5, 23};
        int[] b = {5, 114, 196, 37, 174, 96, 49, 80, 29, 3};
        int[] c = new int[10];

        for (int i = 0; i < a.length; i++) {
            if (a[i] > b[i]) {
                c[i] = a[i];
            } else {
                c[i] = b[i];
            }
        }
        System.out.println("Os maiores numeros entre os 2 vetores de cada posição:");
        for (int i = 0; i < c.length; i++) {
            System.out.println("C[" + i + "]=" + c[i]);
        }

    }

}
```
