# CB Angular/App Test

Greetings, candidate. Welcome to Colossusbets challenge! Please read carefully the README before starting the test.

If you run into any issues please contact aurel.tirnovanu@colossusbets.com.

Good luck!

### 1. Getting started

This repository is a simple Angular CLI generated project. Contains no styles and no pre-defined logic. It is based on Angular 11.x default CLI generated project.

### 2. Coding Test

Firstly, there are 2 branches in this project (do not use the master branch): `feature/cordova` and `feature/capacitor`. You can choose the one you prefer and you feel more comfortable to solve the exercise. 

***From one of the branches of your choosing, clone and create another branch with your solution.***

##### 2.1 Test description

In order to complete the test, the following requirements of the project/ app need to be met:

- need to contain 2 components, based on routing
- within the app, when you come from any of those 2 deeplinks(explained below) you will display the query parameters within the appropiate component and you will save them to native localstorage with a 1h expiration
- closing the app and opening it again, will redirect you automaticaly to the route saved in localstorage

***Deeplinks:****

`cbionic:///facebook?utm_campaign=[VALUE]&utm_medium=[VALUE]`

`cbionic:///twitter?utm_campaign=[VALUE]&utm_medium=[VALUE]`


And basically you should display within the app the `utm_campaign` and `utm_medium` parameters value.


You have ***2 hours*** to complete the test. 


### Note: if you require any other packages or configuration, feel free to install it
