### What is this?
A very simple SPA voting system for conferences and other alike events. Simply click on one of 3 faces (happy, whatever, bad) to vote. This is mobile app and it is working on PhoneGap and Ionic. Using `HTML5 local storage` to save data.

Note: This is practically the same as [votiepi-app](https://github.com/Teodors/votiepi-app) except it works offline. Some time later it might get merged together. 

### Getting started
You will need [ionic](http://ionicframework.com/) installed and [node](http://nodejs.org/) installed.
 1. Create app with `ionic start myApp blank`. 
 2. Run `ionic add platform android` to create android app or replace with ios for iphone (not tested). 
 3. Replace contents of `www` directory with this repository.
 4. (Optionally) add description in `config.xml` or change app icon in `platforms\android\res`.
 5. Run app with `ionic run android`. If you have your phone plugged in with all drivers installed it will run on phone, else it will run on virtual machine.

### Features
 * Responsive design for your smart devices

### TO-DO
 * Add diagrams
 * Remove last vote

### Issues
Found a bug or better solution? Please report to the issue section.
