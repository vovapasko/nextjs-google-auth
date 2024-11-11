# Django REST-based Authentication with Auth.js

The repository is split into two directories:

1. `backend` -- the backend part of the project (Django, DRF, dj-rest-auth)
2. `frontend` -- the frontend part of the project (Next.js, Auth.js)

> If you're interested only in Django REST framework authentication take a look at [this repo](https://github.com/duplxey/django-rest-allauth).

## Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/django-rest-authjs/).

## Want to use this project?

Go ahead and fork/clone the repository and then setup backend and frontend individually.

### Backend
    
1. Your authentication API is now accessible at [http://localhost:8080/oauth/google/](http://localhost:8080/oauth/google/).

### Frontend

1. Change directory to `frontend`.

1. Install the dependencies:

    ```sh
    $ npm install
    ```
	
1. Run the development server:

    ```sh
    $ npx next dev
    ```
	
1. Navigate to [http://localhost:3000/](http://localhost:3000/) in your favorite web browser.
