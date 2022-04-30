How to install and run Level Field from source

Step 1: 
Install Django. See https://docs.djangoproject.com/en/1.7/intro/install/ for details

Step 2: 
unzip LevelFiel.zip 

Step 3: 
(If not on a Windows platform) Templates in /LevelField/resume/templates/resume/ refers to the base file using Windows reference (i.e. '\' instead of '/'). Bad, I know. You'll need to change them back to '/' (in an ideal world, I would have notice that early enough in this weekend to be more clever about this...)

Step 4: 
Go into /LevelField/ and run:
python manage.py runserver 

Step 5: 
LevelField should be available on 127.0.0.1/

