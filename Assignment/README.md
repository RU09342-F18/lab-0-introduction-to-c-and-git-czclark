#
/*
 * math.h
 *
 *  Created on: Aug 22, 2017
 * 	Last Edited: Sept 7, 2018
 *      Author: Russell Trafford
 */

/* Your assignment is to take the math function and implement at least the following functions:
 * + Add (num1 + num2)
 * - Subtract (num1 - num2)
 * * Multiply (num1 * num2)
 * / Divide (num1 / num2)
 * % Modulus (num1 % num2)
 * < Left Shift (num1 << num2)
 * > Right Shift (num1 >> num2)
 * & Bitwise AND (num1 & num2)
 * | Bitwise OR (num1 | num2)
 * ^ Bitwise XOR (num1 ^ num2)
 * ~ Bitwise Inverse (~num1) for this operation, num1 and num2 are still needed
*/

//Part of your documentation should be listing the valid inputs and outputs for the functions you create.


// MY CODE STARTS HERE         /////////////////////////////////////////////////////////////////////////////////////////////////

// math.h

#include <stdio.h>

#ifndef MATH_H_
#define MATH_H_

// The following math function only work with integers
// Fractions/Decimals cannot be used

int math(int num1, int num2, char Operator);


#endif /* MATH_H_ */

// Implementation file
// math.c


int math(int num1, int num2, char Operator)
{

    int Result;
    
// Symbols for operators for each operation must be entered 
// exactly as shown below (under switch statement)

    switch(Operator)
    {
        +: // If operator entered is a "+", perform addition 
        
           Result = num1 + num2;
           printf(num1 "+" num2 "="
        
        -: // If operator entered is a "-", perform subtraction 

           Result = num1 - num2;
           
        *: // If operator entered is a "*", perform multiplication 

           Result = num1 * num2;

        /: // If operator entered is a "/", perform division 

           Result = num1 / num2;

        %: // If operator entered is a "%", perform modulo operation 

           Result = num1 % num2;
        
        <: // If operator entered is a "<", left shift by specified amount (Num2)
        
           Result = num1 << num2;        
        
        >: // If operator entered is a ">", right shift by specified amount (Num2)
        
           Result = num1 >> num2;
        
        &: // If operator entered is a "&", perform a logical AND operation
        
           Result = num1 & num2;
        
        |: // If operator entered is a "|", perform a logical OR operation
          
           Result = num1 | num2;
        
        ^: // If operator entered is a "^", perform a logical XOR operation
        
           Result = num1 ^ num2;
        
        ~: // If operator entered is a "~", negate num1
        
           Result = ~num1;
        
   default: // If none of the above symbols are used, 
            // Prompt user to restart program    
    }
   
    return Result;
}

#endif /* MATH_H_ */


