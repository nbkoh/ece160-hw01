#include <stdio.h>
#include <stdlib.h>

int main(int argc, char* argv[])
{
    //printf("Input as following --> Operator value1 value2\n");
    float result;
    //scanf("%c %d %d", &operator, &valueone, &valuetwo);
    
    if(argc == 1 || argc > 4)
    {
        printf("Wrong Input\n");
        return (-1);
    }
    
    int operator = *argv[1];
    float valueone = atof(argv[2]);
    float valuetwo = atof(argv[3]);

    if(operator == 120)
    {
        result = valueone * valuetwo;
    }
    
    else if(operator == 43)
    {
        result = valueone + valuetwo;
    }
    
    else if(operator == 45)
    {
        result = valueone - valuetwo;
    }
    
    else if(operator == 47)
    {
        result = valueone / valuetwo;
    }
    
    else
    {
        printf("Wrong Operator Input\n");
        return 0;
    }
    
    printf("The result is: %.2f \n", result);
    return 0;
    
}
