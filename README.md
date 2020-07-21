# Web Scraper
## Web Scraper based on https://sandiego.craigslist.org/ using Django Web Framework 3.0 and 
* HTML
* CSS
* Python
* Materialize from https://materializecss.com/
* Django https://docs.djangoproject.com/en/3.0/
## Prerequisites
<pre>python== 3.5 or up and django==2.1.4</pre>
## Installing
<pre>open terminal and type</pre><br>
<code>git clone  https://github.com/art3mis69/Django-Web-scraper.git</code><br>
## To migrate the database open terminal in project directory and type
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code><br>
## Playing with the API
<code>python manage.py shell</code>
## Creating an admin user
First we’ll need to create a user who can login to the admin site. Run the following command:
<code>python manage.py createsuperuser</code>
Enter your desired username and press enter.
<pre>Username: admin</pre>
You will then be prompted for your desired email address:
<pre>Email address: admin@example.com</pre>
The final step is to enter your password. You will be asked to enter your password twice, the second time as a confirmation of the first.
``` Password: **********
Password (again): *********
Superuser created successfully.
```
## Django-app
Consists of Web Interface,where you can Search the craigslist Website on Beautiful Web UI

## The development server
run the following commands:
<code>python manage.py runserver.</code><br>
Now, open a Web browser and go to “/admin/” on your local domain – e.g., http://127.0.0.1:8000/admin/.
