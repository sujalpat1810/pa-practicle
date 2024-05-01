#include<xc.h>
#include<stdio.h>
#include<stdlib.h>
#include<pic18f4550.h>

void main(void){
    int i,j,temp=0x00;
   int a={0x03,0x05,0x02,0x0a};
   for(i=0;i<4;i++){
       for(j=0;j<4-i;j++){
           if(a[j]>a[j+1]){
               temp=a[j];
               a[j]=a[j+1];
               a[j+1]=temp;
               
           }
       }
   }
 
   TRISD=0;
    for(i=0;i<4;i++) {
        PORTD=a[i];
        for(int n=0;n<1000;n++){
            for(j=0;j<500;j++){
                
            }
        }
    }
    
    for(i=0;i<4;i++){
       for(j=0;j<4-i;j++){
           if(a[j]<a[j+1]){
               temp=a[j];
               a[j]=a[j+1];
               a[j+1]=temp;
               
           }
       }
   }
 
   TRISB=0;
    for(i=0;i<4;i++) {
        PORTB=a[i];
        for(int n=0;n<1000;n++){
            for(j=0;j<500;j++){
                
            }
        }
    }
    return;
   
   
}
