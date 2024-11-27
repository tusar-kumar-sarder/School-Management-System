# New Django project setup and run command 

py -m venv env                    # Set up a virtual environment 
../env/Scripts/activate             # For activate virtual environment 
pip install Django                 # Install django
django-admin startproject School_Management_System    # Create a new project
cd School_Management_System        # Navigate to the project directory 
py manage.py runserver  	         # Run the server
django-admin startapp student_app  # Create a new app


# To generate a file requirements.txt  for dependencies  
1. pip freeze > requirements.txt
# Install dependencies from requirements.txt
3. pip install -r requirements.txt


 # Git  Command 

 1.git inin 
 2.git add .
 3.git commit -m "comment"
 4.git remote add origin (repository-URL from github)
 5.git push origin master
