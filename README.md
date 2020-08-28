// Switch-statement-conditional-statements-program-.-Food-and-its-price
// it is a program which will tell the name of the food item and the price by taking input from the user as the serial no. of that food item.
#include<stdio.h>
int main()
{
printf("1.Pizza,Rs 239\n2.Burger,Rs 129\n3.Pasta,Rs 179\n4.French Fries,Rs 99\n5.Sandwich,Rs 149\n\n");
int x;
printf("Enter a number:");
scanf("%d",&x);
switch(x)
{
    case 1:printf("Food item-Pizza\nPrice-Rs 239");
        break;
    case 2:printf("Food item-Burger\nPrice-Rs 129");
        break;
    case 3:printf("Food item-pasta\nPrice-Rs 179");
        break;
    case 4:printf("Food item-French Fries\nPrice-Rs 99");
        break;
    case 5:printf("Food item-Sandwich\nPrice-Rs 149");
        break;
    default:printf("Food item not in list(Wrong entry)");
}
return 0;
}
