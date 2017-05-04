UTM EDITOR README

Welcome to version 1.0 of the UTM editor.


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~GETTING STARTED~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

For this software work on any computer there are two things you need to do: 

1) Download the most up to date Java Runtime Environment. Most computers have a version of this, you can check your version by doing: 

->click start menu
->all programs
->click Java
->click about Java

Then you'll get a popup saying something like Version x update y. 

If you've got a version older than 8 go to:

->http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html

Then download the version suitable for your OS. The install manager can uninstall older versions of your JRE so you don't waste memory. 

2) Copy the chromedriver.exe file over that's included in the zip. 

3) You're ready to start the program! 



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~USER INPUT GUIDE~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The software will ask you for a few pieces of information:

1) Path to chromedriver - this is the path location of where you copied the chromedriver.exe file over to. 

E.g.

C:\Users\User\Desktop\chromedriver.exe


You can check the path location of the file by doing: 

->right click chromedriver.exe
->click properties

There, it should highlight the path location. Don't forget to add "chromedriver.exe" to the input! 

2) Username and Password. You should know this. Tut tut. 

3) Campaign ID and Items per page - the campaign ID is normally a 4 digit number that is unique to the campaign you're looking for.

4) UTM, First Page, First Creative, Last Page, Last Creative. This is the last bit of input required.

	i)  The UTM is the new one you want to use, starting from a question mark. E.g. ?utm_medium=CPC
	This will be appended to URLS without a UTM, or replace old UTMs.
	
	ii) The First Page you want to start editing from, this can be any page.
	
	iii) The first creative on the first page you want to start editing from. 
	NOTE: from every page thereafter, it'll start from the first creative of that page.
	
	iV) The last page to want to edit to. 
	
	v) The last creative on that last page to edit to. 


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~DEBUGGING~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Hopefully you won't need to. But if anything is going wrong, try running the file from command. To do this:

->click start menu
->search "cmd"
->change directory to that which the file is in, you can do this by typing cd [your directory], E.g. cd Desktop
->run the file using this command: java -jar UTMeditor.jar

It still won't work but it will at least say why. Message me the error logs so i can try and get a fix. 
	
This is all for windows operating systems. For mac users I suggest the following:

->switch off your mac
->purchase a windows machine 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~END~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~