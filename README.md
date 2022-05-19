# data-mgmt-web
Website for large scale data management project

**PREREQ**

Start up a new python virtual environment using "python3 -m venv [NAME OF ENVIRONMENT]" or any other virtual enviornment wrapper of your choosing
After doing so, on windows run "[NAME OF ENVIRONMENT]\Scripts\activate.bat"
                on linux run "[NAME OF ENVIRONMENT]/bin/activate"
More info for python virtual environment: https://docs.python.org/3/tutorial/venv.html

Then install required modules in requirements.txt
Should be "pip install -r requirements.txt" (although I'm not too sure).

**END OF PREREQ**

To run the server, simply run "python manage.py runserver" in the directory manage.py is under.
At this point you can test if the application works correctly by going to localhost:8000 and localhost:8000/about.

# THIS PROJECT IS CURRENTLY DEPLOYED ON HEROKU
https://lsdm-yt-data.herokuapp.com/
## If website is not functioning, it is because the DB is down and needs to be recreated due to hosting
