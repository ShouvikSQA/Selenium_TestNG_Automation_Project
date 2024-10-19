# Project Summary :
It is an project where we have automated Different scenarios using Selenium and TestNG. We have followed the Page Object Model (POM) for designing and developing the project.
## Technology used:
- Language: Java
- Build System: Gradle
- Automation tool and framework: Selenium and TestNG
- Data manipulation: Simple JSON and CSV Parser

## Peoject Description -

1. Visit the website https://dailyfinance.roadtocareer.net/
2. Register User implementing different Scenarios
3. Log in as admin (pass admin credentials from the terminal) and check if the last registered user is displayed on the admin dashboard. 
4. Log in with the last registered user and update their profile image.
5. Add a cost/expenditure from a CSV file. Create a CSV file with 5 rows, This test will loop 5 times, as there are 5 data sets in the CSV.
6. Print the total cost and assert it against your expected total sum of the amounts.
7. Search for an item by name from the list and assert that the total cost matches the item's price.
8. Create Regression Suite and Smoke Suite, ANd run them individually.

## How to run this project
- Clone the project
- Open the project from IntellIJ; File>Open>Select and expand folder>Open as project
- Hit this command: `gradle clean test -PsuiteName="regressionSuite.xml"` to run the regression suite or `gradle clean test -PsuiteName="smokeSuite.xml"` to run the smoke suite.
## Generate Allure report:

- ``` allure generate allure-results --clean -output ``` 
-   ``` allure serve allure-results ```



## Output -
### Smoke Suite Report :
![image](https://github.com/user-attachments/assets/67ebba38-6bd5-480d-984a-0e0de190941c)



  ![image](https://github.com/user-attachments/assets/f2e7b39a-092e-4e83-a560-8089cd6cc404)




 ### Regression Suite Report :
   ![image](https://github.com/user-attachments/assets/459094b2-3b2a-4a5c-847c-0c5e0d3c16b3)



   
   ![image](https://github.com/user-attachments/assets/8b805ffc-4562-486d-8bc8-bfc26db3d284)


  


### Output Video Link :
-  [Click Here To see the output video of Smoke Suite Automation Script ](https://drive.google.com/file/d/1UOgzquutpV7HKzWAnYEGZd0_SrC2XCcn/view?usp=sharing)
- [Click Here To see the output video of Regression Suite Automation Script ](https://drive.google.com/file/d/1Wb2csy888SR6k4PsrnF4nQPT-6FwISeX/view?usp=sharing)
    
