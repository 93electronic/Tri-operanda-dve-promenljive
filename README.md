#include <stdio.h>
void main()
{
	int a, b, c;
	char q, w;
	scanf("%d%c%d%c%d", &a, &q, &b, &w, &c);
	if (q == '+' && w == '+')
		printf("Rezultat je: %d", a + b + c);
	else if (q == '+' && w == '*')
		printf("Rezultat je: %d", a + b * c);
	else if (q == '*' && w == '+')
		printf("Rezultat je: %d", a * b + c);
	else if (q == '*' && w == '*')
		printf("Rezultat je: %d", a * b * c);

}
