c ++
help me please // Eu tenho que criar um loop de repetição que imprima 60 valores aleatórios (de 1 a 100), mas os valores impressos 
não podem ser repetidos. // Idioma: C // Vou escrever o código de forma simplificada, porque o foco não é a sintaxe, mas a lógica.

#include <stdio.h> #include <conio.h> #include <stdlib.h> int main (void) {int i;

printf ("Gerando 10 valores aleatórios: \ n \ n");

para (i = 0; i = 60; i ++) 
{
/ * gerando valores aleatórios entre zero e 100 * / 
printf ("% d", rand ()% 100); 
}

getch (); return 0; }

© 2018 GitHub , Inc.
