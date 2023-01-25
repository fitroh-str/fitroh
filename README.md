#include <stdio.h>
int main()
{
	int tebakan;
	printf("tebak dari angka 1 sampai 10\n");
	scanf("%d", &tebakan);
	switch (tebakan) 
	{
		case 1:
		printf("terlalu kecil, coba lagi");
		break;
		case 5:
		printf("tepat sekali !. anda menang");        break;
		case 10:
		printf("terlalu besar, coba lagi");
		default:
		printf("angka yang anda masukan salah coba lagi ");
	}
	return 0;
;}
