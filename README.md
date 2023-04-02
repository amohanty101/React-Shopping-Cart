## Module 19 - MIT Shopping Cart Excercise

In the shopping cart exercise, we need to refactor the program to add another feature to the  application whoch is resetting the stock. 
 To accomplish this, you’ll need to make a call to a Strapi API and get a fresh list of available products.

# Here’s how the reset stock feature works:

There’s an input field on the page that contains the URL to the Strapi back end
When a user clicks the “ReStock Products” button, a call is made to the Strapi back end specified in the input field
The result of this call is an updated list of products
The  task is to implement the restock feature. You should add your code to the “cart.jsx” file. More specifically, you need to implement the “restockProducts” function on line number 169 of the file. 

Download these files (Links to an external site.) to get started.

Hints:

Make use of the “doFetch” function to make a call to the API
Make use of “setItems” to update the existing items