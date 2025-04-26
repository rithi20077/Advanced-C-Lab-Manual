EXP NO:6 C PROGRAM PRINT THE LOWERCASE ENGLISH WORD CORRESPONDING TO THE NUMBER
Aim:
To write a C program print the lowercase English word corresponding to the number
Algorithm:
1.	Start
- Initialize an integer variable n.
2.	Input Validation
3.	Switch Statement cases.
-	Case 5: Print "seventy one"
-	Case 6: Print "seventy two"
-	Case 13: Print "seventy three"
-	...
-	Case 13: Print "seventy nine"
-	Default: Print "Greater than 13"
4.	Exit the program.
 
Program:

```
struct Node

{

    struct Node *prev;

    struct Node *next;

    float data;

}*head;



void search(float data)

{

    

    struct Node *temp;

    temp=head;

    float item=data;

    int i=0,flag;

    if(temp==NULL)

    {

        printf("List is empty");

    }

    else

    {

        while(temp!=0)

        {

            if(temp->data==item)

            {

                printf("item %.2f found at location %d",item,i+1);

                flag=0;

            }i++;

            temp=temp->next;

        }

    }

    if(flag!=0)

    {

        printf("Item not found");

    }   

}


```

Output:


![WhatsApp Image 2025-04-26 at 20 39 36_9568a938](https://github.com/user-attachments/assets/1f7cbdc5-c849-4b82-ad6a-5eda9d52ce44)


Result:
Thus, the program is verified successfully


 
EXP NO:7 C PROGRAM TO PRINT TEN SPACE-SEPARATED INTEGERS     IN A SINGLE  LINE DENOTING THE FREQUENCY OF EACH DIGIT FROM 0 TO 3 .
Aim:
To write a C program to print ten space-separated integers in a single line denoting the frequency of each digit from 0 to 3.
Algorithm:
1.	Start
2.	Declare char array a[50] outer loop for each digit from 0 to 3
3.	Initialize counter c to 0
4.	For each character in the string print count c for current digit, followed by a space
5.	Increment h to move to the next digit
6.	End
 
Program:

```
struct Node{
    int data; 
    struct Node *next;
}*head;


void insert(int data)
{
  struct Node *ptr;
  ptr=(struct Node*)malloc(sizeof(struct Node));
  struct Node *temp;
  if(head==NULL){
      head=ptr;
      head->data=data;
      ptr->next=NULL;
      return;
  } 
  temp=head;
  while(temp->next!=NULL){
      temp=temp->next;
  }
  ptr->data=data;
  ptr->next=NULL;
  temp->next=ptr;
}

```


Output:


 ![WhatsApp Image 2025-04-26 at 20 39 57_35ab0d93](https://github.com/user-attachments/assets/1d775627-eca9-4203-aa25-e5aff2d756c8)


Result:
Thus, the program is verified successfully




EXP NO:8 C PROGRAM TO PRINT ALL OF ITS PERMUTATIONS IN STRICT LEXICOGRAPHICAL ORDER.
Aim:
To write a C program to print all of its permutations in strict lexicographical order.

Algorithm:
1.	Start
2.	Declare variables s (pointer to an array of strings) and n (number of strings)

3.	Memory Allocation
Dynamically allocate memory for s to store an array of strings
4.	Input
Read the number of strings n from the user Dynamically allocate memory for each string in s
5.	Permutation Generation Loop
6.	Memory Deallocation
Free the memory allocated for each string in s Free the memory allocated for s
7.	End
 
Program:

```
struct Node
{
    struct Node *prev;
    struct Node *next;
    int data;
}*head;

void display()
{
    while(head!=NULL)
    {
        printf("%d\n",head->data);
        head=head->next;
    } 
}

```

Output:


![WhatsApp Image 2025-04-26 at 20 40 20_b9078266](https://github.com/user-attachments/assets/ee02ec65-6c8f-4dc0-9f82-5c41e8980868)



Result:
Thus, the program is verified successfully



 
EXP NO:9 C PROGRAM PRINT A PATTERN OF NUMBERS FROM 1 TO N AS
SHOWN BELOW.
Aim:
To write a C program to print a pattern of numbers from 1 to n as shown below.
Algorithm:
1.	Start
2.	Declare integer variables n, i, j, min
3.	Read the value of n from the user
4.	Calculate the length of the side of the square matrix: len = n * 2 - 1
5.	Matrix Generation Loop
6.	Calculate min as the minimum distance to the borders
7.	End
 
Program:

```
struct Node
{
    struct Node *prev;
    struct Node *next;
    char data;
}*head;

void insert(char data)
{
    struct Node *n=(struct Node *)malloc(sizeof(struct Node *));
    struct Node *temp;
    if(head==NULL)
    {
        head=n;
        head->data=data;
        n->next=NULL;
        return;
    }
    temp=head;
    while(temp->next!=NULL)
    {
        temp=temp->next;
    }
    n->data=data;
    n->next=NULL;
    temp->next=n;
    
    
}
```

Output:


![WhatsApp Image 2025-04-26 at 20 40 41_81d36325](https://github.com/user-attachments/assets/fa3a5ac7-f002-46d8-afd0-f45b2f2b8a73)


Result:
Thus, the program is verified successfully



EXP NO:10 C PROGRAM TO FIND A SQUARE  OF NUMBER USING FUNCTION WITHOUT ARGUMENTS WITH RETURN TYPE

Aim:

To write a C program that calculates the square of a number using a function that does not take any arguments, but returns the square of the number.

Algorithm:

1.	Start.
2.	Define a function square() with no parameters. This function will return an integer value.
3.	Inside the function:
o	Declare an integer variable to store the number.
o	Ask the user to input a number.
o	Calculate the square of the number (multiply the number by itself).
o	Return the squared value.
4.	In the main function:
o	Call the square() function and display the result.
5.	End.

Program:

```
struct Node
{
    char data; 
    struct Node *next;
}*head;
void delete()
{
    if(head != NULL)
    {
        head = head->next;
        printf("Node deleted from the begining ...\n");
    }
    else
    {
       printf("List is empty");
    }
}
```
Output:


![WhatsApp Image 2025-04-26 at 20 41 01_87deaaef](https://github.com/user-attachments/assets/38fcbef2-a156-49cb-bf3a-84867ab5060e)


Result:
Thus, the program is verified successfully



























