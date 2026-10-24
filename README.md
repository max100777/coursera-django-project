# Online Course assessment project

This repository contains the Django OnlineCourse application and the final
assessment feature from the Coursera final project lab.

## Run locally

```powershell
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Open `/admin/` to create a course, lessons, questions, and choices. Enrolled
learners can open a course, start its exam, submit answers, and view the
graded result.

## Assignment evidence

| Requirement | File |
| --- | --- |
| Question, Choice, Submission models | `onlinecourse/models.py` |
| Admin imports, inlines, and admin classes | `onlinecourse/admin.py` |
| Course detail and exam form | `onlinecourse/templates/onlinecourse/course_detail_bootstrap.html` |
| Submission and result views | `onlinecourse/views.py` |
| Exam URL routes | `onlinecourse/urls.py` |
| Admin screenshot | `03-admin-site.png` |
| Successful result screenshot | `07-final.png` |
