# Ex01 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a Car Inventory Database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
MODELS.PY
from django.db import models
from django.contrib import admin
class studentdb(models.Model):
    student_name = models.CharField(max_length=25)
    student_id = models.IntegerField()
    student_email = models.EmailField()
    join_date = models.DateField()

class studentdbAdmin(admin.ModelAdmin):
    list_display = ('student_name','student_id','student_email','join_date')
ADMIN.PY
from django.contrib import admin
from.models import studentdb, studentdbAdmin
admin.site.register(studentdb, studentdbAdmin)

### STEP 4:
Execute Django admin and create details for 5 Car 

## PROGRAM
Include your program
## OUTPUT
<img width="1560" height="1067" alt="Screenshot 2025-11-29 121612" src="https://github.com/user-attachments/assets/4de803aa-2d2e-4a13-a562-7dc79313d2b6" />
<img width="1916" height="1075" alt="Screenshot 2025-11-29 121545" src="https://github.com/user-attachments/assets/80f21a97-3ebe-4acd-a726-0ff651057821" />



## RESULT
Thus the program for creating car inventory database database using ORM hass been executed successfully
