# codeacademy_project1a
#codeacademy_first_project
lovely_loveseat_description = """
			Lovely Loveseat. 
Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."""
lovely_loveseat_price = float(254.00)
stylish_settee_description = """
			Stylish Settee. 
Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."""
stylish_settee_price = float(180.50)
print(lovely_loveseat_price)
luxurious_lamp_description = """"
			Luxurious Lamp. 
Glass and iron. 36 inches tall. Brown with cream shade."""
luxurious_lamp_price = float(52.15)
sales_tax = float(0.088)
customer_one_total = 0
customer_one_itemization = ""
customer_one_itemization += str(lovely_loveseat_description)
customer_one_total += lovely_loveseat_price
customer_one_total +=luxurious_lamp_price
customer_one_itemization += luxurious_lamp_description 
customer_one_tax = customer_one_total * sales_tax
customer_one_total +=customer_one_tax
print("Custom One items:")
print(customer_one_itemization)
print("Customer One Total:")
print(customer_one_total)
customer_two_total = 0
customer_two_itemization = str("")
customer_two_total +=stylish_settee_price
customer_two_itemization += stylish_settee_description
customer_two_total +=luxurious_lamp_price
customer_two_itemization +=luxurious_lamp_description
customer_two_tax = customer_two_total *sales_tax
customer_two_total += customer_two_tax
print("""

""")
print("Customer 2 Items:")
print(customer_two_itemization)
print("Customer Two Total:")
print(customer_two_total)
