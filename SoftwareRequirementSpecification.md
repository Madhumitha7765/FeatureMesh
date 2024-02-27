# Feature: Authentication
  Description of the feature

## Scenario: User logs in with valid credentials
  Description of the scenario

  Given the user is on the login page
  When they enter valid username and password
  Then they should be redirected to the dashboard

## Scenario: User logs in with invalid credentials
  Description of the scenario

  Given the user is on the login page
  When they enter invalid username and password
  Then they should see an error message

# Feature: Shopping Cart
  Description of the feature

## Scenario: User adds items to the cart
  Description of the scenario

  Given the user is logged in
  And they are on the product page
  When they click on "Add to Cart" button
  Then the item should be added to the cart

## Scenario: User removes items from the cart
  Description of the scenario

  Given the user has items in their cart
  When they click on "Remove" button next to an item
  Then the item should be removed from the cart

# Feature: Search Functionality
  Description of the feature

## Scenario Outline: User searches for a product
  Description of the scenario outline

  Given the user is on the search page
  When they search for "<search_term>"
  Then they should see relevant results

  Examples:
    | search_term |
    | iPhone      |
    | Laptop      |

# Tags
@smoke @regression
Feature: Tagging example
  Description of the feature with tags

@critical
Scenario: Tagging a scenario
  Description of the scenario with tag

# Comments
# This is a comment
# You can use comments to provide additional information or context
