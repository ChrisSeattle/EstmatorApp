# Dependencies

1. dj-database-url==0.3.0   => 0.5.0
    - help configure the DB connection
1. Django==1.8.3  => 2.1.1
    - Web framework!
    - REQUIRES PYTHON3.4 +
1. django-bootstrap3==6.1.0   => 11.0.0
    - CSS Bootstrap for Django
1. django-grappelli==2.7.1  => 2.11.1
    - Only release that supports django2.0+
    - Replacement for the built-in Admin console
1. django-localflavor==1.1  => 2.1 
    - location and currency data standards
1. django-registration-redux==1.2  => 2.4
    - Registration process - no support for Django2.1 (TBD)
1. djangorestframework==3.2.0  => 3.8.0  
    - API Framework for building RESTful endpoints in Django
1. factory-boy==2.5.2  => 2.11.1
    - Does not support Python3.7 or Django2.1
    - Provides fake data for testing!
1. fake-factory==0.5.2  => DEPRECATED!
    - Is now Faker (scott believes Faker is installed with Factory-boy...?)
1. Pillow==2.9.0  => 5.2.0
    - Imaging library for supporting image file management in Python
1. psycopg2==2.6.1  => 2.7.5
    - Postgres adapter for python 
    - We know from recent experience that we need psycopg2-binary
1. requests==2.7.0 =>  2.19.1
   - Send HTTP requests from within out code
1. selenium==2.47.1  =>  3.14.1 
    - Headless browser drivers for scripted e2e testing
1. splinter==0.7.3  => 0.9.0
    - Testing tool for finding elements, events, etc 
1. wheel==0.24.0  => 0.31.1
    - packaging and distribution

