 # README

 > **NAME**

How do I Connect Database with PHPMYADMIN?

 > **DESCRIPTION**
This will help you to start to conect database with PHPMYADMIN. It is guide for you to connect your databases from your personal computer.
[Reference](https://www.inmotionhosting.com/support/website/connect-database-remotely-mysql-workbench/)


  > **VISUAL**

![DATABASE](http://webvaultwiki.com.au/GetFile.aspx?File=/images/screenshots/mysql/phpmyadmin01.png)
![PHP](http://webvaultwiki.com.au/GetFile.aspx?File=/images/screenshots/mysql/phpmyadmin02.png)
  > ***Installation**

{
	Step 1 -	Download phpMyAdmin 5.1.1
	Choose the latest PHPMYADMIN and select to download.
}

{

    	Step 2 - installing
	Once you downloaded MyPHPADMIN you can install it onto your computer
}

{

    	Step 3 - Setup my PHPMYADMIN
	Browse to your phpMyAdmin URL using your Internet Web Browser, and login using your root or dba user login as shown.
    
}
{

    	Step 4 - Steps to connect to your database remotely
	- Open PHPMYADMIN
	- From the main menu choose Databases
	- In the create database field type in a name for your database. Leave the collation drop down box if you wish to use the default MySQL schema collation. Click Create.
	-Your database will now be visible on the right hand side under the list of available databases. To setup a new user login to access this database, click on Users in the main menu. Choose the Add User option under the list of available server users.

	- In the section titledLogin Information - type in a username, localhost and a password in the fields as shown. Optionally you can press the Generate button to create a random password for you.
	- The section that relates to the users GLOBAL privileges are privileges you want to assign to this user which apply to ALL databases on the server. It is recommended that you do NOT assign these permissions unless you know exactly what you are doing. It is far more secure to assign seperate user logins to each piece of software or website that will require access to only a particular database. Therefore leave this section BLANK, and then click the Add User button.
	- After the user is created, you can see it listed on the Users page. Click Edit Privileges to assign access to a specific database.
                  - Once again leave the Global Privileges section BLANK. Scroll down to the section titled Database-Specific Privileges. Choose the database you want the user to be able to access from the list, and click GO.
                  - Assign the permissions as shown to provide the user with access to the given database. The following permissions are recommended for compatibility with most modern web-based software applications
                      Select, Insert, Update, Delete, Create, Alter, Index, Drop, Create Temporary Tables, Lock Tables.
                      ![DATABASE](http://webvaultwiki.com.au/GetFile.aspx?File=/images/screenshots/mysql/phpmyadmin10.png)
                  - Click GO after selecting the relevant privileges.( http://webvaultwiki.com.au/GetFile.aspx?File=/images/screenshots/mysql/phpmyadmin12.png)
                  -  If you click on the users Edit Privileges option now, you will see that new privileges for the specific database are now listed as belonging to the user.
                  - Click the Logout option in the top left corner, and test your new user login with phpMyAdmin.
                  - Test your new user login by using it to login to phpMyAdmin.
                      NOTE: phpMyAdmin must be configured in the default cookie authentication mode to be able to login to MySQL server with any username.
                      ![DATABASE](http://webvaultwiki.com.au/GetFile.aspx?File=/images/screenshots/mysql/phpmyadmin15.png)
                      ![DATABASE](http://webvaultwiki.com.au/GetFile.aspx?File=/images/screenshots/mysql/phpmyadmin15.png)
                  - If you can only your new database in the list of schema's on the left then your new database and username is most likely ready for use.
                 

}
> **AUTHOR**

Author Name: Jester Ken Nale


