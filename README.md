# django-blog

A basic personal CRUD blog 

## Description

A simple blog application in Django with create, read, update and delete functionality for posts. Build followed the [Django Girls Tutorial](https://tutorial.djangogirls.org/en/) with added style customization. 

Thanks to [PythonAnywhere](https://pythonanywhere.com) for free hosting :)

## Getting Started

### Dependencies

Make sure you have installed Git and Python 3.7 on your system before proceeding.

### Installing

1. Download/Clone the code:
```
git clone https://github.com/ameybhavsar24/django-blog.git
cd django-blog
```

2. Create a virtual environment to install dependencies (recommended):
```
python3 -m venv env
source env/bin/activate
```
_These commands are focused on Bash users, you should be able to find equivalent commads for MacOS and Windows system easily._

3. Install the requirements
```
pip install -r requirements.txt
```

### Executing program

1. Start the application
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
The development server should have started on [127.0.0.1:8000](http://127.0.0.1:8000)

2. Create a super user
```
python manage.py createsuperuser
```

3. Login as super user at [127.0.0.1:8000/admin](http://127.0.0.1:8000/admin/).
4. Go to homepage at [127.0.0.1:8000](http://127.0.0.1:8000)

You should be able to add new posts and then edit or delete posts. All created posts will be seen on the homepage.

#### Screenshots
##### Homepage
![image](https://user-images.githubusercontent.com/65420449/139160947-4978e3fa-70b0-4809-8c82-dd2149950cd7.png)
##### Post view
![image](https://user-images.githubusercontent.com/65420449/139161069-0fea9b56-6c37-48c4-9531-88e7d48ca020.png)



## Contributers

Here is a list of users who already contributed to this repository:


<a href="https://github.com/ameybhavsar24/django-blog/graphs/contributors">
  <img
  src="https://contributors-img.web.app/image?repo=ameybhavsar24/django-blog"
  />
</a>

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

[Django Girls](https://tutorial.djangogirls.org/en/)
