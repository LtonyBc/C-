#include <stdio.h>
#include <conio.h>

int main () {
    float a,b,c,d,e,F;
    
    printf ("Digite um valor: ");
    scanf ("%f", &a);
    printf ("Digite o Numero da sua Matricula: ");
    scanf ("%f", &b);
    c = a / b;
	printf (" Resultado  %.2f", c)     ;
	d=c>2;
    e=c<2;
    F= if(c=1);
    
	printf ("Voce escolheu um numero mais de duas vezes maior que o meu %.2f",d);
	scanf("%f",&d);
    printf("Voce escolheu um numero quase igual ao meu %.2f",e);
    scanf("%f",&e);
    printf("Voce escolheu um numero igual ao meu %.2f",F);
    scanf("%f",&F);
getch ();
return (0);
