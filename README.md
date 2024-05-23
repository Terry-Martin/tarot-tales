![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# TarotTales
(Developer: Terry Martin)


[Live webpage](terry-martin.github.io/tarot-tales/)

## Table Of Contents

1. [Project Goals](#project-goals)
    1. [Creator Goals](#creator-goals)
    2. [Player Goals](#player-goals)
2. [Game Info](#game-info)
    1. [Game Story](#game-story)
    2. [Game Basics](#game-basics)
    3. [Flow Chart](#flow-chart)
3. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requrements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
4. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colour](#colour)
5. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks and Tools](#frameworks-and-tools)
6. [Features](#features)
7. [Testing](#validation)
    1. [Python Validation](#PYTHON-validation)
    2. [Bugs](#Bugs)
8. [Deployment](#deplyment)
9. [Credits](#credits)
10. [Acknowledgements](#acknowledgements)

## Project Goals

### Creator Goals
- Build HTML and CSS project
- Create a three page website about tarot readings
- Home page to give general information around what we offer
- Cards page to give the user a view of some of the marjor cards
- Allow user to make a booking


### User Goals
- Learn about tarot
- View website offerings
- Select a date and time and make a booking

### Flow Chart
![flow chart image](images/flowchart.jpg)

## User Experience

### Target Audience
The website is designed with the following target audience in mind:
- Project assessor
- Student peers
- People with an interest in html and css
- People with a interest in tarot cards


## Design

### Design Choices
The website was created with amobile first approach and scaled up for larger screens

### Colour
Basic colours were chosen from those available through https://pypi.org/project/colorama/

## Technologies Used

### Languages
The following languages were used to develop the website:
- HTML
- CSS

### Frameworks and Tools
The following tools were used to develop the website:
- Gitpod
- Github


## Features

### Data stored and taken from Google Sheets

![image](images/sheet.jpg)


### Title

![image](images/title.jpg)

- Made with Colorama and Pyfiglet



### Player Name and Stats

![image](images/name_stats.jpg)

- Allows user enter their name
- Displays current stats


### Error Handling

![image](images/error-handling.jpg)


## Testing


### Bugs

- Bug: When adding pyfiglet and colorama
- Fix: Rearrange order of inport statements at top of run.py

- Bug: In deployed site after adding pyfiglet and colorama
- Fix: Add names and versions to requirements.txt

- Bug: Using Character class out of scope
- Fix: Pass data through arguments in functions

## Deployment
- Code placed in the `run.py` file
- Dependencies placed in the `requirements.txt` file

## Creating the Heroku app

Followed instructions from Code Institute:
- Add two buildpacks from the _Settings_ tab. The ordering is as follows:
- 1. `heroku/python`
- 2. `heroku/nodejs`
- Create a _Config Var_ called `PORT`. Set this to `8000`
- For credentials, create another _Config Var_ called `CREDS` and paste the JSON into the value field.
- Connect  GitHub repository and deploy
- The deployment terminal is set to 80 columns by 24 rows.

- Part 1 - https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LS101+2021_T1/courseware/293ee9d8ff3542d3b877137ed81b9a5b/e3b664e16366444c8d722c5d8340b340/
- Part 2 - https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LS101+2021_T1/courseware/293ee9d8ff3542d3b877137ed81b9a5b/e3b664e16366444c8d722c5d8340b340/


### Code

- Validation code based on: https://www.youtube.com/watch?v=LUWyA3m_-r0

### Next steps
- Move all string\text to excel sheet "text"

## Acknowledgements

Thanks to all the below:
- Classmates who are always on halnd to help out
- Slack community
- Course facilitator (Lewis Dillon)