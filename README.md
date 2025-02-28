# Simplehands-on-dynamoDB

Amazon DynamoDB is a fully managed NoSQL database service that provides fast and scalable performance. 
In this project, we created a DynamoDB table, added items, and queried data using the AWS Management Console.

Step 1: Log in to AWS Console
Go to AWS Management Console and Search for DynamoDB in the AWS services search bar.
Click on DynamoDB to open the service.

Step 2: Create a DynamoDB Table
In the DynamoDB Dashboard, click on "Create Table".
![create table](https://github.com/user-attachments/assets/3f7d3214-5e6d-4376-bbac-b3dcf577c727)
Enter a Table Name (e.g., customer_id).
Set the Primary Key (Partition Key) as:
Name: UserID
Data Type: String
![table details](https://github.com/user-attachments/assets/6727a41d-e7d2-4e54-9b0b-8403e10bbcb9)
(Optional) If needed, add a Sort Key (e.g., UserEmail, String).
Keep the Default settings (for billing and capacity mode).
Click "Create Table" and wait for the table to be created.
![table 1 created](https://github.com/user-attachments/assets/e1da6998-ac67-4007-b997-7b8282ebb978)

Step 3: Add Items to the Table
After the table is created, go to the "Tables" section.
Click on your table name (e.g., customer_id).
Navigate to the "Items" tab.
Click on "Create Item" and Enter data for the item.
Click "Save" to insert the item.

![explore table item](https://github.com/user-attachments/assets/f6dd1901-53e4-4aba-a923-1773b0d04ede)


Step 4: Verify the Data
In the Items tab, check if the item appears in the table.
Click on an item to view its details.
![items created](https://github.com/user-attachments/assets/be76dfd8-5ed1-44c4-b88c-ba4da5bd0611)

Step 5: Query the Table (Optional)
![explore table item](https://github.com/user-attachments/assets/f6dd1901-53e4-4aba-a923-1773b0d04ede)
