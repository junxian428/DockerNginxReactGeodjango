# DockerNginxReactGeodjango

Step 1: First Create Virtual Environment

Windows:

python3 -m venv tutorial-env

tutorial-env\Scripts\activate.bat

Unix or MacOS:

source tutorial-env/bin/activate

Step 2: 

pip install django==3.1.5 djangorestframework==3.12.2 djangorestframework-gis==0.17 django-leaflet==0.27.1

Reference:

https://youtu.be/zQx4IT70w4g

Step 3:

pip freeze > requirements.txt

Step 4 Start Project:

django-admin.py startproject schools_api .

Issue:

no module named django.core

Solution:

(Geodjango-env) C:\Users\user\Desktop\forbes\GeoDjango\Geodjango-env>python C:\Users\user\Desktop\forbes\GeoDjango\Geodjango-env\Scripts\django-admin.py startproject schools_api .
