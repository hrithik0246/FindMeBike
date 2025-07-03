#include<stdio.h>
#include<stdlib.h>

void _125cc(){
    printf("1.DUKE125\n");
    printf("2.NS125\n");
    printf("3.RC125\n");

}

void _200cc(){
    printf("1.DUKE200\n");
    printf("2.NS200\n");
    printf("3.xpulse200\n");

}

void _300cc(){
    printf("1.CB300\n");
    printf("2.TNT 300\n");
    printf("3.NINJA 300\n");

}




int main(){
    int cc;

    printf("enter cc of bike you are looking for");
    scanf("%d",&cc);


    switch(cc){
        case 125:
            _125cc();
            break;

        case 200:
        _200cc();
        break;

         case 300:
        _300cc();
        break;

        default:
        printf("enter valid input");

    
    }

    return 0;
