#include<stdio.h>
void main()
{
    double year,age;
    printf("enter your year of birth ");
    scanf("%lf",&year);
    age=2021-year;
    printf("you are %.0lf\n",age);
    if(age>=18)
    {
        printf("you are major\n");
        printf("you can vote\n");
    }
    else
    {
        printf("you are minor \n");
        printf("you can't vote \n");
    }
}
