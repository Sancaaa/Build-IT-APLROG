#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int x;
    scanf("%d", &x);
    if (x%2 == 1){
        printf("Ganjil");
    } else {
        printf("Genap");
    }
    return 0;
}