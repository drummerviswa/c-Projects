#include <stdio.h>
    
int main()
{
float rupees,result;
int choice;
printf("Enter amount in Rupees\n");
scanf("%f",&rupees);
printf("Enter 1 for USD\n");
printf("Enter 2 for EUR\n");
printf("Enter 3 for AUS\n");
printf("Enter 4 for UAE Dirham\n");
scanf("%d",&choice);

switch (choice)
{
case 1:
result=rupees/73.04 ;
printf("%f Rupees is equivalent to %f USD\n",rupees,result);
break;
        
case 2:
result=rupees/88.82 ;
printf("%f Rupees is equivalent to %f EUR\n",rupees,result);
break;

case 3:
result=rupees/56.36 ;
printf("%f Rupees is equivalent to %f AUS\n",rupees,result);
break;

case 4:
result=rupees/19.89 ;
printf("%f Rupees is equivalent to %f Dirham\n",rupees,result);
break;

default:
printf("Please Enter the correct choice!");
break;
}
return 0;
}
