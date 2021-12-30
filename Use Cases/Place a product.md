# _Place a Product_

  This use case allows a registered user to place his own product or service.

### Bacis Flow:

  Step 1. The use case start when a user indicates he wants to place his product being displayed. 
  
  Step 2. The user clicks "Post an Ad" button.
  
  Step 3. In order to publish information the system requests user's phone number verification. (First time only)
  
  Step 4. The user enters his phone number.
  
  Step 5. The system checks the phone number is valid and doesn't duplicate any existing user's phone number.
  
  Step 6. The system sends SMS with digital verification code to provided phone number.
  
  Step 7. The user enter the code.
  
  Step 8. The system introduces the rules of posting to the user.
  
  Step 9. The user accepts the rules by clicking corresponding button.
  
  Step 10. The system requests to select a category of the product from given options. Shows up 'Category', highlighted as a first step for out of 4 (1. Category  2. Compose  3. preview  4. Publish) in GUI.
    
   * Category 
      * Subcategory 
      * Subcategory
      * Subcategory 
      * ... 
   * Category 
      * Subcategory 
      * Subcategory
      * Subcategory
      *  ...
   * Category 
      * Subcategory
      * Subcategory
      * Subcategory
      * ...
  
  Missing step users actions
  
  Step 11. The system requests to fill the fields specifying the item. 2nd step (compose) out of 4 shows up in GUI.
  
  Step 12. The user fills the empty feilds.
  
  Step 13. The system checks filled data is matching the requirments of categories and subcategories.

  Step 14. The system displays 3rd step out of 4 as a perview of product to be posted.  
  
  Step 15. The user clicks the post button.
  
  Step 16. The system displays 4th step (publish) showing a message thet the item will be review by a moderator.
  
  Step 17. The system sends confirmation email to the user about the product has been placed.
