# Algorithm Document

1. Prompt user: 'What is your subscription package? (Green, Blue or purple)'
    - Convert the input to lowercase


2. While the package input is invalid:
    - Output: 'Invalid input, please choose Green, Blue or Purple
    - Continue prompting the user until a valid input is given


3. Prompt user: ('What is the amount of data they used (in GB)') 
    - Ensure the input is a positive number.


4. If the input is invalid:
   - Continue to prompt the user ('Invalid input, please enter a positive number')


5. If the package is green:
    - ask if they have a coupon (yes/no)


6. Calculate the cost based on the package
    - If the package is green:
      - Base price is $49.99/month for 2GB of data
      - Additional cost is 15 GB for any data over 2GB
    - If the package is blue:
      - Base price is $70/month for 4GB of data
      - Additional cost is $10 per GB for any data over 4GB
    - If the package is purple:
      - Flat rate is $99.95/month for unlimited data


7. Apply discount:
   - If green cost > 75 
   - subtract 20 dollars from total


8. Calculate total cost:
    1. For Green and Blue the total cost = base price + additional cost
    2. For Purple the total cost = $99.95 


9. Output ('Your total bill is:', total cost)

