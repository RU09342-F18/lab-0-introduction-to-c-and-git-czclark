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



#include <stdio.h>

#ifndef MATH_H_
#define MATH_H_


int math(int num1, int num2, char Operator)
{
   
   int Result;
    
    switch(Operator)
    {
        +: // If operator entered is a "+", perform addition 
        
        -: // If operator entered is a "-", perform subtraction 
        
        *: // If operator entered is a "*", perform multiplication 
        
        /: // If operator entered is a "/", perform division 
        
        %: // If operator entered is a "%", perform modulo operation 
        
        <: // If operator entered is a "<", left shift by specified amount (Num2)
        
        >: // If operator entered is a ">", right shift by specified amount (Num2)
        
        &: // If operator entered is a "&", perform a logical AND operation
        
        |: // If operator entered is a "|", perform a logical OR operation
        
        ^: // If operator entered is a "^", perform a logical XOR operation
        
        ~: // If operator entered is a "~", negate num1
        
   default: // If none of the above symbols are used, 
            // Prompt user to select a different symbol
   
    }
   
    return Result;
}


int main()
{
    int num1;
    int num2;
    char Operator;
    
    
    math (num1, num2, Operator);
    return 0;
}

#endif /* MATH_H_ */


