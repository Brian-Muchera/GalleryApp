# Gallery

## Author

> Muchera-Brian

# Description

This is a Django application for personal gallery that allows a user to upload images for other to see and be able to to share by coping the image link.

# Live Link
[MucheraBrian] https://briangallery2.herokuapp.com



###### Categories

- Entertainment
- Nature
- Food

## User Story  
  
* View different photos that interest them  
* Click a single image to expand it and view the details of that photo  
* Search for different categories   
* Copy a link to the photo to share with my friends.  
* View photos based on the location they were taken.

## Setup and Installation

To get the project .......

##### Cloning the repository:

```bash
https://github.com/Brian-Muchera/GalleryApp.git
```

##### Navigate into the folder and install requirements

```bash
cd Galleria pip install -r requirements.txt
```

##### Install and activate Virtual

```bash
- pip3 install virtualenv
```

```bash
- . env/bin/activate
```

##### Create Virtual

```bash
virtualenv env
```

##### Install Dependencies

```bash
pip install -r requirements.txt
```

##### Setup Database

SetUp your database User,Password, Host then make migrate

```bash
python manage.py makemigrations photohub
```

Now Migrate

```bash
python manage.py migrate
```

##### Run the application

```bash
python manage.py runserver
```

##### Testing the application

```bash
python manage.py test
```

Open the application on your browser `127.0.0.1:8000`.

## Technology used

- [Python3.8](https://www.python.org/)
- [Django 3.0.6](https://docs.djangoproject.com/en/2.2/)
- [Heroku](https://heroku.com)

## Known Bugs

- There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information

If you have any question or contributions, please email me at [mucherabrian2@gmail.com]

## License

- [![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](https://github.com/default-007/Galleria/blob/master/LICENSE)
- Copyright (c) 2020 **Brian Muchera**
