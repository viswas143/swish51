
#include<stdio.h> 
int main() 
{ 
float x,p,amount=0.0; 
scanf("%f%f",&x&p); while(x>0) 
{ if(x>=1.0) amount+=x; 
x-=((p*x)/100.0); 
} 
printf("\n%f",amount); 
}
