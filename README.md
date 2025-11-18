# bee1115-number-problem
<img width="692" height="412" alt="image" src="https://github.com/user-attachments/assets/471ffc50-8779-43aa-8495-e446e18c973b" />


[main.c](https://github.com/user-attachments/files/23599539/main.c)
#include <stdio.h>
#include <stdlib.h>

int main(){
int a,b;
while(1){
    scanf("%d %d",&a,&b);

        if(a==0 || b==0)break;

    if(a>0 && b>0)printf("primeiro\n");
    if(a>0 && b<0)printf("quarto\n");
    if(a<0 && b<0)printf("terceiro\n");
    if(a<0 && b>0)printf("segundo\n");


}
return 0;
}
