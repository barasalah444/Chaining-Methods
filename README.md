# Chaining-Methods

# Chaining Methods - Python

This is a simple Python project to practice **Method Chaining** in OOP.

## What I did
- Updated the `User` class methods (`make_deposit`, `make_withdrawal`, `display_user_balance`).
- Added `return self` to each method so they can be chained together in a single line.

## Example
```python
guido.make_deposit(100).make_deposit(200).make_withdrawal(50).display_user_balance()
