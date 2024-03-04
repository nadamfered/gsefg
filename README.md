# gsefg#include <stdio.h>
#include <conio.h>
#include <string.h>#include <stdio.h>
#include <conio.h>
#include <string.h>

void main()
{
	char i, s[30];
	FILE * f;
	clrscr();
	f = fopen("DSSV.TXT", "w");
	i = 1;
	printf("Nhap ho ten cua tung hoc sinh, ket thuc go Enter\n");
	do {
		printf("Ho ten hoc sinh thu %d : ", i++);
		gets(s);
		if (strlen(s) > 0)
		{
			strcat(s, "\n");
			fputs(s, f);
		}
	} while (strlen(s) > 0);
	fclose(f);i++);
		scanf("%d", &x);
		fprintf(fp, "%d ", x);
		printf("Tiep tuc nhap ? (c/k) : ");
		fflush(stdin);
		t = getchar();
	} while ((t == 'c') || (t == 'C'));
	fclose(fp);
	fp = fopen("tepsn.dat", "r");
	ts = sd = 0;
	if (!feof(fp))
	{
	clrscr();
	f = fopen("DSSV.TXT", "r");
	printf("Danh sach hoc sinh doc tu tep :\n\n");
	i = 1;
	while (fgets(s, 30, f))
	{
		printf("%d. ", i++);
		puts(s);
	}

	fclose(f);
	getch();
}****
	fclose(f);
	clrscr();
	f = fopen("DSSV.TXT", "r");
	printf("Danh sach hoc sinh doc tu tep :\n\n");
	i = 1;
	while (fgets(s, 30, f))
	{i++);
		scanf("%d", &x);
		fprintf(fp, "%d ", x);
		printf("Tiep tuc nhap ? (c/k) : ");
		fflush(stdin);
		t = getchar();
	} while ((t == 'c') || (t == 'C'));
	fclose(fp);
	fp = fopen("tepsn.dat", "r");
	ts = sd = 0;
	if (!feof(fp))
	{i++);
		scanf("%d", &x);
		fprintf(fp, "%d ", x);
		printf("Tiep tuc nhap ? (c/k) : ");
		fflush(stdin);
		t = getchar();
	} while ((t == 'c') || (t == 'C'));
	fclose(fp);
	fp = fopen("tepsn.dat", "r");
	ts = sd = 0;
	if (!feof(fp))
	{
		printf("%d. ", i++);
		puts(s);
	}

	fclose(f);
	getch();
}
