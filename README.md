# Test-Cases v1
*These are Test Cases made by me in the Manual and Automation Software Testing course.*

ID: LT1

## Title: 
Test login with correct credential

## Description: 
Check if the login works when a person uses a correct user & password.

## Steps to reproduce: 
1. Go to www.website.com/login
2. Add a correct user & password
3. Press login button

## Expected Result: 
User should be able to login and is taken to his profile page.

## Test data: 
User: Stefan & Password: 12345678

## Status: New, In Progress, Passed or Faild

--------

ID: LT2
## Title:
Test login with incorrect credential
     
## Description: 
Check if the login works when a person uses a correct user & incorrect password.
     
## Steps to reproduce: 
1. Go to www.website.com/login
2. Add a correct user & incorrect password
3. Press login button
     
## Expected Result: 
User shouldn’t be able to login and get an error message.
     
## Test data: 
User: Stefan & Password: 1111111
     
## Status: New, In Progress, Passed or Faild
-----------

ID: SF1

## Title:
Test search functionality
     
## Description: 
Check if the search working correctly.
     
## Steps to reproduce: 
1. Go to www.amazon.md
2. Add a 5 different keywords in the search bar
3. Click to search button
      
## Expected Result: 
The results must be displayed only with the keyword entered in the search.

## Test data: 
Keywords: bulb, doorbell, ball, rj-45, glasses
    
## Status: New, In Progress, Passed or Faild

ID: RN1

## Title:
User can register to web site with true data
     
## Description: 
User create a new account, using real data (correct format email). 
     
## Steps to reproduce: 
1. Go to www.website.com/register
2. Add a correct data - e-mail/username/password/confirm password
3. Click to Register button

## Expected Result: 
User can register on www.website.com with a true data.

## Test data: 
e-mail: true@mail.com  
username: Gheorghe
password: 1234567890
confirm password: 1234567890
    
## Status: New, In Progress, Passed or Faild


ID: RN2

## Title:
The user cannot register with a fake email
     
## Description: 
The user cannot register with an e-mail does not match the email address format.
     
## Steps to reproduce: 
1. Go to www.website.com/register
2. Add the data in the required fields: e-mail/username/password/confirm password
3. Click to Register button

## Expected Result: 
The user receives a message that it is not possible to register with this e-mail format.

## Test data: 
e-mail: qwe asd zxc
username: Gheorghe
password: 1234567890
confirm password: 1234567890
    
## Status: New, In Progress, Passed or Faild
