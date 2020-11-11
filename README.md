# System Login and Logout
 
This applications helps you to register, login and logout. 
It is made with the helpp of django. 

Clone this repository using this command:-

   `git clone https://github.com/Thakursim/Login`

# Getting up and running.
`cd Login`

This steps below will get you up and running with a local development environment. We assume you have the following installed:

  - pip
  - virtualenv

First make sure to create and activate a virtialenv, then open a terminal at the project root and install the requirements for local development.

    $ pip install -r requirements.txt 

When you have installed all the required modules, get inside the src folder using this command. 

`cd login_logout`

Now you have to run a command to create a super user in the database. 
```sh
$ python manage.py createsuperuser
```
  You have to give a username, email address, and a password. By doing this you are good to go for the next step. 
 After getting inside of the login_logout folder run this command to open the web page on the browser. 
 ```sh
 $ python manage.py runserver
 ```

- Copy the http address visible on your shell, while pasting it in your browser add **/admin**.
Login there with your credentials. 
- There you can see the **users**, by clicking on that you can see all the users using this application. 
- As you are already logged in with that superuser credentials, so now you can type **/accounts** to get a page from where you can *logout*.
- When you will logout then you can see a new page **System login**,  there you can register yourself if you want to create a new user or you can login with your registered credentials also.
- After clicking on LOGIN a new page will apper with a greeting along with the username. 


