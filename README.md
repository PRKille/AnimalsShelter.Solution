# _Animal Shelter_

#### _Animal shelter with database site, 3/17/2020_

#### By _**JW/PK/PD**_

## Daily Summary
_We were able to build the basic functioning site for the animal shelter.  We set up a database, are able to add new animals with a form, and view each animal's details by clicking on their name.  We played with sorting the index list in different ways, and it is currently set to sort by date of admittance._
_The main issue we struggled with was trying to get the date format in C# and our database to cooperate.  We tried a number of options, and ended up converting the date to a string and saving it in the database that way.  We received the date information in the datetime format, so each date string will be formatted similarly, and thus we are able to compare and sort based on this data.  We also attempted to have a boolean value for "plays well with others" but didn't have much success, and didn't have time to pursue the solution._
__
## Description

_The app is a tracking system for animals in the shelter.  Upon landing on the splash page, a user can navigate to the index list of animals, add new animals, and see the list sorted by date of admittance._

## Setup/Installation Requirements

* _Setup requires dotnet core_
* _Clone from https://github.com/fractalscape13/AnimalShelter_
* _From AnimalShelter directory, run "dotnet restore" and "dotnet build"_
* _In terminal, enter "dotnet run" to run program and view on localhost:5000 in browser_
* _Open files in text editor to view code_

## Specifications

* _User may navigate between pages._
    * _Example: Input: Home page -> Create New Animal Page_
    * _Output: All code written for New Animal Page is run_

* _User may create a new Animal._
    * _Example: Input: Click link to New Animal Page._
    * _Output: A new Animal object is added to the shelter list._
    
* _User may click on an animal's name to view specific details._
    * _Example: Input: Click animal's name in index list._
    * _Output: Specific details about the animal being clicked on are revealed to the user._ 

## Known Bugs

_There are no known bugs at the moment._

## Support and contact details

_If you have any questions, comments, concerns, or suggestions, feel free to contact us by submitting a pull request._

## Technologies Used

* _Command Terminal_
* _Git_
* _VS Code_
* _HTML_
* _CSS_
* _C#_
* _.NET core_
* _Asp.Net core_
* _MVC_
* _MYSQL_


### License

*MIT License*

Copyright (c) 2020 **_JW, PK, PD_**