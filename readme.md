
# Soicial Mongard
## Project Overview
This project is a Django-based social media platform named __social_moongard__ based on course [django-social](https://www.mongard.ir/courses/django-social/). This project allows users to register, login, logout, view profiles, reset passwords, follow/unfollow other users, edit their own profiles, and view, create, delete, update posts and like them or add comments.

## Project Structure
The project consists of the following key components:

__Home App__: Handles the display of posts, including searching, creating, updating, and deleting posts, as well as managing comments and likes on posts..\
__Accounts App__: Handles user authentication, profile management, and password reset functionality.

## Setup Instructions
* Clone the project repository.
* Install the required dependencies using the package manager [pip](https://pip.pypa.io/en/stable/).
```bash
pip install -r requirements.txt
```
* Set up the database configuration in `social_moongard/settings.py`.
* Run migrations and create a superuser using `python manage.py`.
```bash
python manage.py makemigraions
python manage.py migrate
python manage.py createsuperuser
```
* Create a `.env` file and fill in the variables acording to the `dotenv.txt`.

## Usage
* Start the development server.
```bash
python manage.py runserver.
```
* Access the admin interface at `http://localhost:8000/admin/` to manage users and profiles.
* Register new users, login, view profiles, reset passwords, follow/unfollow users, and edit profiles through the provided views.
