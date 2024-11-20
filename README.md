Intro to Javascript:-

-Javascript is a High programming language for bulding web application in a efficient way.
-Javascript works on both client side redering as well as server side rendering.
-Node JS is the runtime environment of Javascript.
-Javascript is comes from echma script so we see the latest version of javascript in the form of echma 
script.
- Now we used the javascript version 6 i.e Echmascript 6(ES6).
-In another way we called ES6 as the Vanilla Javascript.
- Javascript is mainly used for building logics or functuionality of a web page.  



Variable:-
- Variable is container to store some data.
- There are 3 types of variable are there in Javascript.
1. Let:-

- Let is type of variable which is used for changing the variable name latter.
- Now these days, most of the developers used let for changing variable value.
-Let is a block scope so we have been using let for most of thr case.
-

2. Var:-

- Var is a type of variable which is also used for changing the variable in later
stage.
- var is used in oldest browser so now a days we are don't use  var most of the 
cases.
- var is function or outside scope.

3. Const:-
-const is a type of variable where we can't change our data.
-const means constant to store some data like number, integer etc..

  Rules for creating Variable Name:-

- Variable names are case sensitive i.e "a" & "A" is different.
-Only letter ,digit, Underscore & special character is allowed.(white space is not allowed).
-only letter ,digit, Underscore & special character should be list 1st character only.
-reserved words cannot be a variable names

ex:-
let a=23
let A=23
Data types in JS:-
- Datatypes is an attributes associated with a piece of data that tells a computer system how to interpret its value.
- In data types we used "type of" operator to know that what type of data it is.
-mainly in java script their are 2types of data types.
 1. Primitive:-

-In javascript there are 7 types of primitive data types are present.
    a. Number:- Number are the types of data types those it contain some numerical values.
     b.Boollean:-In Boolean data types  we get Boolean value like & false.
    c. Undefiened:-In Undefiened data types the data is not define so that
    it will show     undefined.
    d. Null:- In this data types we get null for the value means nothing.
    e.Bigint:-	In bigint we will get big integer value
    f.string:-String is a type of data type that can hold some character like names or words.
    g. Symbol :-In symbol we will get whole symbol as well as the values we
    get for the data  type.


   2. Reference or non primitive:-

    Datatypes are the type of data type that can hold multiple item in a single time.
    * Non primitive datatype are object,array,function.
    * Object is a non primitive data type which can hold multiple of item in one single entity.
    * Mainly objects are working on (key:value) pair.
    * The left hand side is our keys and right hand side are the value of the key.
     ex:-

       person = {
        "name" : "man heart",
         "age" : 20,
        "business" : "software",
        "carrier" : "good",
       }

       ex of array:-
        

        let arr = {1,2,3,9,4}
        note- array indexing start from "0".

        ex of function:-

        function great(){
          console.log("hello Lucky")
        }
        great()


Operator in Javascript:-

* Operator is a the key feature to do some task or operate some task.
* ex:- A+B
* In the given example A & B are the operands, "+" sign is our operator.
* There are 5 types of operator are their in Javascript.

1. Arithmatic Operators:- (+,-,*,/%(module),  **{Exponents}   )
2. Unary Operators :-  ++( increment) , --(Decrement)
3. Assignment Operators:- (=, +=, -=, *=,/=, %=, **=)
4. Logical Operators:- (Logical and operator -&&), ( Logical or operator||)
5. Comparison Operators:- (++, !=, !==, ===)

Conditional Statement in Javascript:-

* Conditional Statement are used to implement some condition in code.
* There are 3 types of conditional statement are their in Javascript.

1. if condition:-

-- if condition is true then statement is execute.
-- syntax:-
if(condition) {
  statement
}

2. if-else condition:-
* if condition is true then if block is executed otherwise to else condition.
--syntax:-
if(condition){
  statement
} else{
  statement
}

3. else-if condition:-

 * its check the condition multiple times where the condition is true.
--syntax:-
if(condition){
  statement
} else if (condition){
  statement
} else{
  statement
}
