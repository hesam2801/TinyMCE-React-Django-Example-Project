# TinyMCE React Django Example Project
## Introduction:
This project demonstrates how to integrate TinyMCE, a powerful rich text editor, with React for the frontend and Django as the backend. It allows users to create, edit, and manage content, including images. The Django backend handles the storage and retrieval of text and media, making it a fully functional web application for managing rich text content.
#### Key features include:
- Rich Text Editing with TinyMCE
- Image Upload and management
- Django API for handling content persistence
- Seamless integration of frontend and backend \
This project serves as a practical example of using TinyMCE with React and Django, providing a flexible and scalable content management solution.
## Installation:
Follow these steps to set up and run the project locally. This guide covers installing dependencies, configuring the Django backend, and starting the React frontend. You'll have a fully functioning text editor with media support once everything is up and running.
- Step 1: Clone the repository: \
`git clone https://github.com/hesam2801/TinyMCE-React-Django-Example-Project.git`
- Step 2: Step 2: Switch to command mode in the terminal, run the following command in the terminal: \
`cmd`
- Step 3: Create a virtual environment folder (.venv) to install the required packages from the req.txt file. To set up the virtual environment, run the following command in the terminal: \
`python -m venv .venv`
- Step 4: Now, activate the virtual environment (.venv) to install the packages from the req.txt file within the virtual environment, run the following command in the terminal: \
this code is for windows: \
`.\.venv\Scripts\activate` \
this code is for mac: \
`source ./.venv/bin/activate` 
- Step 5: After activating the virtual environment (.venv), proceed to install the packages listed in the requirements.txt file, run the following command in the terminal: \
`pip install -r req.txt` 
- Step 6: Open a new terminal window and navigate to the frontend folder using the cd command, run the following command in the terminal: \
`cd .\frontend\` 
- Step 7: Now, it's time to install the necessary npm packages, run the following command in the terminal: \
`npm install`
## How to lunch:
- To start the server, open the first terminal window and enter the following command:
`python manage.py runserver`
- Next, switch to the second terminal window and enter the following command:\
`npm start`