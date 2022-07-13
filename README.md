# Credit
Credit is a program that is created for CS50 Problem Set 1. The program is used to check the types of credit cards and it is created by using C. The users will be prompted to enter a credit card number in integers. After that, the program will be classified whether the credit card number is AMEX (American Express), MASTERCARD, VISA, or INVALID. The validity of the Visa card is checked by using Luhn's Algorithm. 

# Information about Credit Cards
A credit (or debit) card, of course, is a plastic card with which you can pay for goods and services. Printed on that card is a number that’s also stored in a database somewhere, so that when your card is used to buy something, the creditor knows whom to bill. There are a lot of people with credit cards in this world, so those numbers are pretty long: American Express uses 15-digit numbers, MasterCard uses 16-digit numbers, and Visa uses 13- and 16-digit numbers. And those are decimal numbers (0 through 9), not binary, which means, for instance, that American Express could print as many as 10^15 = 1,000,000,000,000,000 unique cards! (That’s, um, a quadrillion.)

Actually, that’s a bit of an exaggeration, because credit card numbers actually have some structure to them. All American Express numbers start with 34 or 37; most MasterCard numbers start with 51, 52, 53, 54, or 55 (they also have some other potential starting numbers which we won’t concern ourselves with for this problem); and all Visa numbers start with 4. But credit card numbers also have a “checksum” built into them, a mathematical relationship between at least one number and others. That checksum enables computers (or humans who like math) to detect typos (e.g., transpositions), if not fraudulent numbers, without having to query a database, which can be slow. Of course, a dishonest mathematician could certainly craft a fake number that nonetheless respects the mathematical constraint, so a database lookup is still necessary for more rigorous checks.

# How to Run the Project
1) Download all the files.
2) Open the "credit.c" file and run the project.

# Some Screenshots from the Program 
![cs50 pset 1 ss1](https://user-images.githubusercontent.com/95561298/178524440-8af3579e-5b1d-4d44-a48a-7468b3a8eb79.png)

# Reference 
https://cs50.harvard.edu/x/2022/psets/1/credit/
