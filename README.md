Instructions for Replacing Files and Importing the Database
Delete the Existing Project Folder:

Go to your XAMPP directory.

Navigate to htdocs → itproject.

Delete the existing itproject folder to remove the old files.

Replace with New Files:

After deleting the old folder, copy the new version of the itproject folder.

Paste it into the htdocs directory of your XAMPP installation.

Create the Database:

Open your XAMPP control panel and start both Apache and MySQL services.

Open phpMyAdmin by navigating to http://localhost/phpmyadmin in your browser.

In the phpMyAdmin interface, click on the Databases tab.

Create a new database named overalldb (make sure the name is in lowercase).

Once the database is created, click on it to open the database management view.

Import the Database:

While inside the overalldb database, click the Import tab.

Click the Choose File button and navigate to: xampp > htdocs > itproject > database.

Select the database file named overalldb.sql (or any other relevant file) and click Open.

After selecting the file, click Go to begin the import process.

Check the Setup:

After the import is complete, make sure all tables and data are correctly loaded into the overalldb database.

You should now be able to access your project and interact with the database through your XAMPP environment.

