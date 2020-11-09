# ValidCardChecker
This Program is for Checking that credit card is valid or not.

There is three function in this program -
1. validateCred() => checks a card is valid or not.
2. findInvalidCards() => checks which number is Invalid and return a array of Invalid numbers.
3. idInvalidCardCompanies() => this function does two things (1) Gives a list of Companies with Invalid Cards (2) If a company not get Identified then prints "Comapny not found!"
 
 
                            ------------------working of Functions--------------------
1 - ValidateCred () - 
    This works on the basis of Luhn's Algorithm[https://en.wikipedia.org/wiki/Luhn_algorithm#Description]


2 - findInvalidCards() -
    It checks through the nested array for every cards that is valid or not using ValidateCred function
    
3 - idInvalidCardCompanies() - 
    First Digit 	 Company
    3	        Amex (American Express)
    4	        Visa
    5	        Mastercard
    6	        Discover
    function check every first number of the card using the above table and put it in the array if it doesn't lie in the range the it simply prints "Company Not Found"    
