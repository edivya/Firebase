## Firebase
There are two main types of storage we will use to save data:

* Client Side Storage: uses cookies, sessionStorage, and localStorage to save and reuse user data across a user’s session.
* Server Side Storage: saves user info to a database that can be reused across multiple devices and sessions. We'll use Firebase to accomplish this.

**Most Recent User**

* Using the file above as a starting point, create an app that stores each new user in a Firebase database.

* Your app should update in real time - if multiple browsers windows are open to the app at the same time, they should all update with the new information if a new user is added.

**Count Down Button**

* Firebase database to store the click data on the backend.
* Your application should be able to run on multiple browser windows simultaneously and register click events on each screen correctly.

**Coder's Bay - View Tracker**

*.set() overwrites everything in the specified directory, so we will need to use .ref() to store bidder data and connections in different folders.
