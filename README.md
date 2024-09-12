#include <stdio.h>

int main() {
    // Declaração da variável que vai armazenar o número
    int numero;

    // Solicita ao usuário que insira um número
    printf("Digite um numero: ");
    scanf("%d", &numero);

    // Estrutura condicional para verificar se o número é positivo, negativo ou zero
    if (numero > 0) {
        printf("O numero %d e positivo.\n", numero);
    } else if (numero < 0) {
        printf("O numero %d e negativo.\n", numero);
    } else {
        printf("O numero e zero.\n");
    }

    return 0;
}
