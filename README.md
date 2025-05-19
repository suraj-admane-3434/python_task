# python_task
#######################task 1#####################

# Step 1: Take integer input from the user
number = int(input("Enter an integer: "))

# Step 2: Check if the number is even or odd
if number % 2 == 0:
    # Step 3: Display result for even number
    print(f"{number} is even.")
else:
    # Step 3: Display result for odd number
    print(f"{number} is odd.")

    ################################task 2#################################

    # Initialize the sum to 0
total_sum = 0

# Use a for loop to iterate over numbers from 1 to 50
for number in range(1, 51):
    total_sum += number  # Add each number to the total sum

# Display the final sum
print("The sum of integers from 1 to 50 is:", total_sum)
