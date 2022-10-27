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
![image](https://user-images.githubusercontent.com/46093495/198238674-04f12641-2551-4b2d-91ea-415b13bc78ae.png)
![image](https://user-images.githubusercontent.com/46093495/198238721-cd6b163c-cf48-4950-b4c2-6211284baa30.png)
![image](https://user-images.githubusercontent.com/46093495/198238759-348849f1-1dfc-4e6c-9afe-934d5a979aca.png)

### Documenting results 
For each operation the bot documents whether the current task was completed successfully or not by indicating in the **Test Results** sheet the results for each operation. 
![image](https://user-images.githubusercontent.com/46093495/198239258-c7968e4c-0f1a-4620-89e1-2044b4ffce78.png)

Thus the user can view the results of the test by simply looking at the **Test Results** sheet. 




