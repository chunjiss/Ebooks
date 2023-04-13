##ABOUT SOURCE CODE
###Programming language: C# NetFramework.
###Database management system: SQL Server.
###Using MVC model.
###Interacting with the database using Entity Framework.
###User interface utilizing Bootstrap.

##THE FUNCTIONS
###1. Administration functions: basic statistics view, add, delete, edit, and view details of objects such as books, genres, publishers, authors, and images.
###2. Role-based authorization for user accounts.
###3. Login and registration functions. Google account login integration (you need to update the ClientId and ClientSecret correctly for it to work).
###4. Integrated email sending for registration and order completion (configure email sending in the web.config file).
###5. Homepage displaying the latest books, most viewed books, and books by different genres.
###6. Detail view page displaying buttons for purchasing books. If a book has already been purchased, these buttons will be replaced with a "View Book" button.
###7. Purchased books page storing books that have been purchased.
###8. Shopping cart page storing information about books that have been added or removed from the cart.
###9. PDFjs integrated book viewing feature, allowing for viewing of books in PDF format.
###10. Pagination feature implemented (using AJAX), with AJAX-based removal of products from the shopping cart.

##INSTALLATION INSTRUCTIONS
###Create and configure Web.config: Based on the Web.config.example file, create a new file named Web.config. The content in Web.config should be similar to Web.config.example. After completing this step, you will need to configure the necessary information in the Web.config file.
###Step 1: Configure SQL Server connection strings.
####Create a database in SQL Server.
####Fill in the correct information for your SQL Server.
![image](https://user-images.githubusercontent.com/80302795/231717051-6701204e-05fb-47b8-8969-42225d57d9b6.png)
###Step 2: Configure Google login.
![image](https://user-images.githubusercontent.com/80302795/231717266-f56bf3e6-7499-4d9d-9cf3-939019eab2fb.png)
###Step 3: Configure email sending using SMTP.
![image](https://user-images.githubusercontent.com/80302795/231717435-c28baa08-bf0c-4778-8427-386280f7547c.png)
####To run the setup function, execute the source code and access the following URL:
http[s]://hostname:[port]/Install/Index
####For example: https://localhost:8888/Install/Index.
####This process will initialize the tables and load basic data into the SQL Server. Once this step is completed, you can start using the existing features.
