JavaScript/TypeScript Intro 

Variables 
  Syntax 
  Data Type 
  Operation example Mathematical operation on numbers 

Logical Operations 

Conditional Statemets 

Loops 

Function or Method - 

Object Oriented 

__________ 
How do you use JavaScript

on its own file with file extension .js we have to use script element to add it to the html page 

Variables : Temporary Storage
The keyword used to create any variable is 
var, let, const

var ageOfTesfaye = 22;

What is JSON
What is JS Object 
How do you convert JS Object to JSON 
 Ans: JSON.Stringfy(JSObject)

How to convert JSON to JS Object 
Ans: JSON.Parse(JasonVar)


Assignment operator is = 


Logical Operators 

Compare equality ( when equal in value ) == 
Similarity ( when value and type is the same ) === 
Less than <
greater than >
less than or equal <= 
greater or equal >=
not equal !==
not similar !===

Special Mathematical Operator 

Modulus   c = a % b => a divided by b and the quatient is c

20 % 3

Prime numbers 2,3,5,7,11,13,17

Conditional Statements: if else condition 

Syntax:  
if ( LogicalCodition ) {
  //When True
} else {
  // When false 
}

if ( condition 1 ) {
  //True for condition 1
} else if (condition 2 ) {
  //true for condition 2
}else if (....){
  //when true
} else {

}


example 
  var age =  40;

  if (age > 20 ) {
    console.log('You are not a teenager');
  } else {
    console.log('You are a teenager');
  }

  var m = 3;

  if (m == 1) {
    console.log( 'It  is January' );
  } else if ( m ==2 ) {
     console.log( 'It  is February' );
  } else if ( m == 3 ) {
     console.log( 'It  is March' );
  } else {
     console.log( 'It  is not defined' );
  }

  To Read: Read about switch ... case  --- another way of conditional statement 

  Looping: For loop / for each 
  syntax: 
  for (intilization; condition; action) {
    // execute this block as long as condition is true 
  }

  example print even numbers between 100 and 200 inclusive 
  Hint a number n is even when n % 2 === 0
 for( var n = 100; n <= 200; n = n + 1){
   if( n % 2 == 0 ){
     console.log(n);
   }   
 }

 TO Read: while loop, do ... while loop 

 Function: block of code 

 Syntax: 

Dedifining a function: 
 function funcName (param1, param2, ... ) {
   ....... code block 
   return value1
 }

 Invoking or calling a function: 
 funcName( p1, p2,. ...);
Example convert degree F to degree c
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}

var calculateAge = function( dob){
  return 21;
}

HTML Manipulation 

HTML page can be accessed through an object called document 
the dot (.) operator lists all the properties of the ducument 

Example to get an html element with id of 'student' from an html page 

document.getElementById('student') returns an element with id of student 








