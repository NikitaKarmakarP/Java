# Java
This is my java repository, where I upload my all java code which I done. Stay connect with me.

# If-Else Statement
# Syntax of If-else statement in Java :

if (condition-to-be-checked) {

	statements-if-condition-true;
 
}

else {

	statements-if-condition-false;
 
} 


# If-else ladder : 
1) Instead of using multiple if statements, we can also use else if along with if thus forming an if-else-if-else ladder.
2) Using such kind of logic reduces indents.
3) Last else is executed only if all the conditions fail.
# SYNTAX
 if (condition1) {

           //Statements;
else if {
 
            // Statements;

 }

 else {

# Switch Case Statements in Java
# SYNTAX:
/*
Switch(var) {
 	Case C1:
 		//Code;	
 		break;
 	Case C2:
 		//Code;
 		break;	
 	Case C3:
		//Code
		break;
	default:
		//Code
*/

*In programming languages, loops are used to execute a particular statement/set of instructions again and again.
*The execution of the loop starts when some conditions become true.
*For example, print 1 to 1000, print multiplication table of 7, etc.
*Loops make it easy for us to tell the computer that a given set of instructions need to be executed repeatedly.

# Types of Loops :
Primarily, there are three types of loops in Java:

1) While loop
2) do-while loop
3) for loop
# Let's look into these, one by one.

# While loops :
1) The while loop in Java is used when we need to execute a block of code again and again based on a given boolean condition.
2) Use a while loop if the exact number of iterations is not known.
3) If the condition never becomes false, the while loop keeps getting executed. Such a loop is known as an infinite loop.

# SYNTAX
/*
while (Boolean condition)

{

            // Statements    -> This keeps executing as long as the condition is true.

}
*/

# Example : 
int i=10;  
while(i>0){  
System.out.println(i);  
i--;  
}  

# The do-while loop in Java

# Do-while loop:
1) Do- while loop is similar to a while loop except for the fact that it is guaranteed to execute at least once.
2) Use a do-while loop when the exact number of iterations is unknown, but you need to execute a code block at least once.
3) After executing a part of a program for once, the rest of the code gets executed on the basis of a given boolean condition.

# Syntax :
/* do {

            //code

} while (condition);            //Note this semicolon */

# Example : 
int i=1;  
do{  
System.out.println(i);  
i++;  
}while(i<=10); 
