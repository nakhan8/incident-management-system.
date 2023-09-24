# Incident-Management-System
An incident management system is a structured approach to handling and resolving unexpected events.
The Front for the incident management system is in html and css. Backend is in Python.
in and need to create the following

To Run the project:<br>
py manage.py<br>
Run the server on http://127.0.0.1:8000/<br>

Requirements:<br>
Python 3.x<br>
Flask web framework<br>
py -m pip install -U Flask<br>
SQL database (such as MySQL or PostgreSQL)<br>
pip install django-rest-passwordreset<br>


# The Key functionalities:
<li> login page </li>
<li> register page </li> <br>
i. User Name<br>
ii. User Email ID<br>
iii. User Phone Number<br>
iv. User Address, Pin code<br>
v. City and Country. <br>
<li> Forgot Password  </li> <br>
<li> Create Incident  </li> <br>
 The incidents include the following details- <br>
<ol> a.Reporter name (Name of the user who logs in and creates the incident)<br>
b. Incident details (text field) Should be editable<br>
c.Incident Reported date and time<br>
d. Priority (Dropdown with values High, Medium, Low)
Should be editable<br>
e.Incident status (Open, In progress, Closed) Should be editable </ol><br>

## Limitations
i. A User should be allowed to view and edit the incidents created by
them only.<br>
ii. No user should be able to view other users’ incidents.<br>
iii. Any Incident which has the state = closed, should not be editable.<br>
iv. There should be a provision to search the incident using the Incident ID.# Incident-Management-System<br>
