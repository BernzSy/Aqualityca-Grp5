# Aqualityca
Aqualityca establishes its focus on delivering water quality assessment methods that combine viable access while maintaining both precision and operating efficiency for water refilling services. This AI-based web application performs water potability assessments using user-generated test strip results for pH and chlorine concentration together with turbidity and hardness measurements and total dissolved solids (TDS) analysis. Through its manual data entry system combined with an intelligence algorithm, the solution eliminates the requirement of cumbersome systems and complex machinery. This system delivers comprehensive water analysis which either identifies water as "potable" or "non-potable" while providing information about parameters that deviate from recommended ranges. The system produces fundamental statistical reports that present parameters of water quality average values median values and most frequent readouts throughout specified time ranges. These features of this project are designed to assist businesses in maintaining compliance with health and safety standards, improving decision-making, and ensuring the consistent delivery of safe drinking water. 

## How to setup the application on the local environment of users? 
In this project, we have made the decision to use Django as the framework for managing our database. Django is a high-level Python web framework that comes with an integrated Object-Relational Mapping (ORM) system, allowing us to interact with the database efficiently. 

Django must also be compatible with the version of SQL being used to ensure smooth operation. It is also responsible for determining the structure of the URLs in the application.

In addition, Django's migration system simplifies database schema changes, ensuring that any updates or modifications to the data structure are handled seamlessly. By using Django's powerful and efficient database handling capabilities, we can ensure that our project maintains data integrity, security, and performance while reducing the complexity of database management.

Let's get started in [Django](https://www.w3schools.com/django/django_getstarted.php)!
<br>

### Install Django
Make sure that you have already downloaded the python with the `pip`, since it is important for the Django for installation. To know if you have it, type the command:
```
pip --version
```

Using the `pip` to install the Django, type the command:

Windows:
```
py -m pip install Django
```
Unix/MacOS:
```
python -m pip install Django
```

Result:
```
Collecting Django
  Downloading Django-4.0.3-py3-none-any.whl (8.0 MB)
      |████████████████████████████████| 8.0 MB 2.2 MB/s
Collecting sqlparse>=0.2.2
  Using cached sqlparse-0.4.2-py3-none-any.whl (42 kB)
Collecting asgiref<4,>=3.4.1
  Downloading asgiref-3.5.0-py3-none-any.whl (22 kB)
Collecting tzdata; sys_platform == "win32"
  Downloading tzdata-2021.5-py2.py3-none-any.whl (339 kB)
      |████████████████████████████████| 339 kB 6.4 MB/s
Installing collected packages: sqlparse, asgiref, tzdata, Django
Successfully installed Django-4.0.3 asgiref-3.5.0 sqlparse-0.4.2 tzdata-2021.5
WARNING: You are using pip version 20.2.3; however, version 22.3 is available.
You should consider upgrading via the 'C:\Users\Your Name\myworld\Scripts\python.exe -m pip install --upgrade pip' command.
```

After installing, check the version of Django that you have by typing this command:
```
django-admin --version
```

<br>
<br>

### Run the Django Project
Run the `aqualityca` project, as the next step is to ensure that you are working in the correct directory where you want to store your project files. Organizing your file system properly is essential for maintaining a structured and manageable development workflow.

Before proceeding, make sure you have already created and activated a virtual environment to keep your Django project isolated from other projects and prevent potential dependency conflicts. For this tutorial, we will be working within the myworld folder, which serves as our designated virtual environment.

Now, using the command prompt or terminal, navigate to the directory where you intend to store your Django project. You need to ensure that you are inside that folder before executing any Django-related commands. Once you have confirmed that you are in the correct location, you can proceed by running the following command in the command prompt:
```
django-admin startproject aqualityca
```

Now that you have successfully created your Django project, the next step is to run the development server and view your project in a web browser. Django comes with a built-in lightweight web server that allows you to test your application locally before deploying it to a production environment.

To begin, you need to navigate to the root directory of your newly created Django project. In this case, since the project is named my_tennis_club, you should ensure that you are inside the `/aqualityca` folder before executing any commands. This folder contains essential files, including the Django settings, URL configurations, and manage.py script, which is used to manage various aspects of your Django project.

Once you have navigated to the correct directory, you can start the Django development server by running the following command in the command prompt:
```
py manage.py runserver
```
If you do not have PIP installed, you can download and install it from this page:

Result:
```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
October 27, 2022 - 13:03:14
Django version 4.1.2, using settings 'my_tennis_club.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```
Open a new browser window and type 127.0.0.1:8000 in the address bar or click the local server if you are running the terminal in VsCode that will take you automatically open to the new browser.
