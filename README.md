# Lists-in-C
Hello all! I need to know how can I compare elements of two lists. Like the number of stock must be bigger than number of request. The output should be like this: "Enter number of materials: 4/stock: 12 13 14 15 /request: 1 1 1 1/Order accepted/".Please i need some help. 
This is my code so far.


#include <stdlib.h>
#include <stdio.h>

struct Node
{
    int data;
    struct Node* next;
};


   struct Node* stock = NULL;
   struct Node* request = NULL;



   void Insert1(int data,struct Node* stock)
   {  struct Node* temp = (struct Node*)malloc(sizeof(struct Node));
      temp -> data = data;
      temp -> next = NULL;
      stoc = temp;

   }
   void Insert2(int data,struct Node* request)
     {
       struct Node* temp = (struct Node*)malloc(sizeof(struct Node));
      temp -> data = data;
      temp -> next = NULL;
      cerere = temp;
      }


    





int main()
{ int n,i,x;
  
   printf("Enter number of materials: ");
   scanf("%d",&n);
   if(n<0 || n >= 20) printf("Number of materials is incorrect!");

   for(i = 0; i < n; i++)
   {
       int x;
       scanf("%d",&x);
       Insert1(x,stock);
       compare();

   }

    for(i = 0; i < n; i++)
   {
       int y;
       scanf("%d",&y);
       Insert2(x,request);
     }
}
