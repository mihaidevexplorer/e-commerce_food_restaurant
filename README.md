# E-Commerce Platform for Online Restaurant Services

This project is an e-commerce platform developed using Django and Python, designed to manage online restaurant services efficiently. The platform offers comprehensive features for providers, customers, and vendors, ensuring a seamless and engaging user experience.

## Features

- **Custom User Model**: Handles authentication and authorization for providers, customers, and vendors.
- **File Upload Management**: Utilizes Django Signals to integrate file upload and management functionalities.
- **User Registration & Authentication**: Includes provider, customer, and vendor registration and authentication with administrator approval for providers and vendors.
- **Dashboards & UX Enhancements**: Provides user-friendly dashboards and integrates Google autocomplete for improved user experience.
- **CRUD Functionalities**: Manages food categories and products within the menu using Bootstrap templates for the frontend.
- **Shopping Cart**: Implements a smooth, AJAX-powered shopping cart for an enhanced shopping experience.
- **Location-Based Search**: Integrates location-based search functionalities to find nearby restaurants using Google Maps API and GIS.
- **Dynamic Operating Schedule**: Develops a dynamic operating schedule module with AJAX, integrated with a PostgreSQL database.
- **Order Model & Checkout**: Implements the order model and checkout page with PayPal payment gateway integration.
- **Email Notifications**: Configures and integrates email templates for confirmations and notifications.
- **Profile Customization**: Customizes profile form configuration and validates user data.
- **Mobile Compatibility**: Optimizes the website for mobile compatibility and responsiveness using Bootstrap for the frontend.

### Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Python 3.11
- PostgreSQL

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/mihaidevexplorer/e-commerce_food_restaurant.git
   cd e-commerce_food_restaurant

  ## Instructions for Setting Up the Environment

### 2. Install the Environment Control
```sh
pip install virtualenv
virtualenv env


  ### 3. Activate the environment
  ### On Windows:
  env\Scripts\activate

### On Mac OS / Linux:
source env/bin/activate

### 4. Install the dependencies
pip install -r requirements.txt

#### Dependencies
Here is a list of dependencies that need to be installed:

- asgiref==3.7.2
- beautifulsoup4==4.12.2
- certifi==2023.11.17
- charset-normalizer==3.3.2
- Django==4.2.6
- docopt==0.6.2
- GDAL @ file:///C:/Users/admin/pipwin/GDAL-3.4.3-cp311-cp311-win_amd64.whl#sha256=f78861fb5115d5c2f8cf3c52a492ff548da9e1256dc84088947379f90e77e5b6
- idna==3.4
- Js2Py==0.74
- packaging==23.2
- Pillow==10.0.1
- pipwin==0.5.2
- psycopg2-binary==2.9.9
- pyjsparser==2.7.1
- PyPrind==2.11.3
- pySmartDL==1.3.4
- python-decouple==3.8
- requests==2.31.0
- simplejson==3.19.2
- six==1.16.0
- soupsieve==2.5
- sqlparse==0.4.4
- tzdata==2023.3
- tzlocal==5.2
- urllib3==2.1.0


#### Configuration
#### Create a .env file in the foodOnline_main folder with the following content:
  SECRET_KEY=
  DEBUG=True

#### Database configuration
DB_NAME=DB
DB_USER=postgres
DB_PASSWORD=Your password
DB_HOST=localhost

#### Email configuration
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_HOST_USER=' '
EMAIL_HOST_PASSWORD=' '

#### API Keys
GOOGLE_API_KEY=
PAYPAL_CLIENT_ID=

#### Apply migrations
python manage.py migrate

#### Run the server
python manage.py runserver

#### Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

### Fork the Project
 Create your Feature Branch (git checkout -b feature/AmazingFeature)
 Commit your Changes (git commit -m 'Add some AmazingFeature')
 Push to the Branch (git push origin feature/AmazingFeature)
 Open a Pull Request






  

  


