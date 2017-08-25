<!—  ex)
### Feature: Shopping Cart
-  As a Shopper
-  I want to put items in my shopping cart
  Because I want to manage items before I check out

### Scenario: User adds item to cart
-  Given I'm a logged-in User
-  When I go to the Item page
-  And I click "Add item to cart"
-  Then the quantity of items in my cart should go up
-  And my subtotal should increment
-  And the warehouse inventory should decrement
—>


### Feature: (Title)
- Describe a feature
-

### Scenario: (Given, When, Then)
- a user scenario 
- 
