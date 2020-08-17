# Addition

## Scenario: Addition of two numbers
  
- Given : It is a properly working calculator.
- When : _oprand '+' operand_ is entered and '=' button is pressed.
- Then : The resuld ie. sum of the two numbers is displayed. 


## Scenario: Operator instead of the second Operand
  
- Given : It is a properly working calculator.
- When : _oprand '+' operator_ is entered and '=' button is pressed.
- Then : The result would be replacement of the existing operator.

**Example:**  input: 56 + / _then_ '=' is pressed.
result: 56 / and still wait for input of new operand 
