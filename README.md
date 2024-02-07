# A Call Log Access App

![final call logs](https://github.com/sai-mudike/call_log_access_app/assets/127184650/c7f7e4b9-c1f5-4bbe-8f25-bce59e5c84ef)


 I've made a Flutter app that helps folks check their call history easily. In the app, you can see details like who called, their number, how long the call lasted, and when it happened. The app's design makes it simple to move around and look at your call log comfortabl

 Click => [Watch Code Explanation Here.](https://pub.dev/packages/permission_handler)



## Getting Started

To get started with this project, follow these simple steps:

## How to Use 

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/sai-mudike/call_log_access_app.git
```

**Step 2:**

Go to project root and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```


## Features:

* Handles Permissions
* Retrieve Call logs
* Display Call History
* Display Contacts
* Search Contacts
* Dark Theme
* Calls


### Libraries Used

* [permission_handler: ^11.2.0](https://pub.dev/packages/permission_handler) (For handling Permissions.)
* [call_log: ^4.0.0](https://pub.dev/packages/call_log) (To Retrive and Display Call History.)
* [flutter_phone_direct_caller: ^2.1.1](https://pub.dev/packages/flutter_phone_direct_caller) (To make calls.)
* [intl: ^0.19.0](https://pub.dev/packages/intl) (For Date and Time Format.)
* [contacts_service: ^0.6.3](https://pub.dev/documentation/contacts_service/latest/)
* 


### Folder Structure
Here is the core folder structure which flutter provides.

```
flutter-app/
|- android
|- build
|- lib
|- test
```

Here is the folder structure we have been using in this project

```
lib/
|- screens/
|- widgets/
|- helpers.dart
|- main.dart
```

```

1- screens — Contains all the ui of your project, contains sub directory for each screen.
2- widgets — Contains the common widgets for the applications.
2- helpers.dart — Contains the common helper functions for the applications.
4- main.dart - This is the starting point of the application. All the application level configurations are defined in this file i.e, theme, routes, title etc.
```



#Happy_Coding👩‍💻

