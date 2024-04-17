
# Student Wellness Nexus

---
## Functions
### Admin
- Signup their account. Then Login (No approval Required).
- Can register/view/approve/reject/delete counsellor (approve those counsellor who applied in their Wellness Nexus).
- Can admit/view/approve/reject/attend to student (attend to student when treatment is done).
- Can view/book/approve Appointment (approve those appointments which is requested by student).

### Counsellor
- Apply in Wellness Nexus. Then Login (Approval required by Wellness Nexus admin, Then only counsellor can login).
- Can only view their student details (complaints/ issues, name, email) assigned to that counsellor by admin.
- Can view their attend tod(by admin) student list.
- Can view their Appointments, booked by admin.
- Can delete their Appointment, when wellness counsellor attended their appointment.

### Student
- Create account for admin in Wellness Nexus. Then Login (Approval required by Wellness Nexus admin, Then only student can login).
- Can view assigned counsellor's details like ( department, email, name).
- Can view their booked appointment status (pending/confirmed by admin).
- Can book appointments.(approval required by admin)

---

## HOW TO RUN THIS PROJECT
- Install Python(3.9.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

```
## Drawbacks/LoopHoles
- Any one can be Admin. There is no Approval required for admin account. So you can disable admin signup process and use any logic like creating superuser.
- There should be at least one counsellor in Wellness Nexus before admitting student. So first add counsellor.
- On update page of counsellor/student you must have to update password.


