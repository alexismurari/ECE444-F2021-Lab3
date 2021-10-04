# Alexis Murari
This repo is a clone of https://github.com/nelaturuk/education_pathways
## Activity 1
![Screenshot from 2021-10-01 18-04-32 (2)](https://user-images.githubusercontent.com/60163267/135779404-34401c1a-c023-41b5-b433-962b8aad2f59.png)

## Activity 2
![Screenshot from 2021-10-01 18-40-18](https://user-images.githubusercontent.com/60163267/135779441-af265112-dedc-4e2f-bee8-9cf372d02097.png)

## Activity 3
![Screenshot from 2021-10-01 18-51-52 (2)](https://user-images.githubusercontent.com/60163267/135779472-cb829689-7f30-4d83-bc60-613e6d073d32.png)

## Activity 4
![Screenshot from 2021-10-01 18-53-06](https://user-images.githubusercontent.com/60163267/135779486-bb4f0a34-fbb5-4227-8407-0e4b782e5353.png)
![Screenshot from 2021-10-01 19-05-22 (2)](https://user-images.githubusercontent.com/60163267/135779505-18153039-2cd2-4571-8e73-627f8ed035b5.png)

## Activity 5
Functional Requirement: I think the search is lacking a lot of filters that are useful for students such as AU credits if a students needs to search a course in a specific field of his degree and also remove some imposed filters such as the "Year" filter as it is not always relevant for courses (students in 4th year ECE can still be interested by courses in 300 series). The website should have more search filters to allow better and more accurate search for users.

Non-Functional Requirement: The website only takes a specific type of input, as it does not give out the same results if the word in the tag field has a capital letter. I think the inputs from the tags should not be affected by capital letters and treat each inputs the same way. The website should be able to treat inputs in different formats (capital letters or not).

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
