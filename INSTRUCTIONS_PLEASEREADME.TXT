========================================
FLOW OF THE PROGRAM TO SUCCESSFULLY WORK
========================================

1. Make sure your Laptop/PC have Java Netbeans IDE installed. If not, Install it first. [I'll provide the Java Netbeans IDE in this setup folder and located at bin folder] -- [jdk-8u111-nb-8_2-windows-x64.exe] -- [double click the file then it will automatically go into installing process]

2. Make sure your Laptop/PC have jdk/jre any version of java is installed. If not, Install it first. [I'll provide the jdk11 (java development kit version 11) in this setup folder and located at bin folder] -- [jdk-11.0.21_windows-x64_bin.exe] -- [double click the file then it will automatically go into installing process]

3. Make sure your Laptop/PC have xampp IDE installed. If not, Install it first. [I'll provide the xampp IDE in this setup folder and located at bin folder] -- [xampp-windows-x64-8.2.4-0-VS16-installer.exe] -- [double click the file then it will automatically go into installing process]

4. Open the Intalled xampp IDE then Click the Start button for Apache and MySQL module/service then click the Admin button beside/under the line of MySQL and it will show you the phpMyAdmin dashboard in your chrome.

5. In your chrome which is the phpMyAdmin dashboard is showing, just click the phpMyAdmin icon, located at the right-upper portion of the screen, After -- click New --> then under the Database name, type: inventorymanagementdb --> then click Create.

6. Under the Database created -- click once the inventorymanagementdb --> after, locate the Import menu inside the database created --> under File to import: click Choose File and locate the .sql file and it is located in this setup folder and open the bin folder and you can see the inventorymanagementdb.sql --> click this file to be imported --> and once it is imported the database [already in phpMyAdmin] --> scroll down to very end, then click the Import button --> And it is DONE!!!

7. Click refresh or click the phpMyAdmin icon to refresh, and you can already use the Application. or run/double click the Goodwell_Ink_Inventory_Management_System.exe -- file and you are already free to used the Application. Enjoy!!!

8. Just make sure to connect your xampp IDE to connect it in the server localhost database first, everytime you use the Application and if you are Done using with in the day, just make sure also to stop the xampp connection to server localhost database.

9. Enjoy using the System!!!!!!!

========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "GoodwellInventoryManagementSystem.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.


======================================================
CREATE BY: RUMIL CHRISTIAN T. SELOVERES
	   BACHELOR OF SCIENCE IN COMPUTER ENGINEERING
======================================================