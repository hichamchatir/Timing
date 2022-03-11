// HorairProject helps you to count the horair after the data which is given by the user for example we enter 23 as hours,44 as minutes and 33 as second then he starts counting with this time until midnight and starts counting with 00:00:00

#include <stdio.h>
#include <stdlib.h>

int main()
{
printf("Entrez l'heure exacte (sous format HH:MM:SS)\t");
    int h=0,m=0,s=0;
    printf("H:");
    scanf("%d",&h);
    printf("M:");
    scanf("%d",&m);
    printf("S:");
    scanf("%d",&s);
    for(h; h<=24; h++) {
       if(h==24) {
            h=0;
        }

        for(m; m<60; m++) {
            for (s; s<60; s++) {
                printf("\n\n\n\n\n\n\n\t\t\t\t%2d:%2d:%2d",h,m,s);
                for (double i=0;i<55999999;i++) {
                    i++;
                    i--;
                }
                system("cls");
            } s=0;

        } m=0;

    }
    return 0;
}


