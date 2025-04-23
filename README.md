 How to Replace Files and Import the Database

- **Step 1: Delete the Old Project Folder**
  - Go to your XAMPP folder.
  - Open the `htdocs` folder.
  - Find the `itproject` folder and delete it.

- **Step 2: Add the New Files**
  - After deleting the old folder, copy the new `itproject` folder.
  - Paste the new folder into the `htdocs` folder.

- **Step 3: Create the Database**
  - Start XAMPP and turn on Apache and MySQL.
  - Open **phpMyAdmin** by going to [http://localhost/phpmyadmin](http://localhost/phpmyadmin) in your web browser.
  - In phpMyAdmin, click the **Databases** tab.
  - Create a new database named `overalldb` (make sure it’s in **lowercase**).
  - Once the database is created, click on it to open it.

- **Step 4: Import the Database**
  - In the `overalldb` database, click the **Import** tab.
  - Click the **Choose File** button and find the database file:
    `xampp > htdocs > itproject > database`.
  - Select the `overalldb.sql` file and click **Open**.
  - Then click **Go** to import the database.

- **Step 5: Check Everything**
  - After the import is done, make sure all the tables and data are loaded correctly.
  - Now you can use the project and interact with the database.

