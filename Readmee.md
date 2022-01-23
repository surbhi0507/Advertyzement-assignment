### How to run the application on your local system?

Step 1: Clone the repository!
```bash
https://github.com/surbhi0507/assignment1.git
```
Step 2: Make sure all the requirements are installed in a virtual environment using the terminal

The packages needed to run this app are listed in requirements.txt
```bash
pip install -r requirements.txt
```
Step 3: Type the following in the terminal for the database which contains the data on which queries will be executed.
```bash
python data_insertion.py
```
Step 4: Since this is a Flask application run 
```bash
set FLASK_APP = app.py
```
Step 5: To run the application on the local machine type 
```bash
python app.py
```
Step 6: Visit the link provided in the terminal and go to 
```bash
http://127.0.0.1:5000/
```
Step 7: The application supports GraphQL calls at 
```bash
http://127.0.0.1:5000/gql
```
