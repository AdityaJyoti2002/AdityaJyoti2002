- š Hi, Iām @AdityaJyoti2002
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
AdityaJyoti2002/AdityaJyoti2002 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
int main(){
    int i, j, n;
    printf("Enter the number =");
    scanf("%d", &n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n;j++){
            if(i==1 || j==1 || n==i || j==n){
                printf("#");
            }
            else{
                printf(" ");

            }
        }
        printf("\n");
    }
    return 0;
}
