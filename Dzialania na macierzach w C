#include <stdio.h>
#include <stdlib.h>

int main()
{
    int tab1[4][4];
    int tab2[4][4];
    int wynik[4][4];
    int wynik1[4][4];
    int tranpoz1[4][4];
    int tranpoz2[4][4];
    int numer;
    int num;
    jump:
    printf("\n\n DZIALANIA NA MACIERZACH \n\n");

    printf("1.Dodawanie dwoch macierzy 4x4.\n2.Odejmowanie dwoch macierzy 4x4.\n3.Mnozenie macierzy 4x4 przez skalar.\n4.Transpozycja macierzy 4x4. \n5.Koniec\nPodaj numer dzialania ktore chcesz wykonac: ");
    scanf("%d",&numer);


    if(numer !=1 && numer!=2 && numer!=3 &&numer!=4)
    {
        printf("Program zakonczyl dzialanie, podano niepoprawny numer lub numer 5.\n");
        exit(0);
    }
    else{
    //branie dwoch macierzy od uzytkownika
    printf("Podaj liczby do pierwszej macierzy:\n");
    for(int i=0;i<4;i++)
    {
        for(int j=0;j<4;j++)
        {
            printf("Podaj %d element w macierzu: ",j+1);
            scanf("%d",&tab1[i][j]);
        }
        printf("\n");
    }
    printf("\n\n\n");

    printf("Podaj liczby do drugiej macierzy:\n");
    for(int i=0;i<4;i++)
    {
        for(int j=0;j<4;j++)
        {
            printf("Podaj %d element w macierzu: ",j+1);
            scanf("%d",&tab2[i][j]);
        }
        printf("\n");
    }
    }

    switch(numer)
    {
    case 1:
        for(int i=0;i<4;i++)
        {
            for(int j=0;j<4;j++)
            {
            wynik[i][j]= tab1[i][j] + tab2[i][j];
            printf("%6d + %d = %d",tab1[i][j],tab2[i][j],wynik[i][j]);
            }
        printf("\n");
        }
        goto jump;
        break;

    case 2:
        for(int i=0;i<4;i++)
        {
            for(int j=0;j<4;j++)
            {
            wynik[i][j]= tab1[i][j] - tab2[i][j];
            printf("%6d - %d = %d",tab1[i][j],tab2[i][j],wynik[i][j]);
            }
        printf("\n");
        goto jump;
        break;
        }
    case 3:
        printf("Podaj numer przez ktory chcesz pomnozyc macierze: ");
        scanf("%d", &num);

        for(int i=0;i<4;i++)
        {
            for(int j=0;j<4;j++)
            {
            wynik[i][j]= num * tab1[i][j];
            printf("%4d * %d = %d",num,tab1[i][j],wynik[i][j]);

            }
        printf("\n");
        }

        printf("\n\n");

        for(int i=0;i<4;i++)
        {
            for(int j=0;j<4;j++)
            {

            wynik1[i][j]= num * tab2[i][j];
            printf("%4d * %d = %d",num,tab2[i][j],wynik1[i][j]);
            }
        printf("\n");
        }
        goto jump;
        break;
    case 4:
        for(int i=0;i<4;i++)
        {
            for(int j=0;j<4;j++)
            {
            tranpoz1[4][4]=tab1[i][j];
            printf("%d\t",tranpoz1[4][4]);
            }
        printf("\n");
        }

        printf("\n\n");

        for(int i=0;i<4;i++)
        {
            for(int j=0;j<4;j++)
            {
            tranpoz2[4][4]=tab2[i][j];
            printf("%d\t",tranpoz2[4][4]);
            }
        printf("\n");
        }
        goto jump;
        break;
    default:
        break;

    }
    return 0;
}
