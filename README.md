
CRUD_Flask is a basic web application built using the Flask framework in Python to demonstrate CRUD operations—Create, Read, Update, and Delete—on a data model. It serves as an introductory-level project for understanding how to build web apps with Flask, connect to a database, and deploy applications to the cloud.

The application allows users to perform standard database operations via a web interface, making it an ideal starting point for learning backend development and full-stack integration.

🧰 Technologies Used

Flask (Python): Lightweight web framework used to build the application.

HTML/CSS (Bootstrap): Frontend design and layout.

SQLite/MySQL: Backend relational database to store and manage records.

Jinja2 Templating Engine: For rendering dynamic content in HTML pages.

Heroku: Platform-as-a-Service (PaaS) used for cloud deployment.

Create: Add new entries through a form submission.

Read: View all records in a list/table format.

Update: Modify existing entries via editable forms.

Delete: Remove records from the database with a single click.

Routing: Clean URL routes handled with Flask’s @app.route decorators.

Error Handling: Basic exception and error handling to improve UX.


Deployment on Heroku

The Flask application is deployed on Heroku, making it accessible online from any device. The deployment process includes:

Creating a Procfile to define the app type.

Using gunicorn as the production WSGI server.

Setting up environment variables via Heroku dashboard.

Pushing the project repository to Heroku using Git.

Managing dependencies with requirements.txt.


Project Structure (Example)
CRUD_Flask/
│
├── app.py                # Main Flask app
├── templates/            # HTML templates (Jinja2)
│   ├── index.html
│   ├── edit.html
│   └── ...
├── static/               # CSS, JS, Images
│   └── style.css
├── models.py             # Database schema (if used separately)
├── requirements.txt      # Python dependencies
├── Procfile              # Heroku deployment instructions
└── README.md             # Project documentation



Learning Outcomes

By completing this project, you will learn how to:

Build dynamic web apps with Flask.

Connect and interact with a relational database.

Use templating for front-end rendering.

Perform CRUD operations in a web environment.

Deploy Python web applications to the cloud using Heroku.
