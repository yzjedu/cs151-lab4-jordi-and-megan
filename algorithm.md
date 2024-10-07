# Algorithm Document

1. Prompt user: ('What is your subscription package? (Green, Blue or purple)')
2. If the input is invalid
   1. continue to prompt the user 'Invalid input, please choose Green, Blue or Purple
3. If the inout is valid continue
4. Prompt user: ('What is the amount of data they used (in GB)') 
5. If the input is invalid:
   1. continue to prompt the user ('Invalid input, please enter a positive number')
6. If input is valid continue
7. Check for coupon
8. If the user has a green package:
   1. ask if they have a coupon (yes/no)
9. Calculate the cost based on the package
10. For package Green:
    1. Base price is $49.99/month for 2GB of data
    2. Additional cost is 15 GB for any data over 2GB
11. If the total bill is > 75 and the customer has a coupon:
    1. subtract $20 from the total
12. For package blue: 
    1. Base price is $70/month for 4GB of data
    2. Additional cost is $10 per GB for any data over 4GB
13. For package Purple:
    1. Flat rate is $99.95/month for unlimited data
14. Calculate total cost:
    1. For Green and Blue the total cost = base price + additional cost
    2. For Purple the total cost = $99.95
15. Output ('Your total bill is:', total cost)

