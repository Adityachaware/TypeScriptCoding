# TypeScriptCoding
--------------------------------------------------------------
while using enum ,

don't use 
enum rollNumber {
}

this syntax , instead use below

const enum rollNumber {

}

because enum rollNumber will create lot of javaScript code while compiling (while compiling to javascript it will create iife function which slows down the execution if lot of enums are used in the project. )

--------------------------------------------------------------

2) In typescript for setter method we cannot give return type.

example. set name(n): string {} not allowed to give string return type.

correct way : set name(n){}