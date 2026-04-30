# Restaurant-Data-Table
This project includes a simple SQL database table for storing restaurant information and its a addon to my cat cafe website.The table is designed for a restaurant, cafe, or small food business website. It can store basic details like the restaurant name, cuisine type, contact information, address, hours, delivery options, reservations, and customer rating.


Files
restaurant_database.sql - Creates the restaurants table and adds one sample restaurant record.
index.html - Existing restaurant/cafe website page.
styles.css - Website styling.
script.js - Website animation behavior.
Table Name
restaurants
Columns
Column	Description
restaurant_id	Unique ID for each restaurant
name	Restaurant name
cuisine_type	Type of food or business, such as Cafe and Bakery
phone_number	Restaurant phone number
email	Restaurant email address
street_address	Street address
city	City
state	State
zip_code	ZIP code
opening_time	Opening time
closing_time	Closing time
price_range	Price level, such as $, $$, or $$$
has_delivery	Uses 1 for yes and 0 for no
has_reservations	Uses 1 for yes and 0 for no
rating	Restaurant rating from 0 to 5
created_at	Date and time the record was created
How To Use
If you have SQLite installed, you can create the database by running:
