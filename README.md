#include <stdio.h>

int main() {
    int a, b, temp;

    printf("Enter first number: ");
    scanf("%d", &a);

    printf("Enter second number: ");
    scanf("%d", &b);

    printf("\nBefore swapping:");
    printf("\nFirst number = %d", a);
    printf("\nSecond number = %d", b);

    // Swapping
    temp = a;
    a = b;
    b = temp;

    printf("\n\nAfter swapping:");
    printf("\nFirst number = %d", a);
    printf("\nSecond number = %d\n", b);

    return 0;
}
