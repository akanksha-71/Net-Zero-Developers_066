
* Objective: To ensure the Swag Labs e-commerce website functions correctly, with a focus on:

  Product listing and sorting
  
  Cart operations (add, remove, calculate)
  
  Checkout functionality
  
  Social media integration


* Tools Used:
  Manual Testing
  Browser Developer Tools

* Scope of Testing

  Functional Testing: Verify core e-commerce functionalities.
  
  UI/UX Testing: Ensure the website is user-friendly and responsive.
  
  Cross-Browser Testing: Ensure compatibility with multiple browsers (e.g., Chrome, Firefox, Safari).
  
  Cart and Checkout: Validate that users can easily add/remove items and complete the purchase process.
  
  Social Media Links: Test the functionality of external links.


* Key Functional Test Cases

  TC01: Verify Default Product Listing

    Objective: Ensure products are listed in alphabetical order by default.
    
    Steps: Navigate to the product catalog and verify the default sorting.
    
    Expected Result: Products listed from "Sauce Labs Backpack" to "Test.allTheThings() T-Shirt (Red)."

  TC02: Add Multiple Items to Cart
  
    Objective: Ensure users can add multiple items to the cart.
    
    Steps: Add several products and check if the cart updates correctly.
    
    Expected Result: Cart icon shows correct number of items and accurate total price.

UI/UX Test Case

  TC06: Verify Social Media Links
    
    Objective: Ensure that external social media links open correctly.
    
    Steps: Scroll to the footer, click on each social media link (Twitter, Facebook, LinkedIn).
    
    Expected Result: Each link should open in a new tab, leading to the respective social media page.
    
Cart and Checkout Functionality

  TC07: Checkout Process
    
    Objective: Test the entire checkout process from cart to confirmation.
    
    
    Steps: Add items, proceed to checkout, fill in billing/shipping info, and complete the purchase.
    
    Expected Result: Order is processed, and a confirmation message is displayed.


* Tools & Technology Used

  Manual Testing:
  
  Test steps and verification through browser interface
  
  Documenting results in test management tools (e.g., TestRail, Excel)
  
  Environment - Platform: Web Browser: Chrome 117.0 
  
  URL: https://www.saucedemo.com
  
  Miro Mind map tool

* Challenges & Mitigations

  Challenge: Maintaining consistent browser compatibility.
  
  Mitigation: Used cross-browser testing tools (e.g., Sauce Labs).
  
  Challenge: Variability in loading times and UI elements.
  
  Mitigation: Incorporated explicit waits.
  
  Challenge: Responsive design issues.
  
  Mitigation: Tested with multiple screen resolutions.






