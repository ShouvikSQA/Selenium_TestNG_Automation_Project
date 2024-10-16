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
   ![image](https://github.com/user-attachments/assets/56eab2c2-1280-470d-86a1-74a62f32565f)

  ![image](https://github.com/user-attachments/assets/22f31be6-245a-40ce-880b-e8e70530bd52)



 ### Regression Suite Report :
   ![image](https://github.com/user-attachments/assets/97915069-8989-4da5-8e8b-03c360762ce0)

   
   ![image](https://github.com/user-attachments/assets/4a91a66b-b5c3-47a6-8c92-d04d6948b601)

  


### Output Video Link :
[Click Here To see the output video of the Automation Script ](https://drive.google.com/file/d/1xesSLvLT_5Tq_V3M8YBLm_GGHAMxOVBx/view?usp=sharing)
    
