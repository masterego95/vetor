# vetor
linguagem C

#include <stdio.h>

int main() {
    int vetor[20]; // Declarando um vetor de 20 números inteiros
    int i;

    // Preencha o vetor com números de exemplo (você pode preencher com os números desejados)
    for (i = 0; i < 20; i++) {
        vetor[i] = i + 1; // Neste exemplo, preenchemos o vetor com os números de 1 a 20

        printf("digite os numeros:");
        scanf("%d", &vetor[i]);
    }

    // Exibe os números do décimo ao vigésimo (índices 9 a 19)
    printf("Os numeros do decimo ao vigesimo são: ");
    for (i = 9; i < 20; i++) {
        printf("%d ", vetor[i]);
    }


    return 0;
}





usando o laço while

#include <stdio.h>

int main() {
    int vetor[20]; // Declarando um vetor de 20 números inteiros
    int i = 0; // Inicializa o índice do vetor

    // Preencha o vetor com números de exemplo (você pode preencher com os números desejados)
    while (i < 20) {

        printf("digite o numero:");
        scanf("%d", &vetor[i]);
        i++;
    }

    // Exibe os números do décimo ao vigésimo (índices 9 a 19)
    i = 9; // Inicializa o índice para o décimo número
    printf("Os números do décimo ao vigésimo são: ");
    while (i < 20) {
        printf("%d ", vetor[i]);
        i++;
    }


    return 0;
}

