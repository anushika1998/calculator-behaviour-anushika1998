# Addition

## Scenario: Addition of two numbers
  
- Given : The calculator is properly working.
- When : The user enters _operand '+' operand_ and presses the '=' button.
- Then : The result is the sum of the two numbers.

## Scenario: Operator instead of the second Operand
  
- Given : The calculator is properly working.
- When : The user enters _operand '+' operator_ and presses the '=' button.
- Then : The result would be replacement of the existing operator.

**Example:**  When we input 56 + / _then press_ '='.
Result: 56 / and still wait for input of new operand.
