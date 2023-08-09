# Ecommerce Product Management API

This project is a Django REST framework (DRF) application that provides APIs for managing categories, subcategories, brands, and products for an ecommerce website. It allows you to create, update, and delete categories, subcategories, brands, and products, along with uploading images for each.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Django
- Django REST framework
- BeautifulSoup (for image scraping, if needed)
- Requests (for image scraping, if needed)

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

## Installation

1. Clone this repository:

```bash
git clone https://github.com/python-hacked/Ecommerce--API-Admin-site.git
cd ecommerce-product-management-api
```

2. Create a virtual environment (recommended):

```bash
python -m venv venv
```

3. Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```

- On macOS/Linux:

```bash
source venv/bin/activate
```

4. Install project dependencies:

```bash
pip install -r requirements.txt
```

5. Run database migrations:

```bash
python manage.py migrate
```

6. Start the development server:

```bash
python manage.py runserver
```

## Usage

1. Open your web browser and navigate to `http://127.0.0.1:8000/admin/` to access the Django admin interface.
2. Log in using the admin credentials or create a superuser using `python manage.py createsuperuser`.
3. Use the admin interface to manage categories, subcategories, brands, and products.

## API Endpoints

- **Categories API**: `/api/categories/`
- **Subcategories API**: `/api/subcategories/`
- **Brands API**: `/api/brands/`
- **Products API**: `/api/products/`

Use these API endpoints to create, update, and delete categories, subcategories, brands, and products. You can also upload images for each entity using these APIs.

