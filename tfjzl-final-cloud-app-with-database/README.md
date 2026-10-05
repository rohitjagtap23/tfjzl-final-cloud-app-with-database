# IBM Final Project - Online Course Assessment

This project is prepared for the IBM Skills Network final project:
**Add a New Assessment Feature to an Online Course Application**.

## GitHub upload

Create a **public** GitHub repository named:

`tfjzl-final-cloud-app-with-database`

Upload the contents of this folder so that `manage.py` is at the repository root.

The five assessment files are:

- `onlinecourse/models.py`
- `onlinecourse/admin.py`
- `onlinecourse/templates/onlinecourse/course_details_bootstrap.html`
- `onlinecourse/views.py`
- `onlinecourse/urls.py`

## Local setup

```bash
pip install -r requirements.txt
python manage.py makemigrations onlinecourse
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open `/admin/` for the Django admin site.

For the assignment, submit the public GitHub file URLs after verifying that each file opens without a 404/error.
