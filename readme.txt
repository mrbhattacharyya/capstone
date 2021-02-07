Modules:

asgiref==3.2.10
Django==3.1.1
django-crispy-forms==1.11.0
image==1.5.33
markdown2==2.3.9
Pillow==8.1.0
pytz==2020.1
six==1.15.0
sqlparse==0.3.1

Project Capstone:

The project capstone solves a fundamental problem that I face at work with file transferring. 

Working in a startup, We use free chatting apps to remotely communicate with my colleagues. However most of these apps are free, and we cannot transfer files exceeding a particular limit. My aim was to eliminate this issue through my project. 

My colleagues can login and share files. Also, keeping track of the files is simpler. I can simply go to the profile of my colleagues and see all the files they have uploaded over any period of time.

Searching files is even easier by a simple search bar. 

And finally, the files remain unmodified when uploaded and downloaded over the application. 

------- content -------


Each app in the project have their own specific functionalities. 

-- users --

This app helps manage users 
To register users, and manage their profile, and update them when necessary

-- blog -- 

This app is used to manage the overall file management, create posts, view posts, update/delete posts, search posts, download files

-- media --

This acts like a container storage for storing files and profile pictures at this location.

-------- run ---------

Make sure the above modules are installed. 
Then run the python manage.py run server to run the project

