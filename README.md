# flask_login
A simple login page using Flask
#This project has following pre-requsites :
	
	1.Needs Flask Microframework preinstalled (use pip install Flask in terminal/command prompt)
	2.Needs Python version>3.2
	3.Needs SQLalchemy preinstalled ( use  pip install Flask-SqlAlchemy in terminal/command prompt)

	
#File structure of the project
|flask_kage
			|static
					|style.css
			|templates
					|login.html
			|tabledef.py
			|sql_tabler.py
			|app.py
			|readme.txt
			
#app.py :
		app.py is the main program source code . You need to run this to start the local server
		(server is a development server as Flask is a microframework and needs WSGI server for production purposes).
		All the libraries are imported and templates and static files are linked through route decorator.
#templates:
			Templates directory contains all the changing and frequents edited files such as all the html
			templates and other files.
#static:
		Static directory contains all  the non changing files such as css and javascripts.
#tabledef.py:
			This file will create the database structure.
			Inside the directory you will find a file called tutorial.db.
#sql_tabler.py:
				This will put dummy data into your database.
				
#After executing the following code in your terminal/cmd
	
	$python app.py

The local server will start on localhost port 5000 aka '127.0.0.1:5000.
