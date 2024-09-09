# FireBase_Form


This project is a simple web-based form integrated with Firebase Realtime Database. Users can input their personal details like ID, name, and age, and perform operations such as inserting, updating, removing, and fetching data from the database using Firebase.

Features :

Insert Data: Add new user information (ID, name, age) to the Firebase Realtime Database.
Update Data: Modify the existing data using the user ID as a reference.
Remove Data: Delete data based on the user ID.
Find Data: Search for and display user details (name, age) by entering their ID.
           Prerequisites
           
Before using this project, ensure you have the following:

Firebase Account: A Firebase project configured with the Realtime Database.
Firebase Web SDK: Ensure the Firebase SDK is included in the project (already done in the HTML file).


Go to the Firebase Console.
Create a new Firebase project.
Add a Web app to your project.

Start the Project:

Open index.html in your browser to interact with the form.

Usage
Insert Data :
          Enter the ID, Name, and Age in the respective fields.
          Click the "INSERT" button to add the data to the Firebase Realtime Database.
          
Find Data by ID :
          Enter the ID in the "Find by ID" section.
          Click the "FIND" button to fetch and display the name and age of the user.
          
Update Data :
          Enter the ID of the user you wish to update.
          Enter the new name and age.
          Click the "UPDATE" button to save the changes.
          
Remove Data :
          Enter the ID of the user you want to remove.
          Click the "REMOVE" button to delete the user from the Firebase Realtime Database.
