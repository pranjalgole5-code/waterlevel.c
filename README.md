#include <stdio.h>

int main()
{
    int level;

    printf("Enter water level: ");
    scanf("%d", &level);

    if (level < 30)
    {
        printf("Low Level");
    }
    else
    {
        if (level <= 70)
        {
            printf("Normal Level");
        }
        else
        {
            printf("High Level");
        }
    }

    return 0;
}
