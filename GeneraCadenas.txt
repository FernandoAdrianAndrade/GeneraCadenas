#include <stdio.h>
int main()
{
    char alfabeto[4] = {'a','0','1','b'};
    int i = 0;
    do{
        if(i <4){
            for(int j=0;j<4;j++){
                printf("%c",alfabeto[j]);
            }
            printf("%c",alfabeto[i]);
            printf("\n");
        }
        else{
            for(int j=3; j>-1; j--){
                printf("%c",alfabeto[j]);
            }
            printf("%c",alfabeto[i-1]);
            printf("\n");
        }
        i +=1;
    }while(i<5);
    return 0;
}
