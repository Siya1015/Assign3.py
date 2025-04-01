# Assign3.py


# Question 1

def calculate_discount(price, discount_percent):

    if discount_percent >= 20:
        discount_price = price * (discount_percent * 0.01)
        return price - discount_price
    
    else:
        return price

# Question 2

price = 999.99 
discount_percent = 25  

# Calculate the final price
final_price = calculate_discount(price, discount_percent)


print(f"The final price after applying the discount is: {final_price:.2f}")



