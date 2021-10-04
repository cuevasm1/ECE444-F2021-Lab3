
Janelle - This is Janelle. This repo is a clone of https://github.com/nelaturuk/education_pathways

ACT 1:
![image](https://user-images.githubusercontent.com/43123955/135801246-b41c5929-4213-4641-9f78-12fa91a0d356.png)

ACT 2:
![image](https://user-images.githubusercontent.com/43123955/135801372-27cab00f-5274-4ad2-87ac-fd8d5384a49f.png)

ACT 3:

![image](https://user-images.githubusercontent.com/43123955/135804832-c29018e4-f6d6-449f-afc8-90e17f959041.png)


ACT 4:

ACT 5:

Function requirement: Execute course word query and return courses related to the word or that contain the word in it's course description. The website does not give feedback when a query does  not find any results for a word. I would add an error message to provide the client some feedback.

Non Functional Requirement: Aesthetically pleasing - this website is "ugly", it looks like basic code was used. The presentation of courses are also close together and at times, it is hard to see where course information starts or stops. I would improve this by using html templates to greate webstie marginsaround the entire page. I would also add padding around the course information.





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
