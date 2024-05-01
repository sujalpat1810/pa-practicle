#include<xc.h>
#include<stdio.h>
#include<pic18f4550.h>
#include<pic18f4550.h>

void main(void){
    int a,b;
    a=0x03;
    b=0x02;
    int mult=0x00;
    
    mult=a*b;
    
    TRISD=0;
    PORTD=mult;
    
    int div=0x00;
    div=a/b;
    
    TRISB=0;
    PORTB=div;
    return;
}
