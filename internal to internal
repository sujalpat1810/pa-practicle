//memory exchange
#include<xc.h>
#include<stdio..h>
#include<stdlib.h>
#include<pic18f4550.h>

void main(void){
    int i=0;
    
    int source[]={0x50,0x10,0x60,0x25,0x80};
    int dest[]={0x00,0x00,0x00,0x00,0x00};
    for(i=0;i<5;i++){
        source[i]=dest[i];
    }
    TRISD=0;
    for(i=0;i<5;i++){
       PORTD=dest[i];
       for(int n=0;n<1000;n++){
           for(int j=0;j<500;j++){
               
           }
       }
    }
    return;
    
}
//memory transfer

#include<xc.h>
#include<stdio.h>
#include<stdlib.h>
#include<pic18f4550.h>

void main(void){
    int i,j,k;
    int source[]={0x1,0x2,0x3,0x4,0x5};
    int dest[]={0x06,0x7,0x8,0x9,0xa};
    
    for(i=0;i<5;i++){
        temp=source[i];
        source[i]=dest[i];
        dest[i]=temp;
    }
    TRISD=0;
    
    for(i=0;i<5;i++){
        PORTB=dest[i];
        PORTD=source[i];
        for(j=0;j<1000;j++){
            for(k=0;k<500;k++){
                
            }
        }
    }
    return;
    
}
