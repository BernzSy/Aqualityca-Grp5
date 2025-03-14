# Aqualityca
Aqualityca establishes its focus on delivering water quality assessment methods that combine viable access while maintaining both precision and operating efficiency for water refilling services. This AI-based web application performs water potability assessments using user-generated test strip results for pH and chlorine concentration together with turbidity and hardness measurements and total dissolved solids (TDS) analysis. Through its manual data entry system combined with an intelligence algorithm, the solution eliminates the requirement of cumbersome systems and complex machinery. This system delivers comprehensive water analysis which either identifies water as "potable" or "non-potable" while providing information about parameters that deviate from recommended ranges. The system produces fundamental statistical reports that present parameters of water quality average values median values and most frequent readouts throughout specified time ranges. These features of this project are designed to assist businesses in maintaining compliance with health and safety standards, improving decision-making, and ensuring the consistent delivery of safe drinking water. 

## How to setup the application on the local environment of users? 
In this project, we have made the decision to use Django as the framework for managing our database. Django is a high-level Python web framework that comes with an integrated Object-Relational Mapping (ORM) system, allowing us to interact with the database efficiently.

In addition, Django's migration system simplifies database schema changes, ensuring that any updates or modifications to the data structure are handled seamlessly. By using Django's powerful and efficient database handling capabilities, we can ensure that our project maintains data integrity, security, and performance while reducing the complexity of database management.

Let's get started in [Django](https://www.w3schools.com/django/django_getstarted.php)!

### Install Python
Django requires Python for the Project.

If you have already Python to the system, check the version of Python by running this command:
```
python --version
```

If you haven't installed it, you can download it for free [Python](https://www.python.org/).

### Create Virtual Environment For Django
It is highly recommended to set up a dedicated virtual environment for each Django project to maintain dependency isolation and prevent conflicts between different projects. One common tool for managing virtual environments is `venv`, which comes pre-installed with Python.

You can choose any name for your virtual environment based on your preference. In this tutorial, we will name it `myworld`.

Before creating the virtual environment, ensure that you navigate to the desired directory where you want to set up your Django project. Once you are in the correct location, enter the following command in the command prompt:

Windows:
```
py -m venv myworld
```
Unix/MacOS:
```
python -m venv myworld
```

This will set up a virtual environment, then create a folder named "myworld" with subfolders and files, that look like this:
```
myworld
  Include
  Lib
  Scripts
  pyvenv.cfg
```

To activate the environment, type this command:
Windows
```
myworld\Scripts\activate.bat
```
Unix/MacOS:
```
(myworld) ... $
```
