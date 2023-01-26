# sourcecode

```
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    // Write C code here
    int a [2][2] = {1 ,2,
                    3, 4};
    int b [2][2];

    int n =2,i,j;
    printf("Input Array ");
    for (i = 0; i < n; i++) {
        for (j = 0; j < n; j++) {
            printf("%i\t",a[i][j]);
        }
        printf("\n");
    }
    
    
    for(i = 0;i<n; i++){
        for(j=0;j<n;j++){
        int result = a[i][0] * a[j][1]; 
        printf("%i\t",result);    
        }
        printf("\n");
    }
    return 0;
    
}

```
