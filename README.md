# Django Models

Django Models task for Zuri Training

# Task Guidelines

Create a new Django project
Create a new application called blog and add it to the main_projects INSTALLED_APPS.

Create a new model in the blog app called Post. It should have the following fields:
Title : A string of maxlength 200, use Django’s models.CharField

Text : Any amount of text, use Django’s TextField

Author : A Foreign Key to the current user model. Make use of Django’s get_user_model function.

Created_date : A date-time column, use Django’s models.DateTimeField.

Published_date : A date-time column, use Django’s models.DateTimeField.

Create migrations for your new model using the makemigrations Django command.

Run all migrations using the migrate Django command.
