# Ecommerce-Store
This is a general-purpose Ecommerce store model ready to be adapted and modified to fit any ecommerce business.  
## Store
![Ecom-Store](https://github.com/Danogbans/Ecommerce-Store/assets/89392668/22ffcf34-1be0-4c56-8d29-764c6080713c)
## Cart
![Ecom-Cart](https://github.com/Danogbans/Ecommerce-Store/assets/89392668/6d25af37-1f3b-4f0a-930a-d854fc6bc1d3)
## Checkout
![Ecom-Checkout](https://github.com/Danogbans/Ecommerce-Store/assets/89392668/55005394-4c8b-4f96-8951-12d3a00cb451)    

## Motivations
I love Python and becoming a Python developer had always been my dream.  
Now that I am one, becoming one of the best in the game is yet another huge dream which I pursue every minute of my life.  
At the moment of writing this readme doc, I am a junior Python developer with 16 months programming experience working extremely          
hard to becoming a senior Python developer in a short period of time, perhaps in 1 year if possible.  
The hunger to learn, grow, be one of the best and get to the top is my motivation.    
             
             if python:       
                 stayHungry = True  
                 
## Lessons Learned
This 2-month project has been a very challenging one. 
The journey drove me deeper into more advanced pythonic web development concepts like:       
- How to render products and add image fields to product models.
- Advanced database modeling: one to many & many to many relationships.  
- An introduction to JavaScript.
- How to write functions in JavaScript.
- How to add event handlers in JavaScript.
- How to set cookies in JavaScript.
- How to work with Python decorators. 
- How to create a checkout form and logic.
- How to integrate payment solutions to a website or an application. 

Some of the challenges I faced creating this Ecommerce store was getting stuck so many times. 
I had to find my way out by googling up information and tutorials, 
books (Django for professionals, Automate the boring stuff with Python, Python crash course), 
using stack overflow and django documentation e.t.c  

## Installation
1 . Clone the repository 
```bash
  git clone https://github.com/<username>/<forked-repo>.git
```
2 . Create your own virtual environment

```bash
  python3 -m venv venv
source venv/bin/activate
```
3 .  Install your requirements
```bash
  pip install -r requirements.txt
```
4 .  Create a new mySQL database
```bash
  CREATE DATABASE databasename
$ \connect databasename
```
5 . Generate a new secret key
6 . Rename the Project

7 . Make your migrations.
The only migrations that should appear in each of your app’s migrations folders are called ‘__init__.py’. 
As we have started a new database, we can delete any existing migrations and migrate from scratch.
```bash
   python manage.py makemigrations
$ python manage.py migrate
```
8 . Create a new superuser
```bash
 python manage.py createsuperuser 
```
9 . Start the development server and ensure everything is running without errors.
```bash
 python manage.py runserver
```
## Features
- Login Users
- Logout Users
- Store
- Add to cart
- Cart
- Cart total
- Update cart
- Checkout
- Guest checkout
- Process orders
- Shipment
- cookies 
- Payment gateways  
- 
## Tech Stack
**Client:** HTML5, CSS3, Bootstrap4, JavaScript

**Server:** Python, Django

**Database:** SQLite3

