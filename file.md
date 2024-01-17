#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <stdlib.h>
#include <unistd.h>

int main()
{
    for(int i = 0; i < 10; i++)
    {
    for(int j = 0; j < 10; j++)
    {
        if (j > i)
        break;
        
        printf("%2d ", i * 10 + j);
    }
        printf("\n");
    }

    
    return 0;
}
