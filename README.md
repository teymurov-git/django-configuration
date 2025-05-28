# Django Configuration

1. Virtual Environment yaradırıq 
    # (python -m venv .venv)

2. Virtual Environment aktivləşdiririk.
    # (.venv\Scripts\activate)

3. Django vəya hər hansı kitabxananı yükləyirik.
    # (pip install Django)

4. Onu requirements.txt faylına yazırıq.
    # (pip freeze > requirements.txt)

5. Proyekti yaradırıq və ad qoyuruq.
    # (django-admin startproject config .)

6. Serveri işə salıb, yoxlayırıq.
    # (python manage.py runserver)

7. Server işləməyəcək çünki migrate edilməyən fayllar mövcuddur.
    # (python manage.py migrate)

8. Serveri yenidən işə salıb, yoxlayırıq.
    # (python manage.py runserver)

9. Django administrasiyasına giriş etmək üçün istifadəçi yaradırıq.
    # (python manage.py createsuperuser)

10. Serveri yenidən işə salıb, yoxlayırıq.
    # (python manage.py runserver)

11. Tətbiqlər (app) yaradırıq və hər birinin içərisində "templates" qovluğu yaradırıq.
    # (python manage.py core)
    # (python manage.py account)
    # (python manage.py product)
    # (python manage.py blog)

12. settings.py faylına tətbiqləri əlavə edirik.

-------------------------------------------------------------------------------


# Django Configuration

1. Create a Virtual Environment
# (python -m venv .venv)

2. Activate the Virtual Environment.
# (.venv\Scripts\activate)

3. Install Django or any library.
# (pip install Django)

4. Write it to the requirements.txt file.
# (pip freeze > requirements.txt)

5. Create the project and give it a name.
# (django-admin startproject config .)

6. Start the server and check.
# (python manage.py runserver)

7. The server will not work because there are files that cannot be migrated.
# (python manage.py migrate)

8. Restart the server and check.
# (python manage.py runserver)

9. Create a user to access the Django administration.
# (python manage.py createsuperuser)

10. Restart the server and check.
# (python manage.py runserver)

11. We create applications (app) and create a "templates" folder inside each one.
# (python manage.py core)
# (python manage.py account)
# (python manage.py product)
# (python manage.py blog)

12.  Add apps to settings.py.
