This application needs to run simultaneously for backend and frontend.  

1. `cd To-do-App`  

2. On one shell, activate your virtual environment and type  
`python manage.py migrate`  
`python manage.py runserver`: Django runs at `http://localhost:8000`  
To check RestAPI migration table goto: `http://localhost:8000/api`  

3. On another shell, type:  
`cd frontend`  
`npm install`  
`npm start`: ReactJS runs at `localhost:3000`  

###### Note to self: `localhost:8000/admin` login: rajitaroy password: 123

#### Application runs at `http://localhost:3000`
                                                         
