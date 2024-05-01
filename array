#include<xc.h>
#include<stdlib.h>
#include<pic18f4550.h>

void main(void){
    int a[]={0x03,0x04,0x05};
    int add=0x00;
    int i;
    
    for(i=0;i<3;i++){
        add=add+a[i];
    }
    
    TRISD=0;
    PORTD=add;
    
    return;
    
    
    
}
