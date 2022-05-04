Market place - electronics store
Inspired by Technodom.

Goal
The main aim of the project is to represent an online platform for sale with quick and understandable requests.

APPS
The market place consists of 4 apps and one package with general constants and other things.

auth_
core
market
payments
Description
“auth_” application represents requests related to user authentication.

“core” includes basic models, queries that form the basis of an online store.

“market” consists of goods with certain characteristics, properties complementary to the product, as well as the integration of the user directly with the system by giving feedback.

“payments” application speaks for itself, it provides endpoints that help to order the delivery of a certain item.

It’s also used popular packages that put together a framework for the entire application.

Draft guidlines
Install django project
Create, configure and activate virtual environment
Install all packages by the following command
pip install -r requirements.txt
Create a table with fields
python manage.py migrate
Enjoy!
