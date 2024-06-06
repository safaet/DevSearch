# DevSearch


# Features
- Share Projects
- Message other developers
- Rate other work
- Search other developers

# Tech Stack
- Django
- Postgres
- Django REST Framework

# Home Page
<img src='./resources/images/Devsearch Home.jpg'>


# Projects Page
<img src="./resources/images/DevSearch Projects.jpg">


# Profile Page
<img src="./resources/images/Devsearch Profile.jpg">


# User Inbox
<img src="./resources/images/Devsearch Inbox.jpg">

# Setup

Update the System
```bash
sudo apt-get update
```
To get this repository, run the following command inside your git enabled terminal
```bash
git clone https://github.com/safaet/DevSearch.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Download django using pip
```bash
sudo apt install python3-pip -y
```
```bash
pip install django
```
Install all Dependencies
```bash
pip install requirements.txt
```
Once you have downloaded django, go to the cloned repository directory and run the following command

```bash
python3 manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
python3 manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
python3 manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
python3 manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/ for the App.

Cheers and Happy Coding 