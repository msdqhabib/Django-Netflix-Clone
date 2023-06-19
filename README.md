# Django-Netflix-Clone

👋 This is a Netflix clone built using Django, incorporating features like authentication, user profiles, movie filtration by age limit, and the ability to watch movies online. The project utilizes Django's built-in authentication system, Django All-Auth, to handle user registration, login, and profile creation.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication: Users can register, login, and manage their profiles.
- Profile creation: Users can create multiple profiles for different family members.
- Movie filtration: Movies are categorized based on age limits, ensuring appropriate content for different audiences.
- Movie playback: Users can watch movies directly on the website.
- Support for seasons and movies: The project handles both individual movies and TV show seasons.

## Installation

To get started with Django-Netflix-Clone, you need to have Python and pip installed on your system. Then, follow these steps:

1. Clone this repository:
```python
git clone https://github.com/msdqhabib/Django-Netflix-Clone.git
```
2. Navigate to the project directory:
```python
cd django_netflix_clone
```
3. Install the required packages:
```python
pip install -r requirements.txt
```
4. Apply the database migrations:
```python
python manage.py migrate
```
5. Create a superuser account:
```python
python manage.py createsuperuser
```
6. Run the development server:
```python
python manage.py runserver
```

The application will now be available at `http://localhost:8000`.

## Usage

To use Django-Netflix-Clone, open your web browser and go to `http://localhost:8000`. From there, you can sign up or log in to your account, create new profiles, and search for movies and seasons.

## Contributing

If you would like to contribute to Django-Netflix-Clone, you can follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Write your code and add tests if possible.
4. Submit a pull request.

## License

Django-Netflix-Clone is licensed under the MIT License. See [LICENSE](LICENSE) for more information.







