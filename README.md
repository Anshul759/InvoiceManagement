# InvoiceManagement
AI-Enabled Fintech B2B Invoice Management App

# Project Description
Below are the major aspects of the application that are developed. 
1) Data Loading in DB:
• A dataset was parsed,processed, and loaded in the database schemas. 
2) UI Representation of the data:
• A responsive Ul that displays the invoice data loaded from the database. 
• The UI supports searching and pagination 
• The UI supports editing of some editable fields, adding a new row to the grid, deleting rows from the grid and advance search. 
3) Al Support in the application:
• Suports predicting the payment date for one or more invoice(s).

# Technologies Used
• HTML/CSS
• JavaScript
• ReactJS
• Java Servlets
• MySQL
• MaterialUI
• Python
• Machine Learning

# Description Images of the Project

• Landing Page 
  • It is how the Web UI looks when we first load our website.
  
  ![Landing Page](https://user-images.githubusercontent.com/76433107/170858723-6e51190a-7ecb-4988-8887-f5fdc9d75532.png)

• Add Modal 
  • It is how the Web UI looks when we click on Add button on landing page. We can add the details of the new invoices and add it to the database.
  • It is active when no records are selected,else is disabled.

![Add Modal](https://user-images.githubusercontent.com/76433107/170858748-2c5f5794-0f18-4a9b-b49a-346d057d122d.png)

• Edit Modal 
  • It is how the Web UI looks when we click on Edit button on landing page. 
  • It is active only when single record is selected,else is disabled.
  • We can edit the editable fields of the selected invoice and save changes to the database.

![Edit Modal](https://user-images.githubusercontent.com/76433107/170858756-f8408117-6b42-4f08-8d04-34830424af99.png)

• Delete Page
  • It is how the Web UI looks when we click on Delete button on landing page. 
  • It is active only when more than one record(s) is(are) selected for delete,else is disabled.  

![Delete Modal](https://user-images.githubusercontent.com/76433107/170858759-af944229-4294-4273-bd90-4471e13df3c1.png)

• Search Field
  • It is used to perform dynamic search in customer Id field

• Advance Search
  • It is how the Web UI looks when we click on Advance Search button on landing page.
  • The user can perform advance search on the basis of following fields
      • Customer Id
      • Invoice Id
      • Document Id
      • Business year
  • User can perform the advance search operation using combination of any of the fields

![Advance Search](https://user-images.githubusercontent.com/76433107/170858770-c6fb2097-d198-49d4-8839-4c8a6cab7734.png)

• Analytics View
  • It is how the Web UI looks when we click on Analytics View button on landing page.
  • The user can provide constraints for the following fields
      • Clear date
      • Baseline Create date
      • Due date
      • Invoice currency
   ![Analytics View](https://user-images.githubusercontent.com/76433107/170858777-4905a14d-3d0c-4562-9810-3d18653ef8bb.png)


  • The image provided in the charts.png is how the graphs looks by providing constraints in the advance field form.
    ![Charts](https://user-images.githubusercontent.com/76433107/170858782-6f7298ab-c62f-4770-95af-6dff851d7561.png)

• Predict Button
  • It is used to predict the expected payment date of the selected invoices.
  • It is active only when more than one record(s) is(are) selected ,else is disabled.
  • It makes use of the machine learning model trained for prediction ,then updates the value in the database. 
  
