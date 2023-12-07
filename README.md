# python4
def is_even(number):
    return number % 2 == 0

# Example usage:
user_input = int(input("Enter a number: "))

if is_even(user_input):
    print(f"{user_input} is an even number.")
else:
    print(f"{user_input} is an odd number.")
