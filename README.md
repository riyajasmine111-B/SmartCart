# SmartCart Billing System in C

## Project Description
SmartCart is a simple billing system developed using the C programming language. It calculates customer discounts, delivery charges, and the final payable amount based on the purchase amount, customer type, and delivery distance.

## Features
- Accepts the purchase amount from the user.
- Identifies student and regular customers.
- Calculates discounts according to customer type and purchase amount.
- Calculates delivery charges based on delivery distance.
- Displays the final bill.
- Validates negative inputs and invalid customer types.

## Discount Rules

### Student Customers
- Purchase amount of Rs. 2000 or above: 15% discount.
- Purchase amount below Rs. 2000: 10% discount.

### Regular Customers
- Purchase amount of Rs. 3000 or above: 8% discount.
- Purchase amount below Rs. 3000: No discount.

## Delivery Charges
- Distance up to 5 km: Rs. 40.
- Distance above 5 km and up to 15 km: Rs. 70.
- Distance above 15 km: Rs. 100.

## Technologies Used
- Programming Language: C
- Header File: `stdio.h`
- Concepts: Variables, input/output, `if-else`, `switch-case`, and arithmetic operations.

## How to Run the Program
1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Compile the program using GCC:

   `gcc smartcart.c -o smartcart`

4. Run the program:

   - Windows: `smartcart.exe`
   - Linux/macOS: `./smartcart`

5. Enter the purchase amount, customer type, and delivery distance when prompted.

## Sample Output

```text
Enter purchase amount: 2500
Enter customer type (1-Student, 2-Regular): 1
Enter delivery distance in km: 8

===== SMARTCART BILL =====
Purchase Amount       : Rs. 2500.00
Discount              : Rs. 375.00
Amount After Discount : Rs. 2125.00
Delivery Charge       : Rs. 70.00
Final Payable Amount  : Rs. 2195.00
```

## Output Screenshots
See the `screenshots` folder for screenshots of the program output.

## Author
B Riya Jasmine 
