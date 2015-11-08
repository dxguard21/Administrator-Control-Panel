README Document.

How to implement:

1.	Copy and paste whole .ZIP file into your public_html directory in your webserver.

2.	Open settings.php in edit mode and set each feild as you wish. Then save it. Do not navigate to the panel via a web browser until this document is filled out.

3.	Navigate to {your website hostname}/admin/mysql.php - It will run and create the datatables

4.	Then open {your website hostname}/admin/ and fix any errors. If there are none you can go and delete the MySQL.php file.

5.  Now log into the dashboard. The username is Administrator and the default password is Banana.

6.  You will need to now go and change the passcode which can be done under the user tab on your dashboard.

7.	Done. Enjoy your now fully working administration control panel.

Your panel can be accessed like this: http://{your host name}/admin/

NOTE: I am continually changing things on this repo. When I feel a release is in order I will release a new version in the releases. Otherwise the master branch is always changing and if you download it as a .zip file I do not garentee it to work as intended. So do so at your own risk.   

Version: 2.4.5
If there are any issues please email me: me@laughingquoll.net

Changelog:
2.4.5:
Updated defunk MySQL codes. Now running MySQLi
2.4.4
Added a unified settings file. Cleaned up code.
Also fixed a issue where login page would allow any password.	
