#include <stdio.h>

int main() {
    int n, i, j, h;
    printf("Enter the size of matrix: ");
    scanf("%d", &n);
 
    int a[n][n];

    printf("Enter elements :");
    for(i = 0; i < n; i++) {
        for(j = 0; j < n; j++) {
            scanf("%d", &a[i][j]);
        }
    }

    for(i = 0; i < n; i++) {
        for(j = i + 1; j < n; j++) {
            h= a[i][j];
            a[i][j] = a[j][i];
            a[j][i] = h;
        }
    }

    printf("Matrix:");
    for(i = 0; i < n; i++) {
        for(j = 0; j < n; j++) {
            printf("%d ", a[i][j]);
        }
        printf("\n");
    }

    return 0;
}
