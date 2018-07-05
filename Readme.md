# Django Polls app
Polls is a simple Django app to conduct Web-based polls. For each
question, visitors can choose between a fixed number of answers.

A simple Django poll app consist of two parts:

- A public site that lets people view polls and vote in them.
-  An admin site that lets you add, change, and delete polls.

# Initial Setup

  - Add "polls" to your INSTALLED_APPS setting like this::
    INSTALLED_APPS = [
...
        'polls',
         ]
  - Include the polls URLconf in your project urls.py like this:
    path('polls/', include('polls.urls')),
  - Run `python manage.py migrate` to create the polls models.
  - Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).
  - Visit http://127.0.0.1:8000/polls/ to participate in the poll.

### Installation
```sh
$ pip install django 
```
### Requirements
Django 1.10+, Python 2.7, 3.4+
