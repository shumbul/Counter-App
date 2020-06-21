# Counter-App
This is a mini project usng Django and MYSql. It invoves basic implementation of databases.

###   Requirements 
1.Python (version >= 3.5)<br>
2.Django

### Running instructions <br>
1.Clone/Download the repository <br>

2.Change directories into your project file .<br>

3.Set up a virtual environment with the steps mentioned in the blog : https://tutorial.djangogirls.org/en/django_installation/<br>

4.Create a database by name "counterapp" (name can differ).<br>

5.In counterapp/settings.py, update your database username and password. <br>

6.In the terminal, Run "python manage.py makemigrations"<br>

7.Run "python manage.py migrate"<br>

8.Run "python manage.py runserver". You should get a message like this:<br>
```
(venv) C:\Users\Shumbul\PycharmProjects\counter>py manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
June 21, 2020 - 17:03:07
Django version 3.0.7, using settings 'counter.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```

9.Go to "localhost:PORT NO. " (Port no. is the port server runs on) where the development server starts.<br>
