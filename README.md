# VASQUEZ_FAHRENHEIT
FAHRENHEIT CODE
#include <stdio.h>

 int main() {

// Write C code her

float fahrenheit;

float celsius;


//input: fahrenheit

printf ("Input a fahrenheit value: ");

scanf ("%f",&fahrenheit);

printf("Fahrenheit = %.2\n",fahrenheit);


//process

celsius = (fahrenheit - 32) * 5 / 9;

//output: celsius

printf("\nCelsius - %.2f",celsius);

return 0;

}