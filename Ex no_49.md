# EX 49 C function to search an element in the doubly linked list.
## DATE:
## AIM:
To write a C function to search an element in the doubly linked list.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to search an element in the double linked list..
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End  

## Program:
```
/*
C function to search an element in the doubly linked list.


struct Node 
{ 
struct Node *prev; 
struct Node *next; 
int data; 
}*head; 
 
void search(int data) 
{ 
struct Node *temp; 
int item=data,i=0,flag; 
temp=head; 
if(temp==NULL) 
{ 
printf("Empty list\n"); 
} 
else{ 
while(temp!=NULL) 
{ 
if(temp->data == item) 
{ 
 
 SAVEETHA ENGINEERING COLLEGE  
printf("item %d found at location %d",item,i+1); 
flag=0; 
} 
i++; 
temp=temp->next; 
} 
if(flag!=0) 
{ 
printf("Item not found\n"); 
} 
}
*/
```

## Output:
<img width="1015" height="536" alt="image" src="https://github.com/user-attachments/assets/9e91dc40-3f5d-42e8-99fe-a59d7f7f827d" />



## Result:
Thus the program was executed and the output was verified successfully.
