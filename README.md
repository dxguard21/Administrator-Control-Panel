<h1>Administrator Control Panel </h1> <b>(Or simply put it Admin Dashboard) </b>
<p>This is a project I created to give every developer a dashboard to use for their clients. <p>

<b>Key Features: </b>

1. Edit pages of your website.

2. Messaging system. 

3. Upload files to a specific directory. - In the works.

4. Change password.

5. Create to-do lists with progress bars. - In the works.

6. Plus more on the way.

<b>How to implement:</b>

1.	Copy and paste whole .ZIP file into your public_html directory in your webserver.

2.	Open settings.php in edit mode and set each field as you wish. Then save it. Do not navigate to the panel via a web browser until this document is filled out. 
Information regarding the salt field: 
Make sure you change this. However after you create the datatables be sure not to change it or your passwords will no longer be recognized and you will need to reinstall the whole system.

3.	Navigate to {your website hostname}/admin/mysql.php - It will run and create the datatables

4.	Then open {your website hostname}/admin/ and fix any errors. If there are none you can go and delete the MySQL.php file.

5.  Now log into the dashboard. The username is Administrator and the default password is Banana.

6.  You will need to now go and change the passcode which can be done under the user tab on your dashboard.

7.	Done. Enjoy your now fully working administration control panel.

Your panel can be accessed like this: http://{your host name}/admin/

<b>Implementation on your website</b>
<p>This tutorial gives instructions on how to add the necessary code to allow things such as messages and page editing to work.<p>

<i>To get messages to function:</i>

You will need to copy and paste some extra code. They are in the untilities folder.

Firstly create a three template page in you website directoy under a messages directory with the file names index.php, reply.php, send.php. 

Then copy and paste the corresponding part into the body section of your each page.

Then go through the send.php section and modify the message as per your wishes.

<i>To get page editing to work:</i>
Copy and paste section one of the editing part in the code.php file to the top of the page you wish the edits to show.
Then copy and paste section two to where you want the text to be displayed.

NOTE: Seeing I cannot see your page structures and which pages you have if you want to change fields or add more pages to edit there are a few steps to take. This is what to do:

1. Copy and paste the home folder in the edits folder. Change it to the page name. Them open the new folder and open index.php find and replace every word that has homepage to the name of your new page. Then change the title from Edit Home Page to Edit {Your Page Name} Page.
2. Then open the index.php file in the edit folder.
2. 
COMMING SOON!

NOTE: I am continually changing things on this repo. When I feel a release is in order I will release a new version in the releases. Otherwise the master branch is always changing and if you download it as a .zip file I do not guarantee it to work as intended. So do so at your own risk.   

Version: 2.4.5
If there are any issues please email me: me@laughingquoll.net

Changelog:
2.4.5:
Updated defunkt MySQL codes. Now running MySQLi
2.4.4
Added a unified settings file. Cleaned up code.
Also fixed an issue where login page would allow any password.	
