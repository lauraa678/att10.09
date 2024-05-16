# att10.09

#include  <stdio.h>
#include  <stdlib.h>

int  principal (){

	raio flutuante;

	printf ( "Escreva o valor do raio da circunferência:" );
	scanf ( "%f" , & raio );

	float  diametro =  raio * 2;
	float  comprimento =  2 * 3,14 * raio;
	área   flutuante =  3,14 * raio * raio;

	printf ("\nO diâmetro dessa circunferência e: %f", diametro);
	printf ("\nO comprimento dessa circunferência e: %f", comprimento);
	printf ("\nA área dessa circunferência e: %f", área);

	retornar 0;
}
