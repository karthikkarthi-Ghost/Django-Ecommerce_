# Django-Ecommerce_

# E-Commerce Site

This is a Django-based e-commerce web application designed to provide a full-fledged platform for buying and selling products. The application includes user authentication, product listing, shopping cart, and order management features.

## Features

- User Registration and Authentication
- Product Listing and Search
- Shopping Cart
- Order Management
- Payment Integration (to be added)
- Responsive Design

## Installation

### Prerequisites

- Python 3.x

### Clone the Repository

```bash
git clone https://github.com/karthikkarthi-Ghost/Django-Ecommerce_.git
cd Django-Ecommerce_
```

### Set Up Virtual Environment

```bash
pip install virtualenv
virtualenv env
```

#### For Mac/Linux

```bash
source env/bin/activate
```

#### For Windows

```bash
env\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Install Specific Versions to Avoid Conflicts

```python
pip install Django==2.2.4
python -m pip install django-allauth==0.40.0
pip install django-crispy-forms==1.7.2
pip install django-countries==5.5
pip install stripe==2.37.1
pip install Pillow
```

### Database Setup

Apply the migrations to set up the database.

```bash
python manage.py makemigrations
python manage.py migrate
```

### Run the Development Server

Start the server to see the application in action.

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your web browser.

### Create Superuser for Admin Login

```python
python manage.py createsuperuser
# Username: admin
# Password: 12345678
```

## Usage

1. **User Registration and Login:**
   - Users can register and log in to their accounts.
   - Admins can manage users from the Django admin panel.

2. **Product Management:**
   - Admins can add, update, and delete products.
   - Users can browse products and view details.

3. **Shopping Cart:**
   - Users can add products to their shopping cart.
   - Cart contents can be modified (add/remove items).

4. **Order Management:**
   - Users can place orders for the products in their cart.
   - Admins can view and manage orders.

## Contributing

We welcome contributions to improve this project. Here’s how you can help:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or need further assistance, feel free to reach out to us at:

- Email: karthikan3004@gmail.com
- GitHub: [karthikkarthi-Ghost](https://github.com/karthikkarthi-Ghost)
