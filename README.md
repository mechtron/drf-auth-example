# drf-vue-social-oauth2

By Corey Gale (corey@gumgum.com)

## API

### Setup

1. Change into the API base directory: `cd api`
1. Create a virtualenv: `python3 -m venv venv && source venv/bin/activate`
1. Install Python dependencies: `pip3 install -r requirements.txt`
1. Migrate the database: `python3 manage.py migrate`
1. Create a super user: `python3 manage.py createsuperuser --email admin@example.com --username admin`
1. Start the API: `python3 manage.py runserver`

### API usage

##### User list

    curl -H 'Accept: application/json; indent=4' -u admin:password123 http://127.0.0.1:8000/users/

##### Group list

    curl -H 'Accept: application/json; indent=4' -u admin:password123 http://127.0.0.1:8000/groups/
