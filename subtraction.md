# Subtraction

## Scenario: Subtraction of two numbers

- Given : It is a properly working calculator.
- When : _operand '-' operand_ is entered and '=' button is pressed.
- Then : The result is the subtraction of the two numbers.

## Scenario: Operator instead of the second Operand
  
- Given : It is a properly working calculator.
- When : _operand '-' operator_ is entered and '=' button is pressed.
- Then : The result would be replacement of the existing operator.

**Example:**  input: 56 - / _then_ '=' is pressed.
result: 56 / and still wait for input of new operand.
