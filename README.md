# Project Goal
This project creates an Android app that retrieves the data from https://fetch-hiring.s3.amazonaws.com/hiring.json

- Display this list of items to the user based on the following requirements:
- Display all the items grouped by "listId"
- Sort the results first by "listId" then by "name" when displaying.
- Filter out any items where "name" is blank or null.

The final result is displayed to the user in an easy-to-read list.

# Major Folders & Files
ListApplication\app\src\main\
- AndroidManifest.xml: a file that describes all the components of the Android app and is read by the Android runtime system when the app is executed

ListApplication\app\src\main\java\com\example\listapplication
- DataItem.java: a class for holding the data retrieved from the remote json file
- RetrieveItemsTask.java: a class to handle data retrieving
- MainActivity.java: a class to display the data

ListApplication\app\src\main\res\layout
- activity_main.xml: creates the layout file for the main activity

ScreenRecording.webm
- Screen recording the content displayed on the mobile screen when the app is running

## Android Studio App Version
Latest version for Windows as of 1/10/2024: Android Studio Hedgehog | 2023.1.1

The above code has been built, run and tested successfully on virtual devices emulating the Pixel 7 and the Pixel 2.
