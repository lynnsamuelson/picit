#picit

Group project to create a Pinterest clone

##Requirements:

Node.js https://nodejs.org/en/
Installation of http-server via npm install -g http-server
A Github account
Your own fork of this repo
A local clone of your fork of this repo
Register your fork as a developer application: https://github.com/settings/developers
An account on Firebase: https://www.firebase.com/
New empty Firebase app
In your Firebase app's login and auth page, enable Github authentication
Copy the GitHub Client ID & GitHub Client Secret from your fork's developer application page into your Firebase app's Github authentication fields
Post Cloning Your Fork Locally:

Modify app/controllers/auth-control.js, replacing the Firebase URL with your own Firebase app's URL
Inside the lib directory:
Run npm install
Run bower install
Inside the main repo directory:
Run http-server
Make note of the port number returned after running http-server
Navigate to http://localhost:[your-port-number]
Usage:

Home screen shows a list of all Pics not flagged private posted by all users.

New Pic button in menu allows adding of a personal Pic, all fields required. Link field is for pasting in the URL of an image.

Clicking Add Pic will prompt for a new board, or enable you to add the Pic to an existing board of yours.

Picit button on other Pics allow for adding of other users' Pics to your own boards.
