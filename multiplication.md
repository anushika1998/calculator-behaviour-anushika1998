# Multiplication

## Scenario: Multiply two numbers

- Given : The calculator is properly working.
- When : The user enters _operand '*' operand_ and presses the '=' button.
- Then : The result of multiplication of the two numbers is displayed.

## Scenario: Operator instead of the second Operand
  
- Given : The calculator is properly working.
- When : The user enters _operand '*' operator_ and presses the '=' button.
- Then : The result would be replacement of the existing operator.

**Example:**  When we input 56 * / _then press_ '='.
result: 56 / and still wait for input of new operand.
