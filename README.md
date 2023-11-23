# Ex-04-Django-Models
# NAME : R.SUBHASHRI
# REFERENCE NUMBER : 23012776
# DEPARTMENT : AIDS
# AIM:
To create django model
# DESIGN PROCEDURE
Django models
step 1: Create django project and app using the following commands django-admin startproject
mymodels python manage.py startapp myApp


step 2: create a user_profile models in model.py
add the models in the admin interface using the code admin.py
write the function based view to render the data from the models to the template in views.py
![WhatsApp Image 2023-11-23 at 09 46 39_a0274dd3](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/408228df-c26a-44ed-b35f-aca0ebfeb0a1)
![WhatsApp Image 2023-11-23 at 09 46 39_849e1bdd](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/d0ac9ffe-a3df-43b4-89e5-c653a167d9ba)
set up the url path for the templates using urls.py
![Screenshot 2023-11-23 105106](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/9b50e129-7adb-4114-9d21-d12311564be9)
in settings.py file add the appcreated

step 3: Now do the migrations process to initiate and save the models
python manage.py makemigrations python manage.py migrate create a template as user_profile.html
![WhatsApp Image 2023-11-23 at 09 46 40_96a00b61](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/18f35533-20e2-4b68-8d1c-71f9321d96c0)

step4: Run the program using the following command
python manage.py runserver 8000 in the admin page you can view the models created and in the
![WhatsApp Image 2023-11-23 at 09 46 40_bc4704bc](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/e6a5ad38-56a4-4dab-95b4-b51158ea76c4)
user_profile template page you can see the profile page of the user
![WhatsApp Image 2023-11-23 at 09 46 40_c55a1b99](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/95f3a913-e39b-4e52-94c6-8780cf5c6491)

# output
![image](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/5eb11586-245a-432e-b558-802f58bf0253)
![image](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/6ee296f8-b72f-4f95-95bc-0f204f6023ce)
![image](https://github.com/SubhashriRavichandran10/ODD2023-WT-Ex-04-Django-Models/assets/145743413/cf0fc27c-de4a-48be-829b-ae583376aab2)
