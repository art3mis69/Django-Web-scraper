# Web Scraper
## Web Scraper based on https://sandiego.craigslist.org/ using Django Web Framework 3.0 and 
* HTML
* CSS
* Python
* Materialize from https://materializecss.com/
* Django https://docs.djangoproject.com/en/3.0/
## Prerequisites
` python== 3.5 or up and django==3.0 `
## Installing
` open terminal and type `
` git clone  https://github.com/art3mis69/Django-Web-scraper.git `
## To migrate the database open terminal in project directory and type
` python manage.py makemigrations `
` python manage.py migrate `
## Playing with the API
` python manage.py shell `
## Creating an admin user
First we’ll need to create a user who can login to the admin site. Run the following command:
` python manage.py createsuperuser `
Enter your desired username and press enter.
` Username: admin `
You will then be prompted for your desired email address:
` Email address: admin@example.com `
The final step is to enter your password. You will be asked to enter your password twice, the second time as a confirmation of the first.
`Password: **********
Password (again): *********
Superuser created successfully. `
## The development server
run the following commands:
` python manage.py runserver `
Now, open a Web browser and go to “/admin/” on your local domain – e.g., http://127.0.0.1:8000/admin/.
