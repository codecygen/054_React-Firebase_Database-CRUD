1) Console Commands:
- npm create-react-app .
- npm i firebase

2) Create Firebase Database
- Add project (Enter project name)
- Click on settings icon, then "Project settings"
- Scroll down and click on "</>" button. It will open a section says "Register app"
- Give a name and click on "Register app" button. (Here if you want, you can also set up a Firebase Hosting for the app)
- Once the app gets registered, 

3) Firebase Configuration File
- "firebase-config.js" under "src" folder.
- Copy the function "firebaseConfig" in "Settings" section of Firebase and paste into "firebase-config.js".
- Create environmental variables ".env" file and put sensitive data inside it.

4) Create "Firestore Database"
- Click on "Firestore Database", then click on "Create Database" button.
- Select "Start in production mode" then click on "Next" button.
- Create a database with collections and data.