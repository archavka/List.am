# _Register User_.

In order to get personalized or restricted information, place orders or do other specialized actions a new user must register a username(email) and password.



## Basic Flow:

Step 1. The use case start when a user indicates that he wants to register.

Step 2. The system requests an email and password.

Step 3. The system requests to enter verification number.

Step 4. The system requests to agree to the Posting Rules and List.am Terms of Service. (defect found: there is no document with terms and rules to agree with)

Step 5. The user enters an email and password.

Step 6. The user enters the verification number.

Step 7. The system checks that the email does not duplicate any existing registered email.

Step 8. The system checks that the verification number is correct.

Step 9. The system requests user's email address confirmation by sending instructions to users email address. "Check your email" button appears on the screen.

Step 10. User clicks the "Check your email" button.

Step 11. The system redirects the user's to his personal email account to follow the instructions thet were send to his email address.

Step 12. The user activates account by following that instructions.

Step 13. The system starts a login session and displays a welcome message.
  
   ### Alternative Flows:
    
   * Step 7: If the username duplicates an existing username the system displays a message and the use case goes back to step 2.
   * Step 8: If the user does not enter a required field, a message is displayed and the use case repeats from step 5.


### Postconditions:	

  The user can now obtain data and perform functions according to his registered access level.



___


# _Login User_.

In order to get personalized or restricted information, place orders or do other specialized actions a user must login so that that the system can determine his access level.


### Basic Flow:

Step 1. The use case starts when a user indicates that he wants to login.

Step 2. The system requests the email and password.

Step 3. The user enters his email and password.

Step 4. The system verifies the email and password against all registered users.

Step 5. The system starts a login session and displays a welcome message.


### Alternative Flow:

* Step 4: if username is invalid, the use case goes back to step 2.

* Step 4: if the password is invalid the system requests that the user re-enter the password. When the user enters another password the use case continues with step 4 using the original email and new password.


### Preconditions:
The user is registered.

### Postconditions:
The user can now obtain data and perform functions according to his registered access level.

### Business Rules:	

  Some data and functions are restricted to certain types of users or users with a particular access level.
