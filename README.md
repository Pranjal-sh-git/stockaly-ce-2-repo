# STOCKALY 
Stockaly is a powerful Inventory Management System built using Django, designed to simplify stock tracking and management. It combines Python for backend logic, HTML and CSS for a clean and responsive user interface, and JavaScript for interactive features. Stockaly helps businesses efficiently manage products, monitor inventory levels, and streamline operations with an intuitive dashboard and real-time updates.




## Deployment

To deploy this project run

1. Create a virtual environment in your vs code by hitting the command in the terminal
```bash
  python -m venv my-env
```
2. Now activate the virtual environment
```bash
  .\my-env\bin\activate
```
3. Now install the following command in the activated virtual environment
```bash
  pip install django
```
4. Now run the following 2 commands in terminal.
```bash
  pip manage.py makemigrations
  ```
```bash
  pip manage.py migrate
  ```  

5. Run the project file using 
```bash
  python manage.py runserver
```
6. You are all set , also you can check the requirements.txt file for the essential requirements for the project.
