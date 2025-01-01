# shopping-system
new system
new code for customer shopping 
Code Fragment:

purchase_amounts = [random.randint(100, 1000) for _ in range(500)]  
for amount in purchase_amounts:
    if amount > 500:
        discount = 0.20  # 20% discount
    else:
        if amount >= 200:
            discount = 0.10 
        else:
            discount = 0.00 
    
    discounted_price = amount - (amount * discount)  
    print(f"Original Amount: {amount}, Discounted Price: {discounted_price:.2f}")


this will expaire date 30/1/2025
