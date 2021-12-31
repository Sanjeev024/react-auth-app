# react-auth-app
react app having two screens 
1.Login/Register-: It is a login screen with following options:
i. Username & Password fields. Username must have a valid email id.
ii. Login Button for user to login
iii. Forgot Password hyperlink through which the user can reset his
password. Once the user clicks the button, then he/she will be redirected
to the next screen i.e User Profile.
2. User Profile: If the successfully authenticated, user profile will be
display with following information of the user (provided as input in the previous
step):
i. User profile image
ii. User name
iii. User email
iv. The app will be sending the user location to Firebase after every 5
seconds. Log the locations in the firebase so we can see the location
history. If the user moves away from this screen then stop logging the
location.


# Setting up the App
Run command to install React project for building React App using create-react-app.

npx create-react-app react-auth-app

Go the app directory with change directory command.
cd react-auth-app

