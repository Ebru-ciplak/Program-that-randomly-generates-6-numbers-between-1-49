# Program-that-randomly-generates-6-numbers-between-1-49
Program that randomly generates 6 numbers between 1 – 49
#include <stdio.h>
#include <stdlib.h>
int main()
{
    int c , n ;

    for ( c = 1 ; c <= 6; c++) {
    
    n = rand ( ) %49 + 1 ;
    printf ("%d\n" , n ) ;
}
    return 0;
}
