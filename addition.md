# Addition

## Scenario: Addition of two numbers
  
- Given : The calculator is properly working.
- When : After entering _operand '+' operand_ the '=' button is pressed.
- Then : The result is the sum of the two numbers.

## Scenario: Operator instead of the second Operand
  
- Given : It is a properly working calculator.
- When : _operand '+' operator_ is entered and '=' button is pressed.
- Then : The result would be replacement of the existing operator.

**Example:**  Input: 56 + / _then_ '=' is pressed.
Result: 56 / and still wait for input of new operand.
