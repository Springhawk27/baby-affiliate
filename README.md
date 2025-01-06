# Amazon Baby Products Affiliate Marketing

## Overview

This project is a Django-based website designed to promote Amazon baby products using affiliate links. The website dynamically displays a list of baby products, and each product has a detailed page that includes product information, an image, price, description, and an affiliate link to purchase the product on Amazon.

The site also includes pages like the "Home", "About", and "Contact" pages to give visitors a complete experience.

## Features

- Dynamic product listing with images, names, prices, and affiliate links.
- Product details page with in-depth product descriptions, pricing, and an affiliate link.
- Modular and reusable Django templates for consistent page layouts.
- Active navigation link highlighting for better user experience.
- Simple but effective CSS styling for a clean user interface.

## Technologies Used

- **Django**: The web framework used for building this project.
- **HTML5 & CSS3**: For front-end structure and styling.
- **SQLite**: The default database used by Django for this project (can be changed as needed).
- **Django Template Language (DTL)**: For dynamic rendering of the content.
- **Python**: The backend programming language for this project.

## Installation Guide

### Step 1: Clone the Repository

Clone this repository to your local machine.

```bash

git clone https://github.com/Springhawk27/baby-affiliate.git

python -m venv venv # run this command in the same folder

```

```bash

cd baby-affiliate

```

```bash

.\venv\Scripts\activate

```

```bash

pip install -r requirements.txt

```

```bash

python manage.py migrate

```

```bash

python manage.py createsuperuser


```

```bash

python manage.py runserver

```

```bash

http://127.0.0.1:8000/

```

```bash

http://127.0.0.1:8000/admin/

```

```bash

baby_affiliate/
│
├── baby_affiliate/          # Project settings
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── products/                # Products app
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── manage.py               # Django management script
├── requirements.txt        # List of dependencies
├── README.md               # Project overview and setup instructions
└── templates/               # HTML templates
    ├── base.html
    ├── product_list.html
    ├── product_detail.html
    └── about.html


```
