Fancy Shop
Welcome to Fancy Shop, an online shopping platform built with Django. This platform offers a wide range of products for users to browse, add to their cart, and make purchases. The shop integrates with various technologies such as Stripe for payment processing, Postgres for the database, AWS for file storage, and Bootstrap for a responsive and visually appealing user interface.

Requirements
The project has been developed using the following libraries and technologies:

asgiref==3.7.2
certifi==2023.5.7
cffi==1.15.1
charset-normalizer==3.1.0
cryptography==41.0.1
defusedxml==0.7.1
dj-database-url==2.0.0
Django==3.2.3
django-allauth==0.54.0
django-crispy-forms==2.0
django-storages==1.13.2
gunicorn==20.1.0
idna==3.4
oauthlib==3.2.2
psycopg2==2.9.6
pycparser==2.21
PyJWT==2.7.0
python3-openid==3.2.0
pytz==2023.3
requests==2.31.0
requests-oauthlib==1.3.1
sqlparse==0.4.4
typing_extensions==4.7.1
urllib3==2.0.3
Installation
To run the Fancy Shop locally, follow the steps below:

Clone the repository to your local machine:

bash
Copy code
git clone <repository_url>
Change to the project directory:

bash
Copy code
cd fancy-shop
Create a virtual environment (optional but recommended):

Copy code
python3 -m venv venv
Activate the virtual environment:

On macOS and Linux:

bash
Copy code
source venv/bin/activate
On Windows:

Copy code
venv\Scripts\activate
Install the required dependencies:

Copy code
pip install -r requirements.txt
Set up the database:

Copy code
python manage.py migrate
Run the development server:

Copy code
python manage.py runserver
Visit http://localhost:8000 in your web browser to access Fancy Shop.

Online Website
To view the live deployment of Fancy Shop, visit the following website:

https://fancy-shop.onrender.com/

Features
Fancy Shop offers the following features:

User registration and authentication with Django Allauth.
Product browsing and filtering by category.
Add products to the cart and update quantities.
Secure checkout process with Stripe integration for payment processing.
Order history and tracking for registered users.
Responsive design with Bootstrap for an optimal viewing experience on different devices.
Commands
Here are some useful commands for running the Fancy Shop project:

Create a superuser (admin) account:

Copy code
python manage.py createsuperuser
Run tests:

bash
Copy code
python manage.py test
Collect static files:

Copy code
python manage.py collectstatic
Deployment
Fancy Shop is deployed using the following technologies:

Hosting: Render (https://render.com/)
Database: Postgres
File Storage: AWS
The live deployment can be accessed at https://fancy-shop.onrender.com/.

License
This project is licensed under the MIT License. Feel free to modify and distribute it as you like.

Acknowledgements
The Fancy Shop project utilizes the Django framework and integrates various technologies and libraries to provide a seamless online shopping experience. Special thanks to the contributors of the libraries and technologies used in this project.
