#include <stdio.h>
int main() {
    int n, i, j;
    scanf("%d", &n);
   int  a=n - 1;
    for (i = 0; i < n; i++) {
        for (j = 0; j < a; j++)
            printf(" ");
        a--;
        for (j = 0; j < 2 * i + 1; j++)
            printf("*");
        printf("\n");
    }
     a=1;
    for (i = n - 1; i > 0; i--) {
        for (j = 0; j < a; j++)
            printf(" ");
        a++;
        for (j = 0; j < 2 * i - 1; j++)
            printf("*");
        printf("\n");
    }
    return 0;
}



