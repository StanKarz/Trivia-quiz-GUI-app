# Trivia Quiz App

This Python project makes requests to the https://opentdb.com/api.php API and retrieves 10 random true or false (boolean) questions. The Graphical User Interface (GUI) was built with Tkinter the ui.py file contains all the code that customises the visual aspect of the App. Questions are displayed to the user along with an option for true or false. The user receives feedback after each response, the quiz_brain.py file is responsible for keeping track of the user score and providing feedback. The main.py ties together all the python files and intiates the quiz app. 

### Prerequisites

This project relies on the requests and Tkinter libraries. As Tkinter already comes installed with Python already, you will only need to install the requests module.

### Installing

The following command can be used to install the requests library

```
$ python -m pip install requests
```

## Built With

* [Tkinter](https://docs.python.org/3/library/tkinter.html) - Used to build the GUI for the quiz app
* [Requests](https://pypi.org/project/requests/) - Used to make HTTP requests to https://opentdb.com/api.php and retrieve data
