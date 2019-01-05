# menentukan-bilangan-terkecil-dari-3-buah-bilangan-

    #include<stdio.h>
#include<conio.h>

int minimum (int x, int y, int z);
int main (void)
{
    int x, y, z, min;
    printf("masukkan bilangan 1 : ");scanf("%d",&x);
    printf("masukkan bilangan 2 : ");scanf("%d",&y);
    printf("masukkan bilangan 3 : ");scanf("%d",&z);
    min=minimum (x,y,z);
    printf("bilangan terkecil adalah %d",min);
    getch ();
}
int minimum (int x, int y, int z)
{
    int min;
    if (x>y) min=y;
    else min=x;
    if (z<min) min=z;
    return (min);
}

![img](https://raw.githubusercontent.com/VIKTORKEVIN/menentukan-bilangan-terkecil-dari-3-buah-bilangan-/master/menentukan%20bilangan%20terkecil%20dari%203%20buah%20bilangan.png)
