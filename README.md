
##In Progress...

All validation need "Validate" class for activate validation lib.

- emailOrUser for validate fields where we expect an user or an email.
- email: for validate fields where we expect an email.
- common-text: for validate fields where we expect text without special characters or numbers.
- number-text: for validate fields where we expect text without special characters but with numbers.
- empty: for validate fields where we expect no empty value
- integer-number: for validate fields where we expect only numbers without decimals
- decimal-number: for validate fields where we expect only numbers with decimals (sperated with dot)
- Doble Check Password: masterPass slavePass.


HOW TO USE
We need link the lib in our HTML document.
Then, we can put in all the fields where we need to validate the necessary classes. 
All the fields have to be contained in a form.
Finally, in our code, we invoke the generalValidation () function, which receives as parameters the form to be validated, and the function to execute if all the fields are correct.
