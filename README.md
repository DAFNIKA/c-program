# c-program
#include<stdio.h>
int main()
{
 int i,ans,point=0;
 int point1,point2,point3,point4,point5;
 printf("\n******lets play with quiz*****");
 printf("\npress 7 to start the quiz");
 printf("\npress 0 to end the quiz");
 scanf("\n%d",&i);
 if(i==7)
 {
    printf("\nNow the quiz begin ");
    printf("\nQ1.Who is the father of C language?");
    printf("\n1) Steve Jobs");
    printf("\n2) James Gosling");
    printf("\n3) Dennis Ritchie");
    printf("\n4) Rasmus Lerdorf");
    scanf("\n%d",&ans);
    if(ans==3)
    {
      printf("\nCorrect answer");
      printf("\nYou scored 5 points"); 
      point1=5;
      point=point+point1; /* code */
    }
    else
    {
        printf("\nOops,Wrong answer");
    }
    printf("\nQ2.Which of the following is not a valid C variable name?");
    printf("\n1)int number; ");
    printf("\n2)float rate; ");
    printf("\n3)int variable_count; ");
    printf("\n4)int $main:");
    scanf("\n%d",&ans);
    if(ans==4)
    {
      printf("\nCorrect answer");
      printf("\nYou scored 5 points");  /* code */
      point2=5;
      point=point+point2;
    }
    else
    {
        printf("\nOops,Wrong answer");
    }
    printf("\nQ3.All keywords in C are?");
    printf("\n1)LowerCase letters");
    printf("\n2)UpperCase letters ");
    printf("\n3)both");
    printf("\n4)none");
    scanf("\n%d",&ans);
    if(ans==1)
    {
      printf("\nCorrect answer");
      printf("\nYou scored 5 points");  /* code */
      point3=5;
      point=point+point3;
    }
    else
    {
        printf("\nOops,Wrong answer");
    }
    printf("\nQ4.Which keyword is used to prevent any changes in the variable within a C program?");
    printf("\n1)immutable");
    printf("\n2)mutable");
    printf("\n3)const");
    printf("\n4)none");
    scanf("\n%d",&ans);
    if(ans==3)
    {
      printf("\nCorrect answer");
      printf("\nYou scored 5 points");  /* code */
      point4=5;
      point=point+point4;
    }
    else
    {
        printf("\nOops,Wrong answer");
    }
    printf("\nQ5.What is an example of iteration in C?");
    printf("\n1)if");
    printf("\n2)do-while");
    printf("\n3)while");
    printf("\n4)all of the mentioned");
    scanf("\n%d",&ans);
    if(ans==4)
    {
      printf("\nCorrect answer");
      printf("\nYou scored 5 points");  /* code */
      point5=5;
      point=point+point5;
    }
    else
    {
        printf("\nOops,Wrong answer");
    }
    printf("\n----Quiz completed----");
    printf("\nYour score : %d",point);
 }
 else if(i==0)
 {
    printf("quiz ends########");
 }
 else
 {
     printf("---invalid value---enter value again.");
 }
}
