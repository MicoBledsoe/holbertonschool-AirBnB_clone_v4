# ![logo](https://user-images.githubusercontent.com/108279441/220420558-12b71945-3e02-4adf-b989-5f8fa1b4c683.png)

# AirBnB Clone V4 - Holberton School

## Overview

This repository, a continuation of the AirBnB clone project, represents version 4 and includes advanced features integrating more dynamic front-end functionalities with a robust Flask-driven RESTful API backend. This version builds upon the previous work by incorporating additional user interactions and data manipulations, made possible through AJAX and updated Flask routing mechanisms.

## Technical Stack

- **Backend Programming**: Python 3, Flask
- **API**: RESTful API practices
- **Frontend**: HTML5, CSS3, JavaScript, AJAX
- **Database**: MySQL
- **Testing**: Unittest for Python
- **Deployment**: Scripts for setting up web and database servers
- **Version Control**: Git, GitHub

## Key Components

### API
The `api` directory contains the Flask application that exposes the RESTful API, allowing for CRUD operations on objects stored in a MySQL database. It includes error handling and route management for different models like User, Place, and State.

### Models
The `models` directory has been updated with more complex class methods and relationships between models to handle more intricate queries and operations that support web interactions.

### Dynamic Web Frontend
The `web_dynamic` directory introduces JavaScript and AJAX to handle asynchronous requests, making the user interface more interactive and responsive.

### Flask Web Framework
The `web_flask` directory contains routes and view functions for serving HTML content that interacts seamlessly with the Flask API, demonstrating a multi-tiered application structure.

### Testing
The `tests` directory includes updated test cases for new features and API endpoints, ensuring that all components work correctly together.

### Deployment
Scripts like `1-pack_web_static.py`, `2-do_deploy_web_static.py`, and `3-deploy_web_static.py` automate the deployment of static and dynamic content to web servers, illustrating best practices in software deployment.

### Configuration
The `.gitignore` and `.env` files manage environment variables and ensure that sensitive or unnecessary files are not included in version control.

## Installation

Clone the repository to your local machine:

#```bash
$ git clone https://github.com/MicoBledsoe/holbertonschool-AirBnB_clone_v4.git
$ cd holbertonschool-AirBnB_clone_v4

Set up the database:
$ mysql -u root -p < setup_mysql_dev.sql

Running the Application
Start the Flask server from the api directory:
$ FLASK_APP=api/v1/app.py FLASK_ENV=development flask run

Navigate to the web_dynamic directory to view dynamic web pages:
$ cd web_dynamic
$ python3 -m http.server 5000

Open your browser and go to http://localhost:5000 to see the site in action.


### Part 4: Additional Information
#```markdown
## Contributors

This project is part of the curriculum of Holberton School and has been a collaborative effort. This version includes contributions from:
- Mico Bledsoe ([GitHub](https://github.com/MicoBledsoe))
- Teylor Chapman ([GitHub](https://github.com/teylorchapman))

## Acknowledgments

Thanks to the contributors of previous versions and the open-source community for providing the tools and libraries used in this project.
Alexa Orrico - [Github](https://github.com/alexaorrico) / [Twitter](https://twitter.com/alexa_orrico)  
Jennifer Huang - [Github](https://github.com/jhuang10123) / [Twitter](https://twitter.com/earthtojhuang)  
Jhoan Zamora - [Github](https://github.com/jzamora5) / [Twitter](https://twitter.com/JhoanZamora10)  
David Ovalle - [Github](https://github.com/Nukemenonai) / [Twitter](https://twitter.com/disartDave)

## License

This project is released under the Public Domain.
