#include "stdio.h"
void menu()
{
printf("**************\n"); 
printf("****0.exit****\n"); 
printf("****1.play****\n"); 
printf("**************\n"); 
return;
}
void game(){
}
void choice()
{
int input=1;
printf("plese choice:\n");
while(input)
{switch(input)
{
scanf("%d",input);
case 0:printf("game is over!\n");break;
case 1:game();break;
default:printf("plese choice again:\n");break;
}
}
}
int main()
{
menu();
choice();	
return 0;
} 
