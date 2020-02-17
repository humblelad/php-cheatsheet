# PHP Cheatsheet
## Simple php cheatsheet for quick reference and fast learning and guidance.

### Hello world ! in PHP

```
<?php
//simple comment
echo "Hello World !";
?> 
```
### Variables
  
 ```
 <?php
 $first_name= "Rose"; //variables start with dollar sign.
 $sec_name= 01;       //numbers don't need quotes unlike the case of strings
 ?>
 ```
 ### Mathematical Operators
 
```
+ //addition
- //subtraction
* //multiplication
/ //division
% //modulus
** exponent
 ```
 
 ### Comparison Operators
 ```
 ==     //equal to 
 !=     //not equal to
 <>     //not equal to
 !==    // not identical
 >      // greater than
 <      // less than
 >=     // greater than or equal to 
 <=     // less than or equal to 
 ```
  ### Assignment Operators
 ```
 =   //basic assignment 
 +=     //addition
 -=     //subtraction
 *=    //multiplication
 /=      //division
 %=      //modulus
 
 ```
  ### Increment Operators
 ```
 ++$variable     //pre increment
 --$variable     //pre decrement
 $variable++     //post increment
 $variable--    // post decrement
 
 ```
  ### Logical Operators
 ```
 and    //true if both are true 
 or    //true if only one is true
 Xor   //true if either are true but not both are true
 &&   //true if both are true
 ||   //true if one is true
 !    // true if it is not true
 ```
  ### IF statement
 ```
<?php
if (cond) {
//run this
}
```
*Example*
```
if(2>1){
echo "let me run please! ";
}
?>
 ```
 ### If else statement
 ```
<?php
if (condition) {
// do something 
}
elseif (condition) {
// do something 
} 
else {
// do something
} ?>
```
*Example:*
```
<?php
if ($variable > 100) {
echo "Your variable is greater than 100";
} 
elseif ($variable == 150) {
Echo "Your variable is 150!";
} 
else {
"Your number is less than 100";
}
?>
```
### Arrays
```
<?php
// Numeric Array
$my_array = array("titanic", "shine", "royalcarribian", "oasesoftheseas");
echo $my_var[0]; // echoes out titanic 
?>

<?php
// Associative Arrays
$ages = array("titanic"=>"39", "rose"=>"18", "flower"=>"29");
echo $ages["titanic"]; // echoes out 39 
?>

```
 ### for loop
 ```
 <?php
for ($count = 1; $count < 10; $count++){
echo $count;
}
?>
```
 ### while loop
 ```
<?php
$count = 0;
while ($count < 10) {
echo $count;
$count++;
}
?>
```
 ### Random Numbers
 ```
<?php
echo rand(1,50); // creates random number between 1 and 50
?>
```
 ### Functions
 ```
<?php
function names($names) {
echo "Hello, my name is " . $names;
}
namer("Jack"); // calls the function
?>
```
 ### Include Function
 ```
<?php
Include('titanic.php');
?>
```
 ### Require once function
 ```
<?php
require_once('jackrose.php');
?>
```
### Strings
```
<?php
$variable = "Unfulfilled love story";
str_replace("Unfulfilled", "Complete", $variable); // replace Unfulfilled with Complete
echo strtoupper($variable); // Capitalize all letters
echo ucwords($variable); // Capitalize first letter of all words
echo strtolower($variable); // Lowercase all letters
echo lcfirst($variable); // Lowercase only first word
?>
```
**Feel free to create a pull request and include more php cheatsheets**


 
 



