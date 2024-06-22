# Contract
So the project is to have a Contract that explains and illustrates the functionality of three statements that is require, assert, and revert .
So In this we have our contract as MyContract which is having a public variable “value” which  will be used to check the functionality of these three statements.
For this firstly we have setValue function having “_value” as its one parameter and it is having the require statement , which is checking the condition that is if “_value” (value given by user ) is greater than zero. If this turns out to be true than it will set the value accordingly otherwise it will display “value must be greater than 0” message.
Next we have testAssert function which is having a assert statement checking condition if value is greater then equal to zero then it will add “1” to the value.
Next we have resetValue function for checking the functionality of revert statement . This function is checking if the value is already equal to zero than revert statement will work and will revert a message as “ value is already 0” and if value is not zero then this function will reset the value to zero.
