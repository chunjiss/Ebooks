# I. ABOUT SOURCE CODE
<p>Programming language: C# NetFramework.</p>
<p>Database management system: SQL Server.</p>
<p>Using MVC model.</p>
<p>Interacting with the database using Entity Framework.</p>
<p>User interface utilizing Bootstrap.</p>

# II. THE FUNCTIONS
<p>1. Administration functions: basic statistics view, add, delete, edit, and view details of objects such as books, genres, publishers, authors, and images.</p>
<p>2. Role-based authorization for user accounts.</p>
<p>3. Login and registration functions. Google account login integration (you need to update the ClientId and ClientSecret correctly for it to work).</p>
<p>4. Integrated email sending for registration and order completion (configure email sending in the web.config file).</p>
<p>5. Homepage displaying the latest books, most viewed books, and books by different genres.</p>
<p>6. Detail view page displaying buttons for purchasing books. If a book has already been purchased, these buttons will be replaced with a "View Book" button.</p>
<p>7. Purchased books page storing books that have been purchased.</p>
<p>8. Shopping cart page storing information about books that have been added or removed from the cart.</p>
<p>9. PDFjs integrated book viewing feature, allowing for viewing of books in PDF format.</p>
<p>10. Pagination feature implemented (using AJAX), with AJAX-based removal of products from the shopping cart.</p>

# III. INSTALLATION INSTRUCTIONS
## 3.1. Create and configure Web.config: 
<p>Based on the Web.config.example file, create a new file named Web.config. The content in Web.config should be similar to Web.config.example. After completing this step, you will need to configure the necessary information in the Web.config file.</p>
<p>Step 1: Configure SQL Server connection strings.</p>
<p>Create a database in SQL Server.</p>
<p>Fill in the correct information for your SQL Server.</p>
<img src="https://user-images.githubusercontent.com/80302795/231725847-dd84b9f6-7b12-416e-a796-0992d2a32f1b.png"/> 
<p>Step 2: Configure Google login.</p>
<img src="https://user-images.githubusercontent.com/80302795/231717266-f56bf3e6-7499-4d9d-9cf3-939019eab2fb.png"/>
<p>Step 3: Configure email sending using SMTP.</p>
<img src="https://user-images.githubusercontent.com/80302795/231717266-f56bf3e6-7499-4d9d-9cf3-939019eab2fb.png"/>

## 3.2. Run the setup function.
<p>To run the setup function, execute the source code and access the following URL:</p>
http[s]://hostname:[port]/Install/Index
<p>For example: https://localhost:8888/Install/Index.</p>
<p>This process will initialize the tables and load basic data into the SQL Server. Once this step is completed, you can start using the existing features.</p>
