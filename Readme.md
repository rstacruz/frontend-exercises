![screenshot](validation.gif)

**[Download template ▸](https://raw.githubusercontent.com/rstacruz/frontend-exercises/master/index.html)**

----

# Credit card validation

## The problem

Our shopping website has customers abandoning their purchase in the order form. 
Our research shows that they drop out because they make typos in their credit 
card numbers. We can do something about this!

## Solution

Implement validation for the credit card number to catch our users mistakes, and 
provide them helpful feedback!

 * It should tell me the credit card type (Mastercard / Visa / American Express) 
  as soon as it knows it.
 * It should show a green check mark as soon as the valid.
 * If the card type isn't known, show a question mark.

## Your mission

 * Get [index.html](index.html) and work on it in your machine.
 * Use whatever tool or library you want. (jQuery, Angular, Backbone, etc)
 * Keep the code clean and reviewable.
 * When you're done, upload it somewhere where it can be viewable by the world.
 * Have fun!

## How?

 - Visa cards start with 4.
 - Visa cards are valid if they have 13 to 16 digits.
 - Mastercard cards start with 5.
 - Mastercard cards are valid if it has 16 digits.
 - American Express cards start with 34 or 37.
 - American Express cards are valid if it has 15 digits.
