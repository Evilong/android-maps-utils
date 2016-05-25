#![alt text] (./images/googlemaps.png "Google Maps")Google Maps Android API utility library

##Table of Contents
 1. [Overview](#overview)
 2. [System Requirements](#system-requirements)
 3. [Functional Requirements](#functional-requirements)
 4. [Non-Functional Requirements](#non-functional-requirements)
 5. [Starting up and running the project on Android Studio](#starting-up-and-running-the-project-on-android-studio)
 6. [4+1 View](#41-view)
	1. [Logical View](#logical-view)
	2. [Process View](#process-view)
	3. [Physical View](#physical-view)
	4. [Development View](#development-view)
	5. [Scenarios](#scenarios)

##Overview

The [Google Maps Android API utility library](http://googlemaps.github.io/android-maps-utils/) is a library that enables the Android developers to extend the functionalities of [Google Maps Android API](http://developer.android.com/google/play-services/maps.html). As an extension it means that it offers the original with some new features.
This library is a open-source project, distributed with [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0), and is being developed by Google along side with GitHub community bringing the number of contributors up to 30.

##System Requirements
This library is a specialized tool for Android development and as such it requires:
 1. [JDK](http://www.oracle.com/technetwork/java/) is a set of development tools that allows the creation of Java applications.
 2. [Android SDK](http://developer.android.com/sdk/) is a  set of development tools that allows the creation of Android applications.
 3. [Google Play Services](https://developers.google.com/android/guides/overview) is a API for the deverse Google-powered features such as Google Maps and Google+.

It is also recomended to utilize the following tools for project managment:

1. [Android Studio + Graddle](http://developer.android.com/sdk/) is the official IDE for Android app development.
2. [Maven](https://maven.apache.org/) is a software project management and comprehension tool.
3. [Eclipse](https://eclipse.org/) + [ADT](http://developer.android.com/tools/sdk/eclipse-adt.html) , Eclipse is a powerfull and well known Java IDE and ADT is a pluggin to extend it's abilites to work with Android Projects

##Functional Requirements
This library has to be able to offer the full potential of Google Maps and also delivers the freedom to the user to be able to create new functionalities and modify others.

##Non-Functional Requirements
The following is order by importance to the project.
 - Compatibility - Needs to be able to work with a bunch of diferent versions of Android.
 - Scalability - Needs to be able to add features as many as the user wants while maintaining the performance.
 - Performance - Need to ensure fast responses to the apps utilizing it, so the app can maintain it's performance.
 - Usability - Needs to remain easy to understand and implement.

##Starting up and running the project on Android Studio

 - Download the latest [Android Studio](http://developer.android.com/sdk/index.html) version
 - Clone the source with git:

> $ git clone https://github.com/googlemaps/android-maps-utils.git

 - [Import the project on Android Studio](./images/import.png)
 - Let the IDE run the Gradle scripts
 - [Now the project is ready to start developing](./images/ready.png)
 - [You can also run the demo app](./images/demo.png)
 
##4+1 View

####Logical view
![alt text] (./images/LogicalView.png "Logical View Diagram")
####Process view
####Physical view
####Development view
####Scenarios
The use cases for this project are few, not because it's a piece of software with little to none features but because it's and extremely focused project that is aimed for Android Developer that want to improve their applications.
Becase of this, in the following diagram only represent the view of a developer !!!
![alt text] (./images/UseCaseDiagram.png "Scenarios Diagram")
