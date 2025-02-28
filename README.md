# E-Commerce Food Restaurant Platform

This e-commerce platform is developed using **Django** and **Python** to efficiently manage online restaurant services. It provides comprehensive features for providers, customers, and administrators, ensuring a seamless user experience.

## ✨ Key Features
- **Custom User Model** – Supports authentication and authorization for providers, customers, and administrators.
- **File Management** – Integrates Django Signals for file upload and management.
- **User Registration & Authentication** – Separate registration for providers, customers, and administrators, with admin approval required for providers.
- **Intuitive Dashboards** – User-friendly interface with Google autocomplete for an enhanced experience.
- **CRUD Functionalities** – Manage food categories and menu items using Bootstrap for the frontend.
- **AJAX-Powered Shopping Cart** – Smooth experience for adding and managing items in the cart.
- **Location-Based Search** – Google Maps API and GIS integration to find nearby restaurants.
- **Dynamic Operating Schedule** – Interactive schedule management using AJAX and PostgreSQL.
- **Order & Checkout System** – Order model implementation and checkout page with **PayPal** integration.
- **Email Notifications** – Configured and integrated email notifications for confirmations.
- **Profile Customization** – Personalized profile forms with user data validation.
- **Mobile Compatibility** – Optimized UI using Bootstrap for a seamless mobile experience.

---

## 🚀 Installation & Setup

### 🔹 1. Prerequisites
Ensure you have the following installed:
- **Python 3.11**
- **PostgreSQL**

### 🔹 2. Installation Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/mihaidevexplorer/e-commerce_food_restaurant.git
   cd e-commerce_food_restaurant
   ```
2. Create a virtual environment:
   ```sh
   pip install virtualenv
   virtualenv env
   ```
3. Activate the virtual environment:
   - On **Windows**:
     ```sh
     env\Scripts\activate
     ```
   - On **Mac OS / Linux**:
     ```sh
     source env/bin/activate
     ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### 🔹 3. Configuration
1. Create a `.env` file inside the **foodOnline_main** directory and add the following settings:
   ```sh
   SECRET_KEY=your_secret_key
   DEBUG=True
   ```

#### Database Configuration
   ```sh
   DB_NAME=your_db_name
   DB_USER=postgres
   DB_PASSWORD=your_password
   DB_HOST=localhost
   ```

#### Email Configuration
   ```sh
   EMAIL_HOST=smtp.gmail.com
   EMAIL_PORT=587
   EMAIL_HOST_USER=your_email
   EMAIL_HOST_PASSWORD=your_email_password
   ```

#### API Keys
   ```sh
   GOOGLE_API_KEY=your_google_api_key
   PAYPAL_CLIENT_ID=your_paypal_client_id
   ```

### 🔹 4. Apply Database Migrations
```sh
python manage.py migrate
```

### 🔹 5. Run the Local Server
```sh
python manage.py runserver
```

---

## 📦 Dependencies
Main dependencies used in this project:
- Django 4.2.6
- PostgreSQL (psycopg2-binary)
- Google Maps API (GDAL)
- Bootstrap for frontend styling
- AJAX for interactivity
- PayPal for online payments

The full list of dependencies is available in the `requirements.txt` file.

---

## 🔥 Contributing
Contributions are welcome! Follow these steps to add a new feature:
1. **Fork** the repository
2. Create a new branch for your feature:
   ```sh
   git checkout -b feature/your-new-feature
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m "Add new feature X"
   ```
4. Push the changes to your forked repository:
   ```sh
   git push origin feature/your-new-feature
   ```
5. Create a **Pull Request** and wait for review.

---

## 📜 License
This project is open-source and licensed under the **MIT License**.

---

If you have any questions or suggestions, feel free to open an issue or contribute to the project! 🚀







  

  


