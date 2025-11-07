
#include <stdio.h>

int main() {

    printf("=====Simulação de Movimentação de Peças de Xadrez=====\n");
    // ===============================
    // Movimento da TORRE (usando FOR)
    // ===============================
    //torre deve mover-se 5 casas para a direita
    int t;
    printf("Movimento da Torre:\n");
    for(t = 1; t <= 5; t++) { //inicialização; condição; incremento
        printf("Direita (%d)\n", t);
    }
    printf("\n");


    // ===============================
    // Movimento do BISPO (usando WHILE)
    // ===============================
    //bispo deve mover-se 5 casas na diagonal superior direita
    int b = 1; //inicialização
    printf("Movimento do Bispo:\n");
    while(b <= 5) {  //condição
        printf("Cima, Direita (%d)\n", b);
        b++; //incremento
    }
    printf("\n");


    // ===============================
    // Movimento da RAINHA (usando DO-WHILE)
    // ===============================
    //rainha deve mover-se 8 casas para a esquerda
    int r = 1; //inicialização
    printf("Movimento da Rainha:\n");
    do {
        printf("Esquerda (%d)\n", r);
        r++; //incremento
    } while(r <= 8); //condição

    printf("\nSimulação concluída!\n");

    return 0;
}
