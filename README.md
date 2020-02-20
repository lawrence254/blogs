# STEVE'S BLOG APP
BLOG-APP is a personal blogging website where you can create and share your opinions and other users can read and comment on them. blog-x also has random quotes that inspire the users. 

## Author
> Kebaso Steve Ongati


## Screenshot
<img src="landing.png">


## Requirements

The following command installs all the application requirements
>``pip freeze -r requirements.txt``


## Installations

Run 
``git clone https://github.com/KEBASOH/BLOG-APP.git``

or download the zip file from github.

After extracting the files, 

1. Navigate to the project folder
>`` cd BLOG-APP.`` 

2. Creating a virtual environment
>``virtualenv virtual.``

3. Activating the virtual environment
>``source virtual/bin/activate.``

4. Running the application

>``python3 manage.py server``

5. Running tests

 > ``python3 manage.py test.``


## Technologies used
* Python3
* Flask
* Html5
* Css3
* Bootstrap4


## User stories
* As a user, I would like to view the blog posts on the site
* As a user, I would like to comment on blog posts
* As a user, I would like to view the most recent posts
* As a user, I would like to an email alert when a new post is made by joining a subscription.
* As a user, I would like to see random quotes on the site
* As a writer, I would like to sign in to the blog.
* As a writer, I would also like to create a blog from the application.
* As a writer, I would like to delete comments that I find insulting or degrading.
* As a writer, I would like to update or delete blogs I have created.

## BDD(Behaviour Driven Development)
>Login Inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg johndoe``|
| Password  | Account password, ``eg parseword``|

>Signup inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg johndoe``|
| Email  | User email, ``eg morty@testmail.com``|
| Password  | Account password, ``eg parseword``|
| Confirm Password  | Account password, ``eg parseword``|

> Blog inputs

| Inputs | Description  |
|---|---|
|  Blog title | the title of the blog eg; `` Car news``  |
|  Blog post| The blog post itself|
| Comment| A comment on the blog post|



## License
> MIT License &copy; Kebaso Steve Ongati 2020

## Collaborate
To collaborate, reach me on [ongatikebaso@gmail.com]()
## Github live Link
- https://sleepy-garden-45210.herokuapp.com/

