# CHAPTER-03 DECISION CONTROL INSTRUCTIONS

## The if-else Statement :
* General form -
* if (this condition is true)
*               statement 1;
* else
*              statement 2;
* If there are more than 1 statements then if is  enclosed within a pain of parentheses.
* ==,!=,<,>,<=,>= [RELATIONAL OPERATORS]
* == **COMPARISION OPERATOR**
* = **ASSIGNMENT OPERATOR**

## Nested if-elses :-
* Writing another if-else within either if or else block. This is called "nesting".
* Ex:- if (i==2)
*           printf ("More questions you ask \n");
*      else
*      {
*         if (i == 3)
*            printf ("Ask a doubt ? \n");
*         else
*            printf ("Thankyou ");
*      }


## A Word Of Caution :-
* Any valid expression will also work.
* Ex = if (a=10)
*         printf ("This works! ");
* In C, a non-zero value is considered to be true and **0** is considered false.
* In the above example, a has a non-zero value, so printf gets executed.

## Common Mistake -
* Ex:- if (i==5);
*           printf ("You entered 5 \n");
* This statement gets executed as follows : 
* if (i==5)
*   ;
* printf ("You entered 5 \n");
* Here if **_i=5_** then a null statement and printf() statement gets executed.
* If **_i!=5_** then only printf() statement is executed.
