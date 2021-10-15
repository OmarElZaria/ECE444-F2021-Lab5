This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1
<img width="1288" alt="Screen Shot 2021-10-14 at 11 53 40 PM" src="https://user-images.githubusercontent.com/46201075/137429696-ff407dd0-b9aa-4ed8-9a3e-c5443103c177.png">

## Activity 2-5
<img width="1438" alt="Screen Shot 2021-10-14 at 11 54 39 PM" src="https://user-images.githubusercontent.com/46201075/137429846-11ecd851-1d59-47c3-a264-24ce4db23607.png">
<img width="1426" alt="Screen Shot 2021-10-14 at 11 55 45 PM" src="https://user-images.githubusercontent.com/46201075/137429847-63122916-9f67-4834-a114-45eeef720242.png">
<img width="1426" alt="Screen Shot 2021-10-14 at 11 55 54 PM" src="https://user-images.githubusercontent.com/46201075/137429850-ee44059f-066f-439f-8968-bbe4b0f30b20.png">


## Activity 6
The Search for courses component in the new UI is better layed out than the old UI with every filter clearly indicating what its functionality is intended for. The line breaks removes confusion, clutter, and is a lot more pleasing for the eye.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
