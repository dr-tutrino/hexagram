Add Creative README

Welcome to version 1.1 of the Add Creative Macro.

Edits: 
The software uses ODS file formats instead of CSV, the delimiters have been reduced to just using ">>". 
There's now functionality for selecting the PG-13 checkbox. 

If you've already read the PAST readme, just download OpenOffice and check the new example sheet for a quick review of changes. 



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~GETTING STARTED~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

For this software work on any computer there are three things you need to do: 

1) Download the most up to date Java Runtime Environment. Most computers have a version of this, you can check your version by doing: 

->click start menu
->all programs
->click Java
->click about Java

Then you'll get a popup saying something like Version x update y. 

If you've got a version older than 8 go to:

->http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html

Then download the version suitable for your OS. The install manager can uninstall older versions of your JRE so you don't waste memory. 

2) Download Apache OpenOffice from: https://www.openoffice.org/

3) Copy the chromedriver.exe file over that's included in the zip. 

You're now ready to start the program! 



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~USER INPUT GUIDE~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Before you start using this software, have a look at how the example.ods is formatted, you want to copy this format for your ods sheets.
The software skips the first line (which has URL, Title, Categories, Photos), and uses '>>' to seperate titles, categories and photos. 
It will also upload every unique title/photo combination, which is why multiple titles and photos are in a single cell for a single url. 
For the PG-13 check box, put a 'Y' in the last column if you want it to get ticked when adding creatives. 

You need to use openoffice for this version.

Then, make sure the images you're going to be using are in the directory that opens when you manually click "change image" for creatives.
You can either change this directory by manually uploading 1 image from the folder that holds all your images, or you can dump all those
images into the folder your browser holds. 


The software will ask you for a few pieces of information:

1) Path to ODS file

- this is the path location of where you copied the example.ods file over to. 

E.g.

C:\Users\User\Desktop\example.ods


2) Path to chromedriver - this is the path location of where you copied the chromedriver.exe file over to. 

E.g.

C:\Users\User\Desktop\chromedriver.exe


You can check the path location of the file by doing: 

->right click chromedriver.exe
->click properties

There, it should highlight the path location. Don't forget to add "chromedriver.exe" or to the input! 

2) Username and Password. You should know this. Tut tut. 

3) Campaign ID - the campaign ID is normally a 4 digit number that is unique to the campaign you're looking for.

Now it'll run happily through your creatives. 


WARNING: DO NOT USE YOUR PC WHILST IT IS DOING THIS. 
This macro sends key presses directly from your operating system, if you try to click away it will STOP THE PROGRAM. 
Typically each unique creative takes 15 seconds to unpload. A pop up window will display if it succesfully did everything. 


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~DEBUGGING~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Hopefully you won't need to. But if anything is going wrong, try running the file from command. To do this:

->click start menu
->search "cmd"
->change directory to that which the file is in, you can do this by typing cd [your directory], E.g. cd Desktop
->run the file using this command: java -jar AddCreative_v1.1.jar

It still won't work but it will at least say why. Message me the error logs so i can try and get a fix. 
	
This is all for windows operating systems. For mac users I suggest the following:

->switch off your mac
->purchase a windows machine 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~END~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~