## Python Web Framework

A website that displays sales data (uploaded from csv), generates charts and pdf reports, and supports user login/profile build up. 

Built with Python (Django), using pandas, matplotlib, seaborn, javascript, html, css, ajax, xhtml2pdf, dropzone.js, etc.

Install the packages:

`$ pip install -r requirements.txt`

To run the server: 

`$ python src/manage.py runserver`

Username `angel`

Password `123`

In order to manage models go to `/admin`

Uploading sales data from `.csv` only takes product items that are already registered in the system. It creates new customers automatically, though.
