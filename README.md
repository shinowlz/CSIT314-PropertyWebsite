
# About The Project

MillionEstate is an Property listing application build with Python Django Framework.In this Project I added Search and filter functionality in Home and Propertys page. We provide Login & Signup system for user. Integrated Google api for Social Authentication. User can add property, edit property, delete property and update profile, In Admin panel admin can Add,Edit & Delete the Property. admin can add Property type, Property For, & location. CRUD Operations are used in this Project.
## 🗒️Installation setup

Python need to be installed

1. Clone the repository: ```https://github.com/shinowlz/CSIT314-PropertyWebsite```.

2. Move to base directory: ```cd CSIT314-PropertyWebsite```.

3. Create virtual environment: ```python -m venv env```.

4. Activate enveronment with: ```env\Scripts\activate``` on windows, or ```source env/bin/activate``` on Mac and Linux.

5. Install required packages to run the project: ```pip install -r requirements.txt```.

6. Make migrations with: ```python manage.py makemigrations```.

7. Make migrate with: ```python manage.py migrate```.

8. Create super user: ```python manage.py createsuperuser ```.
 _GitBash users may have to run this to create a super user - `winpty python manage.py createsuperuser`_

11. Run server ```python manage.py runserver```

12. Login to admin panel - (`http://127.0.0.1:8000/superadmin/`)

13. Add Property Type, Property For, Country, State, City.

14. To Config google auth api you need Client id & Secret Add them in: (`http://127.0.0.1:8000/admin/`) Social Accounts



    
## ✨Features

- Login 
- Registration
- Google authentication
- Property Listing (Add, Edit, Delete)
- Search and Filter
- Pagination

