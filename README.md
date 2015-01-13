Sanitation Review - Android Application
======================================


Members
----------

* Vishnu G T

* Aditya A Prasad

* Abhishek Kaushik - Mentor


Overview
--------

This is an Android application which is going to be used for reviewing government facilities.
It will be used by volunteers to visit government facilities such as toilets & latrines ... 
and gather data that will be send to the government server for review.
This will be used to make sure the money being dispersed for these facilities are being used
for the correct purpose.
The fluid UI for the application is available [here][1].


Features
--------

we hope to implement the following features :

* The app will have a login facility for the volunteers, the user name and the hash of the entered password will be send to the server for authentication. This will take place asynchronously so that the user experience won't be affected.
In the server side after the hash corresponding to the user name is fetched from the database, it is compared with hash key which was sent and the result of the comparison is conveyed to the client (mobile app) which is used to take the 
user to the next activity.

* We also will have a 'stay logged in' option in the login activity letting the volunteer bypass this whole login process
after the first time. We can do this by storing the username and password hash in the app cache using shared preferences
and using them without user interference. This way if the password was changed the app will ask the user to login again.

* In the second activity we will use the GPS in the mobile to use the user's location to find the nearby locations 
and display it in a list. The user can choose from the locations in the list and answer some standard questions.
This will ensure that the volunteer was physically present at the location when he reviews the utility.

* Then in the final activity the user can choose existing pictures from the gallery or take them on the fly and send
a maximum of 4 images to the server.


[1]: https://www.fluidui.com/editor/live/preview/p_y4JUtRyz6cc2o762Q3HdPZVve4l7Sizi.1420968044593

===Revised Plan===

Toilet Finder
-----------------
1st User

Step 1
Add a toilet
1st step
Toilet Address
Address

Step 2
Exists or Not (Flag or iButton)
Red means - This toilet does not exist
Green means - This toilet exists.

Step 3
Rate & Review
Rate Toilet - Stars for (Afordability or Free )
Accessibility  - Stars for (Afordability or Free )
Hygene - Stars for (Afordability or Free )
Safety - Stars for (Afordability or Free )

Add Comments

Submit
----------
2nd User
Locate a Toilet in Map
Add Photo
Inside & Outside
Mark Gender - Male, Female or Both

All Other Features of 1st User

Toilet added by this user will be reviewed before publishing 
——————
3rd User

Admin Review Panel
Add/Edit/Delete Toilets
Add researchers and other 

-----------------
4th User (General Public)

User Login

Auto location finder
Auto show all toilets around
Guide user to selected toilet
Click to see rating and address
List view of detail

Five minutes after entering into a fixed radius of (50-100 mtrs)
Notification to ask
Used or Not Used
If Used
Rate and Review

Share in social sites (FB, Twitter)



