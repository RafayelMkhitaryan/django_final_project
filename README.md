# E-Commerce Django Project

📖 About the Project

This is a fully functional E-Commerce web application built using Django. It provides a seamless shopping experience for users, allowing them to browse products, add them to a cart, and complete orders securely. The project includes essential features like authentication, email notifications, and an admin panel for managing the store efficiently.

## 🚀 Features
- **CRUD Operations**: Manage products, categories, orders, and users.
- **Authentication & Authorization**: Secure login, registration, password reset, and role-based access control.
- **Email Notifications**: Send emails for order confirmations, password resets, and promotions.
- **Cart & Checkout**: Add to cart, manage orders, and process payments.
- **Admin Dashboard**: Manage users, products, and orders using Django Admin.

## 🛠 Tech Stack
- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite
- **Authentication**: Django Auth
- **Email**: SMTP / Django Email Backend

## 📦 Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ecommerce-django.git
   cd ecommerce-django
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

## 📧 Email Configuration


## 🔑 Authentication
- User registration & login using Django authentication.
- Password reset via email.
- Role-based access control for admin and customers.


## 📜 License
This project is licensed under the MIT License.

