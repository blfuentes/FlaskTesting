https://flask.palletsprojects.com/en/1.1.x/quickstart/

# Create an environment

Create a project folder and a venv folder within:

> mkdir myproject
>
> cd myproject
>
> python3 -m venv venv


# Activate the environment

Before you work on your project, activate the corresponding environment:

> venv\Scripts\activate

# Install Flask

Within the activated environment, use the following command to install Flask:

> pip install Flask


# Run Application

PowerShell:

> C:\path\to\app> $env:FLASK_APP = "hello.py"
>
> python -m flask run

# Debug Mode

> C:\path\to\app> $env:FLASK_ENV="development"
>
> flask run
