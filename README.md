#include<stdio.h>


int main()

{
    int ID [3][2]={{2001,1002}, 
                   
                    {53705,80085}, 
                   
                    {121518,181512}};
    int User, Pin;

    printf("Enter ID number: ");
    scanf("%d", &User);

    printf("Enter PIN: ");
    scanf("%d",&Pin);

 if(User == ID [0][0] && Pin== ID [0][1]) {
        printf("\nYou have successfully logged in\n");
        printf("ID# : %d\n", ID[0][0]);
        
    } else if (User == ID[1][0] && Pin == ID[1][1]) {
        printf("\nYou have successfully logged in\n");
        printf("ID# : %d\n", ID[1][0]);
        
    } else if (User == ID[2][0] && Pin == ID[2][1]) {
        printf("\nYou have successfully logged in\n");
        printf("ID# : %d\n", ID[2][0]);
        
    } else { printf("\n Invalid ID/PIN! \n"); }
    
      return 0;
}
