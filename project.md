---
title: My Project Idea
---

<!-- References for links -->
[home]:index "Home"

[pascal_wiki]: https://en.wikipedia.org/wiki/Pascal_(programming_language) "Pascal"
[c_wiki]: https://en.wikipedia.org/wiki/C_(programming_language) "C Language"
[esta]: https://www.esta.vic.gov.au "Emergency Services Telecommunications Authority"
[oua]: http://www.open.edu.au "Open Universitys Australia"
[googleLink]: https://careers.google.com/jobs/results/82102238182286022/ "Google Software Engineer"
<!-- References for images -->
[googleJob]:img/googleJob.png "Google Software Engineer"
[mbtiResult]:img/mbtiResult.png "MBTI Result"
[bigFiveResult]:img/bigFiveResult.png "Big 5 Result"
[learningStyle]:img/learningStyle.png "Learning style Result"

# Project Idea
## Overview
I have started developing an Android Application for my work. We all currently rotate on a 4 on and 4 off (2 x 12-hour day shifts, 2 x 12-hour night shifts), some shifts not all attract penalty rates which can make knowing what you are being paid difficult. The application calculates 26 fortnights of wages (including shift penalties) and displays the net amount for the user. It allows for sick leave, annual leave, shift swapping via an editable roster page. The idea that if the user wants to know what is coming in on payday this is a quick reference.

## Motivation
There is currently an Excel spreadsheet that has been developed over many years, is extremely accurate and widely used. Its main problem though is it uses Microsoft Excel and must be used from a Laptop/Desktop computer that has VB capabilities. So, if you just want to know what is being deposited in a particular fortnight you need to fire up a computer, wait for it to load, get into excel and navigate to the tab on the sheet. 
The app will be a one tap display of your current net pay. A lot of people at my workplace have shown a great interest for this.

## Description 
The app will be designed initially on Android Studio using Java programming language and xml style android tabs. The design will be a bottom navigation pane with 2 options for “Fortnight Pay” and “Settings”. It will be available on Google’s Play Store at a cost of $10 to the user, Ad free.

The intention to port to Apple IOS at a later date (after I learn how to create IOS applications because at the moment I haven’t even looked at it).

On startup, the application will ask you what site of ESTA (Emergency Services Telecommunications Authority) you currently work at (Ballarat, Melbourne, Burwood) as the rosters are slightly different at each center.
It will then ask the user to input their primary service (Police, CFA/MFB, Ambulance) as this also changes the roster format. The current pay level the user is on (6 different levels, that changes the base rate), the current crew they are working on to work out the days rostered, if the user has a HELP/SFSS debt to work out extra tax and how many current hours or annual/personal leave entitled.

After the initial setup the primary tab on the application will be “Fortnight Pay” which will display 14 (editable) days of the fortnight with the shift the user is rostered to work, then in big bold text the net amount being deposited.
The user will be able to edit any of the 14 days displayed from a drop-down box (to eliminate input errors) to either day, night, afternoon, personal leave, annual leave or leave without pay.

It will need to have a function that in the scenario of a user going up in pay level or changing crew that it will update the remaining fortnights following the change.

The application will also calculate if the user takes leave (annual/personal) and update the running total of entitlements to the user. Also adding 7.45 hours of leave to every fortnight worked keeping in mind it does not accrue when the user does not have enough personal leave entitlements.

I have spoken to ESTA management about this and agreed upon the terms that it must not have any ESTA logo’s, references and must be submitted prior to putting the application live on the Google Play Store.

## Tools and Technologies
I will be using Android Studio which is based on JetBrains’ IntelliJ IDEA software. The application will be coded in Java programming language and the GUI in xml files which Android Studio creates for the developer but also allows to manual editing.

My old laptop (2011 Toshiba 15”) made doing any software development difficult due to screen size and processing power so as a result I have purchased a new Acer Predator 17” laptop (primarily for my RMIT course) 2 Phillips 25” monitors which are wall mounted to make it easy to have code 1 side and final product the other side as well as the Oracle website for referencing methods. 

## Skills Required 
The skills needed to create such an application is adept knowledge in Java programming language and adept knowledge using android studio. The functions of the code will need to be designed before starting to make sure it all flows and is easily upgradeable in the future.

The minimum hardware requirement for this application will be any smart device running android 7.0 or later due to needing access to modules not included in previous android versions. Most devices today meet these requirements with less than 16% of the worlds android devices using Android 6.0 and below (none of them would be at a communications company)

I envision doing this project solo due to knowing the requirements of the workplace, but I believe the project would benefit from some sort of design as I feel I lack in the area of making GUI’s pretty.


## Outcome
If this is successful, the outcome would be a lot of happy 000 employees who like to know how much are they getting paid every fortnight without having to wait 10-15 minutes to find a computer/laptop and boot it up.

This will change things for a lot of employees who need to make decisions based on their wages (I know not everyone lives pay to pay but a lot do). In a down week of only week day shifts (no penalties) you might try and pickup some overtime and vice versa if your normal roster is all weekend shifts (very high penalties) you may want to purchase that new laptop and 2 new screens because the budget allows.

Also, the learning benefits for the developer, Multiple java files and activity xml’s, 2D arrays and HashMap’s! How do you even get an app on the Play Store? Well now I know…

___

[Back][home]