# Project Summary :
It is an project where we have automated Different scenarios using Selenium and TestNG. We have followed the Page Object Model (POM) for designing and developing the project.
## Technology used:
- Language: Java
- Build System: Gradle
- Automation tool and framework: Selenium and TestNG
- Data manipulation: Simple JSON and CSV Parser
## Project Flow:
- Check if admin can login and see user data list
- Register new users
- Login by latest user
- Create daily expenditure
- See profile data
## How to run this project
- Clone the project
- Open the project from IntellIJ; File>Open>Select and expand folder>Open as project
- Hit this command: `gradle clean test -PsuiteName="regressionSuite.xml"` to run the regression suite or `gradle clean test -PsuiteName="smokeSuite.xml"` to run the smoke suite.
- Generate Allure report:

- ``` allure generate allure-results --clean -output ``` 
-   ``` allure serve allure-results ```

## Peoject Description -

1. Visit the website https://dailyfinance.roadtocareer.net/
2. Register User implementing different Scenarios
3. Log in as admin (pass admin credentials from the terminal) and check if the last registered user is displayed on the admin dashboard. 
4. Log in with the last registered user and update their profile image.
5. Add a cost/expenditure from a CSV file. Create a CSV file with 5 rows, This test will loop 5 times, as there are 5 data sets in the CSV.
6. Print the total cost and assert it against your expected total sum of the amounts.
7. Search for an item by name from the list and assert that the total cost matches the item's price.
8. Create Regression Suite and Smoke Suite, ANd run them individually.

## Output -
### Smoke Suite :
   ![image](https://github.com/user-attachments/assets/aaf94f53-9ab5-478d-9955-f45074e47f94)
   ![image](https://github.com/user-attachments/assets/3b653c79-2728-41b8-b94b-49fab66e3177)


 ### Regression Suite :
   ![image](https://github.com/user-attachments/assets/484d1787-8931-41cb-9185-361d964a0afb)
   ![image](https://github.com/user-attachments/assets/0cc03e69-7faf-4443-b89e-01d7a0875248)


### Output Video Link :
[Click Here To see the output video of the Automation Script ](https://drive.google.com/file/d/1xesSLvLT_5Tq_V3M8YBLm_GGHAMxOVBx/view?usp=sharing)
    
