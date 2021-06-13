# guessing-name
//This is my first repository
// Online C compiler to run C program online
#include <stdio.h>
#include<stdlib.h>

int main()
{
int secretnumber=5;
int guess;
int guesscount=0;
int guesslimit=3;
int outofguesses=0;
while(guess != secretnumber && outofguesses==0)
{
    if(guesscount<guesslimit)
    {
    printf("enter a number:");
    scanf("%d",&guess);
    guesscount++;
    }
    else
    {
        outofguesses=1;
    }
}    
if (outofguesses==1)
{
    printf("outofguesses");
}
else
{
printf("you win");
}
return 0;
}
