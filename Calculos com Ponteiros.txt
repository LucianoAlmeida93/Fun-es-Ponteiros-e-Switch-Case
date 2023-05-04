
#include <stdio.h>

int main()
{
    int n1, n2;
    int *p1, *p2;
    
    p1 = &n1;
    p2 = &n2;
    
    printf("Digite o primeiro número:");
    scanf("%d", p1);
    printf("Digite o segundo número:");
    scanf("%d", p2);
    
    printf("Soma dos valore: %d + %d = %d \n", *p1, *p2, (*p1 + *p2));
    printf("\nSubtração dos valores: %d - %d = %d \n", *p1, *p2, (*p1 - *p2));
    printf("\nDivisão dos valores: %d / %d = %d \n", *p1, *p2, (*p1 / *p2));
    printf("\nMultiplicação dos valores: %d * %d = %d \n", *p1, *p2, (*p1 * *p2));
}
