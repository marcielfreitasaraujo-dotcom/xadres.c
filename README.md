#include <stdio.h>

int main() {

    printf("=====Simulação de Movimentação de Peças de Xadrez=====\n");

    // ===============================
    // Movimento da TORRE (usando FOR)
    // ===============================
    //torre deve mover-se 5 casas para a direita
    int i;
    printf("Movimento da Torre:\n");
    for(i = 1; i <= 5; i++) { //inicialização; condição; incremento
        printf("Direita (%d)\n", i);
    }
    printf("\n");


    // ===============================
    // Movimento do BISPO (usando WHILE)
    // ===============================
    //bispo deve mover-se 5 casas na diagonal superior direita
    int j = 1; //inicialização
    printf("Movimento do Bispo:\n");
    while(j <= 5) {  //condição
        printf("Cima, Direita (%d)\n", j);
        j++; //incremento
    }
    printf("\n");


    // ===============================
    // Movimento da RAINHA (usando DO-WHILE)
    // ===============================
    //rainha deve mover-se 8 casas para a esquerda
    int k = 1; //inicialização
    printf("Movimento da Rainha:\n");
    do {
        printf("Esquerda (%d)\n", k);
        k++; //incremento
    } while(k <= 8); //condição
    printf("\n");


    // ===============================
    // Movimento do CAVALO (usando loops aninhados)
    // ===============================
    // O cavalo se move em "L": 2 casas para baixo e 1 casa para a esquerda
    // Usando um loop for (para baixo) e um loop while (para esquerda)
    int l, m;
    printf("Movimento do Cavalo:\n");

    for(l = 1; l <= 2; l++) { // movimenta duas casas para baixo
        printf("Baixo (%d)\n", l);
    }

    for(m = 1; m <= 1; m++) { // movimenta uma casa para a esquerda
            printf("Esquerda (%d)\n", m);
        }
    

    printf("\nSimulação concluída!\n");

    return 0;
}

//codigo atualizado 09/11/2025-- nivel aventureiro
