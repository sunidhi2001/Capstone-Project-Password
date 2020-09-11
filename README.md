# Capstone-Project-Password
Password Project Details
## THE CHALLENGE 

You need to create a program that will store the user ID and passwords for the users of a system. It should display the following menu: 
1. Create a new User ID
2. Change a Password
3. Display all user IDs
4. Quit

Enter Selection :
 
If the user selects 1, it should ask them to enter a user ID. It should check if the user ID is already in the list. If it is, the program should display a suitable message and ask them to select another user ID. Once a suitable user ID has been entered it should ask for a password. Passwords should be scored with 1 point for each of the following:  

 it should have at least 8 characters; 
 it should include uppercase letters; 
 it should include lower case letters; 
 it should include numbers; and 
 it should include at least one special character such as !, £, $, %, &, <, * or @. 

If the password scores only 1 or 2 it should be rejected with a message saying it is a weak password; if it scores 3 or 4 tell them that “This password could be improved.”
Ask them if they want to try again. If it scores 5 tell them they have selected a strong password. Only acceptable user IDs and passwords should be added to the end of the .csv file. 

If they select 2 from the menu they will need to enter a user ID, check to see if the user ID exists in the list, and if it does, allow the user to change the password and save the changes to the .csv file. Make sure the program only alters the existing password and does not create a new record.  

If the user selects 3 from the menu, display all the user IDs but not the passwords. 

If the user selects 4 from the menu it should stop the program. 
