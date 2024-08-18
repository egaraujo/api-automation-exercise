# API Automation with Postman
This is a test suite in Postman, for API Automation Exercise

## Run tests
1. Clone the repo
2. Install newman: ```npm install -g newman```
3. Run tests from command line: ```newman run AutomationExercise.postman_collection.json```   

## Test cases
![screenshot](https://github.com/egaraujo/api-automation-exercise/blob/main/screenshot.jpg)
• GET productsList: status  
• GET productsList: body   
• POST productsList not supported method: status    
• POST productsList not supported method: body    
• GET brandsList: status    
• GET brandsList: body    
• PUT brandsList not supported method: status  
• PUT brandsList not supported method: body  
• POST searchProduct tshirt: status  
• POST searchProduct tshirt: body    
• POST searchProduct without search_product parameter: status  
• POST searchProduct without search_product parameter: body  
• POST createAccount: status  
• POST createAccount: body  
• POST verifyLogin with valid details: status  
• POST verifyLogin with valid details: body  
• POST verifyLogin with invalid details: status  
• POST verifyLogin with invalid details: body  
• POST verifyLogin without email parameter: status  
• POST verifyLogin without email parameter: body  
• DELETE verifyLogin not supported method: status  
• DELETE verifyLogin not supported method: body  
• GET getUserDetailByEmail: status  
• GET getUserDetailByEmail: body  
• PUT updateAccount change addresses: status  
• PUT updateAccount change addresses: body  
• GET getUserDetailByEmail check updated addresses: status  
• GET getUserDetailByEmail check updated addresses: body  
• DELETE deleteAccount: status  
• DELETE deleteAccount: body  

## Links
Automation Exercise API: https://www.automationexercise.com/api_list  
