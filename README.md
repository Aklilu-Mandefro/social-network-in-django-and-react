## ✍️ Social Network for Developers

This app is a Social Network For Developers. In this Project I have used Django and Django-Rest-Framework for Backend and React For Frontend.

## Frontend( React )

#### To install dependency

```
npm install
```

#### To start the server

```
npm start
```

#### For Production Build

```
npm run build
```

- I have used proxy `http://127.0.0.1` for axios in package.json
- You can set axios.defaults.baseURL = `https://api.example.com` Globally

## Backend( Django )

#### Installing

open terminal and type

```
git clone https://github.com/Aklilu-Mandefro/social-network-for-developers-in-django-and-react.git
```

or you can download using the url below

```
https://github.com/Aklilu-Mandefro/social-network-for-developers-in-django-and-react.git
```

#### Requirements

To install requirements type

```
pip install -r requirements.txt
```

`To use Github api put your credentials in settings.py`

```
GIT_CLIENT_ID = 'your github client id'
GIT_CLIENT_SECRET = 'your github client secret'
```

To migrate the database open terminal in project directory and type

```
python manage.py makemigrations
python manage.py migrate
```

To run the program in local server use the following command

```
python manage.py runserver
```

Server will be available at `http://127.0.0.1:8000` in your browser

Don't Forget to whitelist your host origin using `django-cors-header` when using in production<br>
[See Documentation](https://pypi.org/project/django-cors-headers/)

## Project Report

In case if you want the documentation of the project, kindly [request here](https://github.com/Aklilu-Mandefro/social-network-for-developers-in-django-and-react/issues)

## Preview of The Project

<img src="https://i.imgur.com/wlFYtXD.png" alt="Developers' social network"/>

<img src="https://i.imgur.com/1IWXvry.png" alt="Developers' social network"/>

<img src="https://i.imgur.com/qqOSKpQ.png" alt="Developers' social network"/>

## Contribute to this project

<blockquote>

Thank you for browsing this repo. Any contributions you make are **greatly
appreciated**.

If you have a suggestion that would make this better, please fork the repo and
create a pull request. You can also simply open an issue with the tag
"enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request

</blockquote>

### Please give this repo a ⭐ if you found it helpful.
