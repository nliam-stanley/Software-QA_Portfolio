# SauceDemo Test Cases

| TC ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|------|---------------|------------|-----------------|---------------|--------|
| TC001 | Login with valid credentials | Enter valid username and password, click Login | User logs in successfully | As expected | Pass |
| TC002 | Login with invalid password | Enter valid username and wrong password | Error message displayed | As expected | Pass |
| TC003 | Login with empty username | Leave username blank and click Login | Validation message displayed | As expected | Pass |
| TC004 | Login with empty password | Leave password blank and click Login | Validation message displayed | As expected | Pass |
| TC005 | Login with both fields empty | Click Login without entering credentials | Validation message displayed | As expected | Pass |
| TC006 | Logout | Click menu and select Logout | User is logged out | As expected | Pass |
| TC007 | Add product to cart | Click "Add to Cart" on a product | Product added to cart | As expected | Pass |
| TC008 | Remove product from cart | Click "Remove" on a product | Product removed from cart | As expected | Pass |
| TC009 | View shopping cart | Click cart icon | Cart page opens | As expected | Pass |
| TC010 | Checkout with valid information | Enter first name, last name and ZIP code | Checkout continues successfully | As expected | Pass |
| TC011 | Checkout with empty fields | Leave checkout fields blank | Validation message displayed | As expected | Pass |
| TC012 | Complete purchase | Finish checkout process | Order confirmation displayed | As expected | Pass |
| TC013 | Sort products by Name (A-Z) | Select A-Z sorting | Products sorted alphabetically | As expected | Pass |
| TC014 | Sort products by Price (Low to High) | Select price sorting | Products sorted correctly | As expected | Pass |
| TC015 | Open product details | Click a product name | Product details page opens | As expected | Pass |
