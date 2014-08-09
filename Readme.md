# Credit card validation

### The problem

Our shopping website has customers abandoning their purchase in the order form.  
Our research shows that they drop out because they make typos in their credit 
card numbers.

### Your mission

Implement validation for the credit card number to catch our users mistakes, and 
provide them helpful feedback!

 * It should tell me the credit card type (Mastercard / Visa / American Express) 
  as soon as it knows it.
 * It should show a green check mark as soon as the valid.
 * If the card type isn't known, show a question mark.

![screenshot](validation.gif)

### How?

 - Visa cards start with 4.
 - Visa cards are valid if they have 13 to 16 digits.
 - Mastercard cards start with 5.
 - Mastercard cards are valid if it has 16 digits.
 - American Express cards start with 34 or 37.
 - American Express cards are valid if it has 15 digits.
