# Team Profile Generator

[![License: MIT](https://img.shields.io/badge/license-MIT-yellowgreen)](https://opensource.org/licenses/MIT)

## Description

The homework 10 of the UWA Bootcamp tasked the students with building a team profile generator CLI application and would generate an HTML team profile page that had cards for one team manager, and multiple engineers and/or interns on the team. 
This project is packaged with pre-made Jest testing files that the student had to use in conjunction with building out the applications's class js pages to ensure that the class constructors and the extensions for the various roles needed for the profile were properly working and would pass all tests. The student also need to build out the main js file (app.js) for the CLI application to take in the input of information for each type of role and then export that information into an HTML generated file.
To prompt the CLI user for the team profile roles and information about each specific role, the inquirer node package was used. Utilizing inquirer a series of questions will be asked to the user to create the each team members profile.
Once all team profiles were generated and no new users needed to be added, the CLI application will render an HTML page in the output folder based on a series of HTML templates found in the Template directory.Once the new profile was filled in and pushed to the array, it would then re-call the function to prompt the user to add another team member.
If the user said no, this would end the application and export the HTML file with a team profile generated success message. Since this function gets re-called each time a new employee has been added to the array, you can keep adding new profiles to the page until you select the option for no more team members. 

## Demo

<img src="/images/team_profile.png">

<img src="/images/init_1.gif">

<img src="/images/init_2.gif">

<img src="/images/init_3.gif">

<img src="/images/main_app.gif">

[Video Link](/images/init_Short.mp4)

[Video Link]("/images/init_Short_2.mp4")

[Video Link]
(https://drive.google.com/file/d/1oKNL2Lid78hXYkOJRnlkG_Cd9_HW4-M6/view?usp=sharing)

[Video Link]("/images/MainCLI.mp4")

## Table of Contents

-   [Installation](#installation)
-   [Usage](#usage)
-   [License](#license)
-   [Tests](#Tests)
-   [Authors](#Authors)
-   [Acknowledgments](#Acknowledgments)
-   [Questions](#questions)

## Installation

To install this app, you need to clone (or download) this to your local machine. Then, you will need to install the node dependencies by running npm install dependencies or module command on  your Terminal

## Usage

To use the app, run app.js from your terminal and answer the prompted questions and it will generate team.html file inside output folder


## License

    								MIT License

    		Team Profile Generator   Copyright (C) 2021 Naresh Raj Poudel

    		Permission is hereby granted, free of charge, to any person obtaining a copy
    		of this software and associated documentation files (the "Software"), to deal
    		in the Software without restriction, including without limitation the rights
    		to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    		copies of the Software, and to permit persons to whom the Software is
    		furnished to do so, subject to the following conditions:

    		The above copyright notice and this permission notice shall be included in all
    		copies or substantial portions of the Software.

    		THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    		IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    		FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    		AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    		LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    		OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    		SOFTWARE.


## Tests

The repo folder for this application includes four tests that are designed to test the functionality and information validation for the employee class and its three extended inheritance classes for Manager, Engineer, and Intern. These tests can be ran with the Jest node package dependency (which
will be installed when npm install is ran) and will detail how the structure of the class constructor and its extensions pass all validation tests.

## Authors

* **Naresh Raj Poudel** - [Git Hub Profile](https://github.com/citenaresh): https://github.com/citenaresh

## Acknowledgments

* Great gratitude to Luca ([https://github.com/duvet86](https://github.com/duvet86)), Sam ([https://github.com/sam-ngu](https://github.com/sam-ngu)) and Renata from the UWA Bootcamp for their enormous help.

## Questions

-   For any questions related to this applicaiton, please feel free to contact me at: citenareshn@gmail.com.

-   Please use this link to access my Github Profile: [Git Hub Profile](https://github.com/citenaresh): https://github.com/citenaresh
