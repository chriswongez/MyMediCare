# MyMediCare

## TCC 3141 - Cloud Computing Project (made by Proton miao miao)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#development-tool">Development Tool</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#middlewares-or-apis">Middlewares or APIs</a></li>
    <li><a href="#version-control">Version Control</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

<p align="center">
  <img src="images/logo.jpg" width="300px" height="300px">
</p>

## What is MyMediCare?

MyMediCare is a combined Body Mass Index(BMI) calculator and Calories Burn Calculator mobile application according to MIT App Inventor which is to measure the person's weight and height, and measure the calories burned by the user. Also, it can record the BMI or calories burn every time users calculate their latest BMI and calories burn. The app can display the charts for the users to show the recorded BMI or calories burn.

## Development Tool

This project is developed using [MIT App Inventor 2](http://ai2.appinventor.mit.edu/).

## Usage

Through this MyMediCare, users need to install an application named <b>MIT AI2 Companion</b> inside their mobile phone in order to connect with the [MIT App Inventor 2](http://ai2.appinventor.mit.edu/) from the browser. After connecting both of them, user will be directed to the MyMediCare with 3 functions provided which are <b><i>BMI Calculator</i></b>, <b><i>Calorie Calculator</i></b>, and <b><i>Show History</i></b>.

<li><b>BMI Calculator</b></li>
In this BMI Calculator tab, users will need to key in their name, weight(in kg) and height(in cm) to calculate their BMI. After keying in 3 of the fields, users have to press "<i>Calculate!</i>" button in order to calculate the BMI result. The screen will show the result of BMI and whether the user is Underweight, Healthy(Normal), Overweight, or Obese. After getting the result, the screen will show user a button "<i>Save name and BMI to database</i>" for users to save the calculated result into the database.
<br />
<br />
<li><b>Calorie Calculator</b></li>
In this Calorie Calculator tab, users will need to key in their name, distance(in km) based on their running distance, and weight(in kg) to calculate how much their calories have burned. After keying in 3 of the fields, users have to press "<i>Calculate</i>" button in order to calculate the Calorie Burn result. The screen will show the result of calories burn and whether they're Low calories burned, Normal calories burned, or High calories burned. After getting the result, the screen will show user a button "<i>Store Data</i>" for users to save the calculated result into the database.
<br />
<br />

<li><b>Show History</b></li>
In this Show History tab, when users press on the button, they'll be directed to the History Screen which allows users to view the <b>BMI History</b>, <b>BMI Chart</b>, <b>Calorie History</b>, or <b>Calorie Chart</b> after they save their result into the database.
<br />
<br />

## Middlewares or APIs

a) <b>HTTP</b>
MyMediCare uses the HTTP GET request to send data and retrieve data.
<br />
<br />
b) <b>Google Apps Scripts</b>

We use the Google Apps Scripts to connect the spereadsheet service which is one of the service from Google Workspace Service. We do some coding to makes the HTTP Get request data appeend to the spreadsheet code and the Apps Script will deploy as the web app. After that, we place the web app's URL inside the [MIT App Inventor 2](http://ai2.appinventor.mit.edu/) and the Google Apps Script will handle the HTTP Get request with the doGet() function. <br>
[Click me to the Google Apps Script](https://script.google.com/d/1xU2GPLoMgeCb1keA91DbpDdqIta6vCVNHUxDqsK8XWGKvym_skFi4WFl/edit?usp=sharing)

C) <b>Google Sheets</b>

We use Google Sheets as our database. All the calculated record and result will store in our spreedsheet. <br>
[Click Me to the Spreadsheet](https://docs.google.com/spreadsheets/d/1og_lD7-E5EnXVghbr1SuS-pMBfp9YDtwlT_2rUbfyrA/edit?usp=sharing)

## Version Control

In this project we keep improving our app, document version control is the process of tracking and managing different versions (or drafts) of a document so you know which is the current iteration of a file.We used the <b>Git for Desktop</b> to implement the version control on Github. There are a few version for our project:

<br> <b>MyMediCare V 0.1.0 (Pre-release) </b>
<br> Release date : 01/10/2021
<br> Author : Wee Pei Xiang, Lim Zheng Wei & Yeap Kai Feng
<br> Improvement : Design for BMI interface and add BMI calculation function and add calories burned function.

<br> <b>MyMediCare V 0.2.0 (Pre-release) </b>
<br> Release date : 25/10/2021
<br> Author : Chris Wong & Wooi Jin Yang, Yeap Kai Feng
<br> Improvement : Add store data history to database, improve friendly user interface and bug fix for calculation.

<br> <b>MyMediCare V 1.0.0 (Formal Edition) </b>
<br> Release date : 04/11/2021
<br> Author : Chris Wong, Wooi Jin Yang, Wee Pei Xiang, Lim Zheng Wei
<br> Improvement : Create an unique icon for the app and bug fix and improve quality of function and user interface.

## Contributing

Contributions are what make our application such a wonderful environment to learn, become challenged, but also build. Every support anyone can offer is much welcome.

1. Fork the Project
2. Create your feature Branch
3. Commit your changes to the fork
4. Push to the Branch
5. Open a Pull Request

## License

Distributed under MIT License. See [LICENSE](https://github.com/chriswongez/MyMediCare/blob/main/LICENSE) for more information.
