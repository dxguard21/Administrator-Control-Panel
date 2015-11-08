<h1>Administrator Control Panel </h1> <b>(Or simply put it Admin Dashboard) </b>
<p>This is a project I created to give every developer a dashboard to use for their clients. <p>

<b>Key Features: </b>

1. Edit pages of your website.

2. Messaging system. 

3. Upload files to a specific directory. - In the works.

4. Change password.

5. Create to-do lists with progress bars. - In the works.

6. Plus more on the way.

How to implement:

1.	Copy and paste whole .ZIP file into your public_html directory in your webserver.

2.	Open settings.php in edit mode and set each feild as you wish. Then save it. Do not navigate to the panel via a web browser until this document is filled out. 
Information regarding the salt feild: 
<b>Make sure you change this. However after you create the databables be sure not to change it or your passwords will no longer be recognised and you will need to reinstal the whole system.<b>

3.	Navigate to {your website hostname}/admin/mysql.php - It will run and create the datatables

4.	Then open {your website hostname}/admin/ and fix any errors. If there are none you can go and delete the MySQL.php file.

5.  Now log into the dashboard. The username is Administrator and the default password is Banana.

6.  You will need to now go and change the passcode which can be done under the user tab on your dashboard.

7.	Done. Enjoy your now fully working administration control panel.

Your panel can be accessed like this: http://{your host name}/admin/

<b>Implimentation on your website</b>
<p>This tutorial gives instructions on how to add the neccary code to allow things such as messages and page editing to work.<p>

NOTE: I am continually changing things on this repo. When I feel a release is in order I will release a new version in the releases. Otherwise the master branch is always changing and if you download it as a .zip file I do not garentee it to work as intended. So do so at your own risk.   

Version: 2.4.5
If there are any issues please email me: me@laughingquoll.net

Changelog:
2.4.5:
Updated defunk MySQL codes. Now running MySQLi
2.4.4
Added a unified settings file. Cleaned up code.
Also fixed a issue where login page would allow any password.	
