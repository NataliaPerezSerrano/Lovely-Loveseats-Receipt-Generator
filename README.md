# Lovely-Loveseats-Receipt-Generator
A simple Python program for a furniture shop that stores product names and prices, tracks customer purchases, calculates totals, and prints formatted receipts. A beginner-friendly project focused on variables, strings, and basic arithmetic.

# create the descritpion of an item
lovely_loveseat_description = 'Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white.'

#price for the item
lovely_loveseat_price = 254.00
 #another item description
stylish_settee_description = "Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."

#price of the item
stylish_settee_price = 180.50

#antoher item description
luxurious_lamp_description= 'Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade.'

#price of the item
luxurious_lamp_price = 52.15

#tax
sales_tax = 0.088

#first customer
customer_one_total = 0
customer_one_total = lovely_loveseat_price + luxurious_lamp_price

customer_one_itemization = ""
customer_one_itemization = lovely_loveseat_description + " " + luxurious_lamp_description

customer_one_tax = customer_one_total * sales_tax

customer_total_cost = customer_one_total + customer_one_tax


print(f'Customer One Items')
print(customer_one_itemization)
print(f"Customer One Total:")
print(customer_total_cost)
