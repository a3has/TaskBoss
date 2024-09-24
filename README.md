# CMPE_195B_TaskBoss_Web

### Table of Contents
- [Introduction](#introduction)
- [Collaborators](#collaborators)
- [Project Setup](#project-setup)
- [How To Use](#how-to-use)
- [Packages](#packages)

## Introduction
// FILL HERE   

## Collaborators 
- Sammy Cuaderno (@Scuaderno1991)
- Abdulkader Hasbini (@a3has)
- // FILL HERE
- // FILL HERE

## Project Setup
1. Clone this repository on your own local machine
```bash
# clone github project
git clone git@github.com:a3has/TaskBoss.git

# navigate into project directory
cd TaskBoss/notesapp
```
2. Create and activate a virtual environment in the `/notesapp` directory
```bash
# in the /TaskBoss/notesapp directory
python3 -m venv venv
source venv/bin/activate
```
3. Install all necessary requirements 
```bash
# install from requirements.txt file
pip3 install -r requirements.txt
```
4. Downgrade Werkzeug to working version
```bash
pip3 install werkzeug==2.2.2
```
5. Start the flask application
```bash
flask run
```

## How To Use
### Login
1. You will initially be prompted to login. Click the link to create an account.
2. Create an account. You will then be successfully logged in and redirected to the project /home route.

### FILL HERE
1. // FILL HERE

### Edit Profile
1. From the /home route, navigate to the /user directory using the `User Profile` button. 
2. Click the `edit` button underlined under the page header.
3. A form will show up allowing you to edit your username, email, and biography.
4. Edit which fields you wish to change, and click submit.
5. Your web page should now show the new profile changes that you set.


### Logout
1. From the /home route, click the `Logout` button. 
2. You will then be logged out, and redirected back to the /login route.


## Packages
Find a list of the packages we used for this application [here](https://github.com/a3has/team10App/blob/milestone2/notesapp/requirements.txt).
