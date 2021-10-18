## Screenshot of Activities Required

<img width="1530" alt="Screen Shot 2021-10-17 at 11 34 46 PM" src="https://user-images.githubusercontent.com/53177360/137666841-b8557335-3399-4136-b6fb-a9380516e11c.png">


<img width="1675" alt="Screen Shot 2021-10-17 at 11 35 01 PM" src="https://user-images.githubusercontent.com/53177360/137666845-2f97254b-0185-4499-9857-dcb9e08b73a5.png">

The new UI is a lot more user-friendly and compartmentalized. It allows the user to see distinct secitons, and the color contrst also helps in the organization of the data for the user.

Note: For some reason, the border of search and center-alignment of education pathways would not work for me even though they are included in the code and I made sure that there is no typo or any such thing, so I am not sure where I went wrong. Please find attached snippets of code as proof:

<img width="258" alt="Screen Shot 2021-10-17 at 11 57 27 PM" src="https://user-images.githubusercontent.com/53177360/137667159-7a9d0bb9-3e8a-4e38-993d-ada7f82cbc86.png">




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
