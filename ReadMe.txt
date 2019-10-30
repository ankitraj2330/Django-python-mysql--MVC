***************************Please Read ME**********************************

************contains steps to compile, build, and install this application****************

1. Install Python from https://www.python.org/downloads/ 
2. Add "Python 3.6 to PATH" under Environment variables. https://www.architectryan.com/2018/03/17/add-to-the-path-on-windows-10/
3. Install Django using command prompt: https://poweruphosting.com/blog/install-django/#win 
Open Administrator command prompt
Run
    >>pip install Django==2.2.6
    >>python -m django --version (command to check version after installation)

4. Make a new directory.
Run
   >>mkdir newdir
5. Copy the downloaded files from elearning(named source_code) to this new directory. source_code folder contains all the code and dependencies of the project.
6. Install the editor - Visual Studio Code https://code.visualstudio.com/
7. In Visual Stuio Code go to File->Open Folder and select the source_code folder.
8. Install MySQL server on the machine and import database(it is in database named folder in the zip file uploaded to elearning).
9. Run the server
Launch Admin Command prompt
run
   >> python manage.py migrate --fake
   >> python manage.py runserver
10. Launch any browser and access localhost:3306


   
