# Django Crash Course
Very simple Django blog app for crash course
cloned from bradtraversy, with thanks

Sources for the very helpful video 
https://www.youtube.com/watch?v=D6esTdOLXh4&t=1s

Some little changes...
add .gitignore, that leaves out .vscode, and a new file djangoproject/settings_secret.py
which separates the SecretKey and Database configuration from commiting to Github

Urls
 url(r'^$', include('posts.urls')),
to
 url(r'^\Z', include('posts.urls')),

March 2019

