# CARTE Education Pathways

This is the repo for Samir Khaki, Ani Srikanth, and Komila Rasulova's Lab5 submission. The repo is a clone of [CARTE's in-development](https://github.com/nelaturuk/education_pathways) tool for course selection at UofT.

<details>
<summary>Description and Setup Instructions</summary>

Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker

## Repository files:

`./Procfile ./wsgi.py` _tells gunicorn how to run the program_

`./environment.yml ./requirements.txt` _specifies python requirements for anaconda and pip respectively_

`./__init__.py` _main flask code_

`./readme.md` _this file_

`./resources:` _contains datasets used in the program_

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz graph.pickle`

`./static:` _contains any static elements of the webpage, in this case just the CARTE logo_
`CARTE_logo.jpg`

`./templates:` _contains flask templates for rendering HTML_

`_formhelpers.html course.html index.html results.html`

</details>

### Activity 1

![image](https://user-images.githubusercontent.com/14436239/197280721-3df909e2-cc8e-405c-b69b-539930ce6203.png)

### Activity 2

No code has been added to the CSS file yet, so the page looks unchanged. But the .css files have been linked as seen in the second screenshot.

![image](https://user-images.githubusercontent.com/14436239/197293520-db000649-0ba4-4e74-8cde-f10836d7feec.png)
![image](https://user-images.githubusercontent.com/14436239/197293410-658d69ce-a079-40ef-8210-3b3527adecc2.png)
![image](https://user-images.githubusercontent.com/14436239/197293823-7520211c-1340-4a8b-a0f7-85a24a98b987.png)

### Activity 3

Homepage:
![image](https://user-images.githubusercontent.com/14436239/197364210-7fa35506-93d0-4b63-b5fd-997df08bf32e.png)

Results:
![image](https://user-images.githubusercontent.com/14436239/197364303-cc9af7c8-75ed-4cd1-899c-ac687f873852.png)

### Activity 4
Homepage:
![image](https://user-images.githubusercontent.com/14436239/197905415-90e7e4b4-e44c-4d43-b676-c7b7d5bc27f1.png)
Results:
![image](https://user-images.githubusercontent.com/14436239/197905653-cab04e3c-ae93-4b73-adf5-3124966aa68e.png)

### Activity 5
![image](https://user-images.githubusercontent.com/14436239/197906963-d15ac0ed-42e5-4060-b1c3-e3b1a2281749.png)

### Activity 6
User Story 1.1:

![image](https://user-images.githubusercontent.com/14436239/198170359-d2559a5e-b9a2-4525-993b-2bcab73f3576.png)
![image](https://user-images.githubusercontent.com/14436239/198171274-6c40a7fd-7552-4779-9a8b-9a04d6f65098.png)

User Story 6.1:
![image](images/UserStory6_1.png)
![image](images/APS360SyllabusNotFound.png)

User Story 6.2:
![image](images/UserStory6_2.png)
![image](images/APS360DownloadSyllabus.png)
