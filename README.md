Music sharing site made in django.

List of Feature:

1. Home page: Describes website and link to login page
2. Register User: Sign up for new user account
3. Login User: Sign in with existing user account
4. Dashboard: It has 4 different types of albums

   1.) Private / Uniquely yours albums [including private & public both]  
   2.) Received Albums
  - Albums which are shared by another users to you only will fall into this category
   3.) Friends Albums
  - It contains Public Albums of users whom you follow
   4.) Browse All
  - It contains all the public albums of all available users on the site 


   Create new Albums and uploads song 
       View/Edit/Delete own albums 
       View albums shared by other users 
       View Friends' albums 
       View public albums of all users 
       Share/Unshare own albums 
       Search any albums with album title, artist, genre 
   Search with specific album category 
  
  
listen/search all songs with their album names

Follow/Unfollow Users

View my profile and analytics :- It is named as [user's] activity on my profile page.
It shows the classification of your albums into 4 diff category and number of songs available in album.

Edit my profile

View profile of my followers

Forgot password with registered email with your account

Users feedback through email

Custom error handler pages inside templates folder [it will be available to use when release mode is on]

Logout


How to run ?

1.) Go to Music_Sharing_Site2 folder
2.) Create new virtual env by running 'python -m venv env' or use existing venv inside project. [virtual env is recommended]
3.) Open terminal there and run 'pip install -r Music_Sharing_Site2/requirements.txt' . It will install all the required packages.
4.) apply migrations and finally python manage.py runserver
