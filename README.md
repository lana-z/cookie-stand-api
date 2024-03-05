# Cookie Stank API

This is the Cookie Stand API Vercel Deployment Lab, course 401 class 41 on March 4, 2024 using the api-quick-start template mentioned below.

### Author: Lana Z

### Links and Resources

- [Deployed site:](https://github.com/lana-z/cookie-stand-api) https://github.com/lana-z/cookie-stand-api 
- quick start template and class review by JB, Class 41



#### api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

#### Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `things` folder to the app name of your choice
- Search through entire code base for `Thing`,`Things` and `things` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update ThingModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Optional: Update `api_tester.py`
