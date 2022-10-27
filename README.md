# Project 4 - UI Automation and testing 

The goal of this project was to create an automatic process to test the Web API developed in the previous projects. This was done by utilizing the UI automation functionality UI Path provides to test a variety of use cases and edge cases.

The following operations was automated by this bot : 

### Website login 
The bot automatically logs in to the Website with credentials that is stored securely in Ui Path Orchestrator
![image](https://user-images.githubusercontent.com/46093495/198237633-325e2984-eb36-4eeb-b00d-790a4d66beb3.png)

### Gathering test data
Once logged in the bot gathers data toe be tested from a specified excel file. 
![image](https://user-images.githubusercontent.com/46093495/198237963-8dd92d28-1735-4e8d-b203-0b53b602567c.png)

### Using the dataset to test CRUD operations
The bot then loops through each record in the excel file and test all CRUD operations on the website one by one.
