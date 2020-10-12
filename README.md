# Linked List Project

You will be writing a statically allocated linked list in ARM assembly.

# Steps You Should Follow

## Step 1
You will statically allocate some space for your link list elements.
You need to make 5 elements, each elements should have two components, the next pointer first then the value stored.
First inialize next pointer to `NULL`.
The value stored at the address will be a string pointer.


## Step 2
You will then write a function that links the statically alloacted linked list elements together.

## Step 3
In your main you call your linking function to link all 5 elements together.

## Step 4
Print out each emement in order by traversing the list.
This means that you can't store each address in registers.
You will lose points if you just print everything.

# Grading
You must have a make file of you can only get 25/50
If you upload your file from a web browser you will only get 25/50 you must use the command line commands discussed in class (git add, git commit, etc)
If the code does not compile you get a 0
Partial credit will be given based on the performance of the program

# Extra credit
Use the malloc call to allacte for n (any number of entries represented by the letter n) entries from the command line. (15 points of extra credit)
