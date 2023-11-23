# vetor
estudo np2
linguagem C

#include <stdio.h>

int main() {
    int vetor[20]; 
    int i;

   
    for (i = 0; i < 20; i++) {
        vetor[i] = i + 1; 
        printf("digite os numeros:");
        scanf("%d", &vetor[i]);
    }

    
    printf("Os numeros do decimo ao vigesimo são: ");
    for (i = 9; i < 20; i++) {
        printf("%d ", vetor[i]);
    }


    return 0;
}





usando o laço while

#include <stdio.h>

int main() {
    int vetor[20]; 
    int i = 0; 

  
    while (i < 20) {

        printf("digite o numero:");
        scanf("%d", &vetor[i]);
        i++;
    }

    
    i = 9; 
    printf("Os números do décimo ao vigésimo são: ");
    while (i < 20) {
        printf("%d ", vetor[i]);
        i++;
    }


    return 0;
}

