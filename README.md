# Overview 

In this activity you will learn how to deploy a web application using [Python Anywhere](https://www.pythonanywhere.com/), a cloud-based Python development and hosting environment, supporting over 400,000 users across 100 countries and hosting more than 50,000 websites. Acquired by Anaconda in 2022, the tool aims to enhance collaboration, accessibility, and infrastructure management for Python developers, especially in educational and team settings.

# Setup

After creating your account and signing in to PythonAnywhere:

* Navigate to the Web tab.
* Click Add a new web app.
* Follow the wizard’s instructions to set up a sample web application.

Once your sample app is running successfully, locate the app’s folder and edit its contents to customize the application according to your needs.

PythonAnywhere supports virtual environments, allowing you to install and manage your preferred Python libraries—such as Flask-Login, Flask-WTF, and others—without affecting the system-wide configuration.

Additionally, PythonAnywhere offers a RESTful API that makes it easier to automate tasks and integrate with other tools or workflows. You can find more information and documentation about their API [here](https://help.pythonanywhere.com/pages/IntegratingWithPythonAnywhere/).

# Instructions

1. Open a Bash console on PythonAnywhere.
2. Navigate to your web app’s folder, typically named mysite. 
3. Clone this activity’s repository into the folder. 
4. In the Web tab, update the following settings:
* Source code: mysite/act-09-python-anywhere/src
* Working directory: mysite/act-09-python-anywhere
5. Edit the WSGI configuration file, setting the project_home variable to  the act-09-python-anywhere/src folder. 
6. Reload your web app from the Web tab.
7. Test your app to ensure it’s running correctly.

