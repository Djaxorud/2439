#include<stdio.h>

int main(void) {
	int i;
	int j;
	int n;
	scanf_s("%d", &n);
	for (i = 1; i <= n; i++) {
		for (j = 0; j < i; j++)
			putchar('*');
		putchar('\n');
	}
	return 0;
}
